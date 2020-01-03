<template>
    <main> 
        <nav-bar/>
        <hero-header
            class="hero"
        />
    </main>
</template>

<script>
import NavBar from '../components/NavBar'
import HeroHeader from '../components/HeroHeader'

export default {
    name: 'Home',
    components:{
        NavBar,
        HeroHeader
    }
}
</script>

<style>
  h1{
        color: #344491!important;
        font-family: Bw Modelica;
        font-style: normal;
        font-weight: 800;
        font-size: 61px;
        line-height: 144.5%;
    }
.col-7{
    margin-left:3%;
    display:flex;
    align-items:center;
}
main{
    background-color:#FFDE8F;
}
</style>