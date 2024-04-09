<script>
    export default{
        data(){
            return{
                message: 'La mia prima volta con VITE....'
            }
        }
    }
</script>

<template>
    <div>
        <h1 class="center">
            {{ message }}
        </h1>
    </div>
</template>

<style scoped>
    .center{
        text-align: center;
    }
</style>