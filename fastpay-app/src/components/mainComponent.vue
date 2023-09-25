<template>
    <div>
        <h2>i'm main component</h2>
        <main-input-vue v-for="item in inputsArr" 
        :key=item.id 
        :title="item.title" 
        :type="item.type"
        :plaseholder="item.placeholder"></main-input-vue>
    </div>
</template>

<script lang="ts">
import mainInputVue from '../serviceComponents/mainInput.vue'

    export default {
        type:Array,

        components: {
            mainInputVue
        },
        data(){
            return {
                inputsArr: [
                { id: 1, title: 'input1', type: 'text', placeholder: 'input1' },
                { id: 2, title: 'input2', type: 'text', placeholder: 'input2' },
                { id: 3, title: 'input3', type: 'text', placeholder: 'input3' },
              ]
            }
            
        }
    }       

</script>