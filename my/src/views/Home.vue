<template>
    <main> 
        <nav-bar
            class="hero"/>
        <hero-header
            class="hero"
        />
        <explore-moods
            class="explore-moods"
        />
    </main>
</template>

<script>
import NavBar from '../components/sections/NavBar'
import HeroHeader from '../components/sections/HeroHeader'
import ExploreMoods from '../components/sections/ExploreMoods'

export default {
    name: 'Home',
    components:{
        NavBar,
        ExploreMoods,
        HeroHeader
    }
}
</script>

<style>
.explore-moods{
        background-color: #7683BF!important;

}
  h1{
        color: #344491;
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