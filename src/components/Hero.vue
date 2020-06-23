<template>
  <section id="hero">
    <div class="hero-bg"></div>
    <div class="container">
      <div class="hero-text section-left-content">
        <!-- 
        <div class="thumbnail">
            <img class="thumbnail-image" src="https://imgur.com/fvDiqkR.jpg">
            <div class="thumbnail-ring"></div>
        </div>
        -->
        <h2>Hello, I'm</h2>
        <h1>AMEZIANE <br />Adnane</h1>
        <h2>Full Stack Web Developer</h2>
      </div>
      <div class="section-right-content">
        <div class="sub-section">
          <h2>About Me</h2>
          <div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta doloribus nulla esse molestiae ea ducimus ex minima fugiat obcaecati, accusamus reprehenderit libero laudantium, consequatur adipisci temporibus alias dolore facere delectus. Quasi nemo voluptas veritatis, a veniam molestiae magni magnam, mollitia aut doloremque distinctio perspiciatis exercitationem soluta fugiat. Incidunt, deserunt possimus?</p>
          </div>
        </div>
        <div class="sub-section">
          <h2>Objective</h2>
          <div>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Id, labore omnis libero nobis vel deleniti et doloremque numquam corporis incidunt aspernatur minima quae fuga, molestiae voluptatem natus molestias, inventore fugit.</p>
          </div>
        </div>
        <div class="sub-section">
          <h2>Social Media</h2>
          <div>
            <a href="">
              <svg height="682pt" viewBox="-21 -35 682.66669 682" width="682pt" xmlns="http://www.w3.org/2000/svg"><path d="m77.613281-.667969c-46.929687 0-77.613281 30.816407-77.613281 71.320313 0 39.609375 29.769531 71.304687 75.8125 71.304687h.890625c47.847656 0 77.625-31.695312 77.625-71.304687-.894531-40.503906-29.777344-71.320313-76.714844-71.320313zm0 0"/><path d="m8.109375 198.3125h137.195313v412.757812h-137.195313zm0 0"/><path d="m482.054688 188.625c-74.011719 0-123.640626 69.546875-123.640626 69.546875v-59.859375h-137.199218v412.757812h137.191406v-230.5c0-12.339843.894531-24.660156 4.519531-33.484374 9.917969-24.640626 32.488281-50.167969 70.390625-50.167969 49.644532 0 69.5 37.851562 69.5 93.339843v220.8125h137.183594v-236.667968c0-126.78125-67.6875-185.777344-157.945312-185.777344zm0 0"/></svg>
            </a>
            <a href="">
              <svg id="Bold" enable-background="new 0 0 24 24" height="512" viewBox="0 0 24 24" width="512" xmlns="http://www.w3.org/2000/svg"><path d="m15.997 3.985h2.191v-3.816c-.378-.052-1.678-.169-3.192-.169-3.159 0-5.323 1.987-5.323 5.639v3.361h-3.486v4.266h3.486v10.734h4.274v-10.733h3.345l.531-4.266h-3.877v-2.939c.001-1.233.333-2.077 2.051-2.077z"/></svg>
            </a>
            <a href="">
              <svg version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                width="95.802px" height="95.802px" viewBox="0 0 95.802 95.802" style="enable-background:new 0 0 95.802 95.802;"
                xml:space="preserve">
                  <path d="M38.664,44.689c0,0,9.065-0.673,9.065-11.306c0-10.632-7.417-15.819-16.813-15.819H13.622h-0.508H0v59.414h13.114h0.508
                    h17.294c0,0,18.873,0.597,18.873-17.536C49.79,59.442,50.613,44.689,38.664,44.689z M13.622,28.125h15.069h2.226
                    c0,0,4.203,0,4.203,6.181c0,6.181-2.473,7.077-5.275,7.077H13.622V28.125z M30.119,66.42H13.622V50.541h17.294
                    c0,0,6.264-0.08,6.264,8.16C37.18,65.572,32.599,66.351,30.119,66.42z"/>
                  <rect x="62.18" y="21.064" width="24.514" height="7.317"/>
                  <path d="M74.961,32.682c-22.848,0-22.828,22.826-22.828,22.826s-1.566,22.713,22.829,22.713c0,0,20.331,1.162,20.331-15.801
                    H84.837c0,0,0.349,6.391-9.526,6.391c0,0-10.455,0.699-10.455-10.34h30.785C95.641,58.471,99.009,32.682,74.961,32.682z
                    M84.255,50.541H64.738c0,0,1.277-9.158,10.455-9.158C84.372,41.382,84.255,50.541,84.255,50.541z"/>
              </svg>
            </a>
          </div>
        </div>
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
  height:calc( 100vh - 63px );
  z-index: -10;
  clip-path: polygon(19% 99%, 0% 83%, 0% 0%, 100% 0%, 100% 91%);
  .hero-bg{
    position:absolute;
    width:100%;
    height:100%;
    background:url('https://images.unsplash.com/photo-1541256942802-7b29531f0df8?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2850&q=80');
    background-size:cover;
    filter:brightness(.3);
    z-index: -1;
    top:0;
    left:0;
  }
  .container {
    align-content: flex-start;
    flex-wrap: wrap;
    .hero-text {
      h1 {
        font-family: $font-secondary;
        font-size: 6rem;
        line-height: 6rem;
        font-weight: 800;
        margin: 0.5rem 0 2rem 0;
        color:#fff;
        &:after {
          content: ".";
          color: $primary;
          font-size: 4rem;
          margin-left: 0.5rem;
        }
      }
      h2:first-of-type {
        font-size: 1.7rem;
        margin-left: 0.4rem;
        font-weight: 400;
        color:#fff;
      }
      h2:last-of-type {
        font-size: 1.5rem;
        color: #fff;
        position: relative;
        margin-bottom:4rem;
        &::after {
          content: "";
          width: 50px;
          height: 4px;
          background: $primary;
          position: absolute;
          left: 0;
          bottom: -5px;
        }
      }
    }
    .section-right-content{
      .sub-section{
        margin-bottom:2rem;
        h2{
          color: #fff;
          font-family: "Abril FatFace", sans-serif;
          font-size: 1.5rem;
          font-weight: 600;
          letter-spacing: 0.2rem;
          position: relative;
          margin:0 0 .5rem 2rem ;
          &::before{
            content: "";
            width: 20px;
            height: 3px;
            position: absolute;
            bottom: 12px;
            left: -30px;
            background: #fff;
          }
        }
        div{
          p{
            color:$hero-grey;
            font-size: 1.2rem;
            line-height: 1.5rem;
          }
          a{
            display: inline-block;
            padding:.5rem .8rem;
            border:2px solid $hero-grey;
            margin-right:1.5rem;
            cursor:pointer;
            svg{
              width: 20px;
              height: 20px;
              fill: $hero-grey;
            }
          }
        }
        &:last-of-type{
          h2{
            margin-bottom:1rem;
          }
        }
      }
    }
  }
}
.thumbnail{
  position: relative;
  width: 160px;
  height: 160px;
  overflow: hidden;
  &-image {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    z-index: 3;
    position: relative;
    top: 20px;
    left: 20px;
  }
  &-ring {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    background: linear-gradient(90deg, rgba(255, 255, 255, 0.2) 0%, rgba(0, 0, 0, 0) 20%, rgba(0, 0, 0, 0) 80%, rgba(255, 255, 255, 0.2) 100%);
    z-index: 2;
    box-shadow: 4px 0 2px -4px rgba(255, 255, 255, 0.9), -4px 0 2px -4px rgba(255, 255, 255, 0.9);
    position: absolute;
    top: 10px;
    left: 10px;
    &-outer {
      width: 200px;
      height: 200px;

    }
  }
}
</style>
