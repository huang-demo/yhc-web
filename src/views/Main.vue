<template>
    <div class="main">
    <div class="left">
        <Left></Left>
    </div>
    <div>
        <div class="top">
            <img src="img/banner.jpg">
        </div>
        <div class="buttom"></div>
    </div>
    </div>
</template>
<style type="text/css">
    *{
       padding:0;
       margin:0;  
    }
    .left{
        widows: 100px;
        float:left;
        margin-right: 10px;

    }
    .right{
        width: 1000px;
        float:left;
        margin-right: 10px;

    }
    .main{
        width: 1200px;
        margin:20px auto;

    }
    .top img{
        height: 200px;
        width:1000px;

    }
    .left,.right{
        background-color: blue;
        height: 500px;
    }

</style>
<script>
    import Left from '@/components/Left.vue';
    export default{
        components:{
            Left
        }
    }
</script>