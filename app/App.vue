<style scoped>
    .container{
        background-color: white;
    }
</style>

<template>
    <div class="container">
        <div class="row">
            <hello></hello>
        </div>
    </div>
</template>

<script>
    import Hello from './components/Hello.vue';

    export default {
        components: {
            hello: Hello,
        },

        data() {
            return {
            }
        },
        beforeCreate(){
        console.log('hi')
        }
    }
</script>
