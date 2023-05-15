<template>
    <div class="container my-2">
        <div class="row my-1">
            <headercomponent/>
        </div>
        <div class="row my-1">
            <div class="col-4">
                <linkscomponent/>
            </div>
            <div class="col-8">
                <bodycomponent/>
            </div>
        </div>
        <div class="row my-1">
            <footercomponent/>
        </div>
    </div>
</template>

<script>
import headercomponent from './components/headercomponent.vue'
import footercomponent from  './components/footercomponent.vue'
import linkscomponent from './components/linkscomponent.vue'
import bodycomponent from './components/bodycomponent.vue'

export default {
    components:{
        linkscomponent,
        headercomponent,
        bodycomponent,
        footercomponent
    }

}
</script>

<style>

</style>