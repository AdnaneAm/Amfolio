<template>
    <nav id="navbar">
        <div id="nav-logo"></div>
        <ul>
            <li><a href="#education">Education</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    #navbar{
        background:#fff;
        ul{
            height:70px;
            border-bottom:1px solid #000;
            text-align:right;
            padding-right:3rem;
            li{
                display:inline-block;
                margin  :.5rem 1rem;
                a{
                    color:#000 !important;
                    text-decoration: none;
                    background:grey;
                    padding:.5rem 1rem;
                }
            }
        }
    }
</style>