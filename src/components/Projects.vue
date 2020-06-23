<template>
  <section id="projects">
    <div class="container">
      <h1 class="section-heading">Projects</h1>
      <div v-for="project in projects" :key="project.id" class="project">
        <div class="project-bg"></div>
        <div class="project-text">
          <h2 class="project-heading">{{ project.name }}</h2>
          <p class="project-description">
            {{ project.description }}
          </p>
          <button class="visit-repo">
            <a :href="`${project.html_url}`" target="_blank"
              >Go to repository</a
            >
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      projects: []
    };
  },
  created() {
    fetch("https://api.github.com/users/adnaneam/repos")
      .then(res => res.json())
      .then(res => {
        this.projects = res;
        console.log(res);
      })
      .catch(err => {
        console.log(err);
      });
  }
};
</script>

<style lang="scss" scoped>
#projects {
  .container {
    flex-wrap: wrap;
    justify-content: space-around;
  }
  h1 {
    width: 100%;
  }
  .project {
    flex-basis: 300px;
    border-radius: 1rem;
    margin: 1rem;
    box-shadow: 0px 7px 30px -5px rgba(0, 0, 0, 0.05);
    .project-bg {
      height: 150px;
    }
    .project-text {
      padding: 2rem;
      .project-heading {
        font-size: 1.8rem;
        font-weight: 500;
        margin: 0.5rem 0 0.3rem 0;
        text-transform: capitalize;
        &::after {
          content: "";
          width: 50px;
          height: 3px;
          background: $primary;
        }
      }
      .project-description {
        font-size: 1.2rem;
        color: lighten($txt-secondary, 3%);
      }
      .visit-repo {
        background: none;
        border: 2px solid black;
        border-radius: 1rem;
        margin: 1rem 0 0.3rem 0;
        a {
          padding: 0.3rem 0.5rem;
          font-weight: 600;
          display: inline-block;
          color: black;
        }
      }
    }
  }
  .project:last-child {
    justify-self: flex-start;
  }
}
</style>
