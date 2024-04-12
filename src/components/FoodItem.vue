<template>
   

    <div>
        <h2>{{ name }}</h2>
        
        <p  v-on:click="countClicks" id="red">You have clicked me {{ clicks }} times.</p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            name: 'Apples',
            clicks: 0
           
        }
    },
    methods: {
        countClicks() {
            this.clicks++;
        }
    }
};
</script>

<style></style>                  