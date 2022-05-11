<template>
    <div class="conversor">
        <h2> {{moedaA}} --> {{moedaB}} </h2>


    </div>
</template>


<script>
import { propsToAttrMap } from "@vue/shared";

export default{
    name: "conversor" 
    props: ['foo']
}

</script>


<style scoped>

</style>