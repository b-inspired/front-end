<template>
  <div class="container-fluid">
      <div class="row titles">
        <h2>¿Cuál es tu mood?</h2>
        <h3>Descubre la inspiración perfecta</h3>
      </div>

    <div class="explore-moods-row">
      <div class="row">
          <div class="col-3">
            <i class="fas fa-smile-beam"></i>
            <h5>Feliz</h5>
          </div>
          <div class="col-3">
              <i class="fas fa-laugh-squint"></i>
              <h5>Risueño</h5>
          </div>
          <div class="col-3">
              <i class="fas fa-sad-cry"></i>
              <h5>Triste</h5>
          </div>
      </div>
      <div class="row">
          <div class="col-3">
              <i class="fas fa-crown"></i>
              <h5>Afortunado</h5>
          </div>
          <div class="col-3">
              <i class="fas fa-heart-broken"></i>
              <h5>Corazón roto</h5>
          </div>
          <div class="col-3">
              <i class="fas fa-dizzy"></i>
              <h5>Equis</h5>
          </div>
      </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.row{
    justify-content: space-around;  
}
.explore-moods-row .row{
    padding-bottom: 5%;
    /* align-items: center; */
}
.explore-moods-row {
    max-width: 80%;
    /* align-items: center; */
}
.titles{
    display: block;
    text-align: center;    
    padding-top:3%;
    margin-bottom:3%;
}
h2{
    font-family: Bw Modelica;
    font-style: normal;
    font-weight: 800;
    font-size: 53px;
    line-height: 136.5%;
    color: white;
}
h3{
    font-family: Bw Modelica;
    font-style: normal;
    font-weight: bold;
    font-size: 44px;
    line-height: 130.5%;
    color: #EFC55F;
}
.container-fluid{
    background-color: #7683BF!important;
}
.col-3{
    width: 100%;
    height: 143px;
    box-shadow: 10px 4px 20px rgba(0, 0, 0, 0.1);
    background: #FFFFFF;
    border-radius: 11px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    color:#344491;
}
.col-3 i{
    font-size: 3.5em;
}
.col-3 h5{
    text-align: center;
    font-size: 2em;
    font-style: normal;
    font-weight: 600;
    line-height: 130.2%;
}
</style>