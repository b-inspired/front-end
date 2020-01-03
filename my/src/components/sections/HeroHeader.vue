<template>
  <div class="container-fluid">
      <div class="row">
          <div class="col content">
              <div class="title">
                <h1>Encuentra la <strong>inspiración perfecta</strong></h1>  
              </div>
            <div class="search-box">
                <select class="form-control form-control-lg">
                    Tu Mood
                 <option>Large select</option>
                </select>
                <select class="form-control form-control-lg">
                 <option>Large select</option>
                </select>
               <button>asdaasd</button> 
            </div>         
          </div>

          <div class="col-5">
              <img src="@/assets/Ilustrations-header.png" alt="" class="img-fluid">
          </div>
      </div>
      <div class="row">
        <img class="divider img-fluid" src="@/assets/divider-hero-header.png" alt="">
      </div>
  </div>
</template>

<script>
export default {
    data () {
      return {
        components: [
          'Autocompletes', 'Comboboxes', 'Forms', 'Inputs', 'Overflow Buttons', 'Selects', 'Selection Controls', 'Sliders', 'Textareas', 'Text Fields',
        ],
      }
    },
}
</script>

<style scoped>
.content{
  align-self: center;
}
.search-input{
    background-color: white;
}
.search-box{
    width:100%;
    display:flex;
    justify-content: flex-start;
}
    h1{
        color: #344491!important;
        font-family: Bw Modelica;
        font-style: normal;
        font-weight: 800;
        font-size: 3.5em;
        line-height: 144.5%;
    }
.col-7{
    margin-left:3%;
    flex-direction: column;
}
img{
  width:100%;
}
.divider{
  margin-top:-1%;
}
.hero{
  margin-top: 2%;
}.title{
      margin-top: -10%;
}
</style>