<template>
  <div class="container-fluid">
      <div class="row">
          <div class="col-7">
              <div class="title">
                <h1>Encuentra la inspiración perfecta</h1>  
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

          <div class="col-4">
              <img src="../assets/Ilustrations-header.png" alt="" class="img-fluid">
          </div>
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
        font-size: 61px;
        line-height: 144.5%;
    }
.col-7{
    margin-left:3%;
    flex-direction: column;
}
</style>