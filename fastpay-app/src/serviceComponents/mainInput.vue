<template>
    <div>
       
        <label for="">{{ title }}</label>
        <input type="text" placeholder="input">
    </div>
   
</template>

<script lang="ts">
    export default {
        props:['id', 'title', 'type', 'placeholder'],
        data(){
            return {
            
            }
            
        }
    }
</script>

<style scoped>
input {
    color: black
}
</style>