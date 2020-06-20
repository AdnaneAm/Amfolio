<template>
    <section id="hero">
        <div class="container">
            <div class="hero-text">
                <h1>AMFOLIO</h1>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Commodi velit, accusantium odit quis doloremque nam cumque veritatis obcaecati enim porro sit repudiandae id nesciunt ex assumenda quod dignissimos harum ipsum, voluptates natus? Quibusdam officiis beatae voluptate. Sit voluptas adipisci consectetur.</p>
            </div>
            <div class="hero-img">
            </div>
        </div>
    </section>

</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    #hero{
        background:$bg-secondary;
        padding:3rem 0;
        position: relative;
        z-index: -10;
        .container{
            align-content: flex-start;
            flex-wrap:wrap;
        }
        .hero-text{
            flex:3;
            h1{
                font-family:$font-primary;
                font-size:2.5rem;
                font-weight: 800;
                margin-bottom:1.2rem;
                &:after{
                    content:'.';
                    color:$primary;
                    font-size:4rem;
                    margin-left:.5rem;
                }
            }
            p{
                color:$txt-secondary;
                font-size:1.2rem;
                width: 80%;
                line-height: 1.8rem;
            }
        }
        .hero-img{
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
            right:30px;
            &::after{
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
        svg{
            fill:$bg-secondary;
        }
    }
</style>