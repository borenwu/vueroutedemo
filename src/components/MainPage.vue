<template>
  <div class="col-sm-9 col-sm-offset-3 col-md-10 col-md-offset-2 main">
    <router-view></router-view>
  </div>
</template>

<style>
  .main {
    padding: 20px;
  }
  @media (min-width: 768px) {
    .main {
      padding-right: 40px;
      padding-left: 40px;
    }
  }
</style>

<script>

    export default{
        data(){
            return{
                msg:'hello main apge'
            }
        },
        components:{

        }
    }
</script>
