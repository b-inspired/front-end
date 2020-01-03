<template>
    <nav class="navbar navbar-expand-lg">
        <div class="logo">
            <logo/>
        </div>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
         <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse nav-cta" id="navbarSupportedContent">
            <buttoncta
            cta="Explorar ideas"
            :classObject="secondary"
            />
            <buttoncta
            cta="Subir ideas"
            :classObject="primary"
            />
        </div>
    </nav>
</template>

<script>
import logo from '../ui/Logo'
import Buttoncta from '../ui/ButtonCTA'

export default {
    name: 'NavBar',
    components: {
        logo,
        Buttoncta
    },
    data(){
        return{
            primary:'btn btn-lg primary-cta',
            secondary:'btn btn-lg secondary-cta',
        }
    }
}
</script>

<style scoped>
nav{
    display:flex;
    justify-content: space-between;
}
.nav-cta{
    display:flex;
    justify-content: flex-end;
}
</style>