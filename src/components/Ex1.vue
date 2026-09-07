<script setup>
    import { ref } from 'vue'

    // Add code here
    // challenge: use array  
    const message = ref("Choose your favourites: ");
    const fruits = ref(["apple", "orange", "peach"]);
    const fruits1 = ref("apple");
    const fruits2 = ref("orange");
    const fruits3 = ref("peach");


</script>

<template>
    {{ message }} 
   
    <label for=""> </label> <input type="radio" name="fruit"> {{fruits1}}
    <label for=""> </label> <input type="radio" name="fruit"> {{fruits2}}
    <label for=""> <input type="radio" name="fruit"> {{ fruits3 }} </label>
    <!-- the name doesnt matter unless youre retrieving the data -->
    <!-- the label is for moral support??? -->
    
    <!-- <label v-for="fruit in fruits" :key="fruit">
        <input type="radio" name="fruit">{{ fruit }}
    </label> -->

</template>

<style scoped>
</style>
