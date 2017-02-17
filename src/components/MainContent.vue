<template>
    <div class="container-fluid">
        <div class="row">
            <side-bar></side-bar>
            <main-page></main-page>
        </div>
    </div>
</template>

<style>

</style>

<script>
    import SideBar from './SideBar'
    import MainPage from './MainPage'

    export default{
        data(){
            return{
                msg:'hello vue'
            }
        },
        components:{
            SideBar,
            MainPage
        }
    }
</script>
