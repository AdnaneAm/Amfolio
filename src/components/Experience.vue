<template>
  <section id="experience">
    <div class="container">
      <div class="section-right-content"></div>
      <div class="section-left-content">
        <h1 class="section-heading">Experience</h1>
        <ul>
          <li class="section-item">
            <span>2010-2011</span>
            <div>
              <span>Graphic Designer</span>
              <span>Polygon Company</span>
            </div>
          </li>
          <li class="section-item">
            <span>2011-2014</span>
            <div>
              <span>Front-End Developer</span>
              <span>SPACE X</span>
            </div>
          </li>
          <li class="section-item">
            <span>2014-2017</span>
            <div>
              <span>Full-Stack Developer</span>
              <span>Tnasoq</span>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
#experience {
  background: $bg-secondary;
  .section-left-content {
    margin-right: 0;
  }
  .section-right-content {
    margin-right: 6rem;
    background-image: url("https://images.unsplash.com/photo-1529400971008-f566de0e6dfc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1650&q=80");
    position: relative;
    z-index: 1;
    border-radius: 1rem;
    border: 20px solid darken($bg-secondary, 2%);
    &::after {
      content: "";
      width: 100px;
      height: 100px;
      background: $primary;
      border: none;
      z-index: -10;
      position: relative;
      top: -100px;
    }
  }
}
</style>
