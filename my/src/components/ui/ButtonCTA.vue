<template>
  <button
    :class="classObject"
    >
      {{cta}}
  </button>
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

<style scoped>
.primary-cta{
  color:white!important;
  background-color:#344491!important;
  border-radius:11px!important;
  padding: 1% 4%!important;
  font-weight: 700!important;
  font-size: 1.5em!important;
}
.secondary-cta{
  background-color:transparent!important;
  margin-right:2%!important;
  color:#344491!important;
  border: 2px solid #344491!important;
  border-radius:11px!important;
  padding: 1% 4%!important;
  font-weight: 700;
}
</style>