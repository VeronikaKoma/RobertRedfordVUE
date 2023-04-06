
<script>
export default {

}
</script>


<template>
    <div>
        <h3>---- v-show directive ----</h3>
        <button v-on:click="changeState"></button>
        <span v-show="isShowing">Sundance...</span>
        <button>
    </div>
</template>


<style>

</style>