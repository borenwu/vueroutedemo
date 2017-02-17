<template>
    <nav class="navbar navbar-inverse navbar-fixed-top">
        <div class="container-fluid">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a class="navbar-brand" href="#">印务通</a>
            </div>
            <div id="navbar" class="navbar-collapse collapse">
                <ul class="nav navbar-nav navbar-right">
                    <li><a href="#">设置</a></li>
                    <li><a href="#">管理员入口</a></li>
                    <li><a href="#">帮助</a></li>
                </ul>
                <!--<form class="navbar-form navbar-right">-->
                    <!--<input type="text" class="form-control" placeholder="Search...">-->
                <!--</form>-->
            </div>
        </div>
    </nav>
</template>

<style>
    .navbar-fixed-top {
        border: 0;
    }
    .navbar-inverse{
        background-color: #2196f3;
    }
    .navbar-inverse .navbar-brand {
        color: #e8eaf6;
    }
    .navbar-inverse .navbar-nav>li>a {
        color: #e8eaf6;
    }
</style>

<script>

    export default{
        data(){
            return{
                msg: 'Welcome to Your Vue.js App'
            }
        },
        components:{

        }
    }
</script>
