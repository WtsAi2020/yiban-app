<template>
    <div class="menuBox">
       <div class="boxOne">
           <router-link to="#"><span>主页</span></router-link>
           <a href="#"></a>
           <router-link to="#"><span>推荐</span></router-link>
       </div>
    </div>
</template>

<script>
    export default {
        name: "Menu"
    }
</script>

<style scoped="scss">
    .menuBox{
        position: fixed;
        top: 7.1rem;
        left: 0;
        width: 100%;
        margin-top: 5px;
        text-align: center;
        border-bottom: 0.1px solid #E4E7ED;
        height: 3.5rem;
        z-index: 1;
    }
    .boxOne{
        display: block;
        font-size: 1.6rem;
        text-align: center;
        line-height: 3.5rem;
        font-family: 方正姚体;
    }
    .boxOne a{
        margin: 0 4rem 0 4rem;
    }

</style>