<template>
  <v-button 
    type="button" 
    :class="classObject"
    >
      {{cta}}
  </v-button>
</template>

<script>
export default {
    name:'button',
    props:{
       cta: {
        type:String,
        required:false
    },
    classObject:{
      type:String,
      required:false
    }
    },
  methods: {
  
  },
  data () {
    return {
        // classObject:""
    }}
}
</script>

<style>
.primary-cta{
  color:white;
  background-color:#344491;
  border-radius:11px;
  padding: 1% 3%;
  font-weight: 700;
}
.secondary-cta{
  margin-right:2%;
  color:#344491;
  border: 2px solid #344491;
  border-radius:11px;
  padding: 1% 3%;
  font-weight: 700;
}
</style>