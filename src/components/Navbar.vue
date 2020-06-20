<template>
    <nav id="navbar">
        <div class="container">
            <div id="nav-logo"></div>
            <ul>
                <li><a href="#education">Education</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    #navbar{
        background:$bg-primary;
        ul{
            margin-left:auto;
            li{
                display:inline-block;
                a{
                    color:#5b5d61 !important;
                    font-weight:600;
                    text-decoration: none;
                    display: inline-block;
                    padding:1.5rem 1rem;
                    transition:all .3s ease-in-out;
                    &:hover{
                        background: $bg-secondary;
                    }
                }
            }
        }
    }
</style>