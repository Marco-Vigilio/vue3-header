<template>
    <div>
        <h1>Sono l'head</h1>
        <NavLink v-for="element in array" />
        :oggetto = element
    </div>
</template>
<script>
import NavLink from './NavLink.vue';
export default {
    name: "HeadApp",
    components: {
        NavLink
    },
    data() {
        return {
            array: [
                {
                    name: "Gino",
                    age: 22,
                }
            ]
        }
    },
}


</script>
<style lang="">
    
</style>