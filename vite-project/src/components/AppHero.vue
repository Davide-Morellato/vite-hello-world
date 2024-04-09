<script>
    export default{
        data(){
            return{
                messageEnd: '.....al limite!'
            }
        }
    }
</script>

<template>
    <div>
        <img src="https://cdn.blogo.it/XUe6DS0DZX_LMqHhUTPcqyu3h6g=/1280x720/smart/https://www.blogo.it/app/uploads/sites/2/2020/03/joe-my-600-lb-life-2.jpg" alt="">
        <h1 class="center">
            {{ messageEnd }}
        </h1>
    </div>
</template>

<style scoped>
    .center{
        text-align: center;
    }
    
    img{
        width: 50%;
    }
</style>