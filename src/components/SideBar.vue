<template>
    <mu-paper class="col-sm-3 col-md-2 sidebar" :zDepth="4">
        <ul class="nav nav-sidebar">
          <li><router-link to="/home">主页</router-link></li>
          <li><router-link to="/order">订单</router-link></li>
          <li><router-link to="/work">生产</router-link></li>
          <li><router-link to="/warehouse">仓库</router-link></li>
          <li><router-link to="/finance">财务</router-link></li>
        </ul>
    </mu-paper>
</template>

<style>
    .sidebar {
        display: none;
    }
    @media (min-width: 768px) {
        .sidebar {
            position: fixed;
            top: 51px;
            bottom: 0;
            left: 0;
            z-index: 1000;
            display: block;
            padding: 20px;
            overflow-x: hidden;
            overflow-y: auto; /* Scrollable contents if viewport is shorter than content. */
            background-color: #f5f5f5;
            border-right: 1px solid #eee;
        }
    }
    .nav-sidebar {
        margin-right: -21px; /* 20px padding + 1px border */
        margin-bottom: 20px;
        margin-left: -20px;
    }
    .nav-sidebar > li > a {
        padding-right: 20px;
        padding-left: 20px;
    }
    .nav-sidebar > .active > a,
    .nav-sidebar > .active > a:hover,
    .nav-sidebar > .active > a:focus {
        color: #fff;
        background-color: #428bca;
    }
</style>


<script>

    export default{
        name: 'side-bar',
        data(){
            return{
                msg:'hello side bar'
            }
        },
        components:{

        }
    }
</script>
