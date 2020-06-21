<template>
  <section id="hero">
    <div class="container">
      <div class="hero-text">
        <h2>Hello, I'm</h2>
        <h1>AMEZIANE <br>Adnane</h1>
        <h2>Full Stack Web Developer</h2>
      </div>
      <div class="hero-img">
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
#hero {
  background: $bg-secondary;
  position: relative;
  z-index: -10;
  .container {
    align-content: flex-start;
    flex-wrap: wrap;
  }
  .hero-text {
    flex: 3;
    h1 {
      font-family: serif;
      font-size: 4rem;
      line-height:4rem;
      font-weight: 800;
      margin:.5rem 0 2rem 0;
      &:after {
        content: ".";
        color: $primary;
        font-size: 4rem;
        margin-left: 0.5rem;
      }
    }
    h2:first-child{
        font-size: 1.7rem;
        margin-left: 0.4rem;
        font-weight: 400;
        color: #9fb1bd;
    }
    h2:last-child{
        font-size:1.5rem;
        color:#000;
        position:relative;
        &::after{
            content:'';
            width:50px;
            height:4px;
            background:$primary;
            position:absolute;
            left:0;
            bottom:-5px;
        }
    }
  }
  .hero-img {
    flex-basis: 400px;
    position: relative;
    text-align: center;
    background-image: url(https://www.pngonly.com/wp-content/uploads/2017/06/Man-Happy-PNG-Picture.png);
    background-size: 500px;
    background-position: -30px -41px;
    border-radius: 0 0 30% 0;
    background-position-x: 34px;
    background-repeat: no-repeat;
    height: 330px;
    margin-left: 2rem;
    right: 30px;
    &::after {
      content: "";
      width: 300px;
      height: 300px;
      border-radius: 50%;
      background: #3498db;
      position: absolute;
      z-index: -1;
      left: 123px;
      bottom: -1px;
    }
  }
  svg {
    fill: $bg-secondary;
  }
}
</style>
