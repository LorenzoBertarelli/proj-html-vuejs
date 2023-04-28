<script>
    export default{
        name: "AppHeader",
    }
</script>

<template>
<div class="box-header">
    <div class="container">
        <div class="navbar">
            <a class="navbar-brand" href="#">
                <img src="../assets/images/dark-logo.png" class="d-inline-block align-top" alt="">
            </a>
            <ul class="d-flex">
                <li><a href="">Home</a></li>
                <li><a href="">Blog</a></li>
                <li><a href="">Courses</a></li>
                <li><a href="">Features</a></li>
                <li><a href="">Blog</a></li>
                <li><a href="">Shop</a></li>
            </ul>
            <div class="loghi">
                <a href=""><i class="fa-brands fa-twitter"></i></a>
                <a href=""><i class="fa-brands fa-facebook-f"></i></a>
                <a href=""><i class="fa-brands fa-instagram"></i></a>
                <a href=""><i class="fa-brands fa-linkedin"></i></a>
            </div>
        </div>
    </div>
    <div class="jumbotron">
        <div>
            <h5 class="display-7">I'M WINGMAN</h5>
            <p class="lead">Peace On Earth A <br> Wonderful Wish <br> But No Way</p>
            <p>Succes isn't overnight. It's when everyday you get a little <br> better than the day before. It all adds up.</p>
            <a class="btn btn-primary btn-lg" href="#" role="button">Get Started For Free <i class="fa-solid fa-arrow-right-long"></i></a>            
        </div>
        <div>
            <img src="../assets/images/home-movation-hero-image.png" alt="">
        </div>
    </div>
</div>

</template>

<style lang="scss" scoped>
    .box-header {
        background-image: url(../assets/images/background-pattern-wavify.png);   
        background-color: rgb(235, 235, 235);     
    }
    .container {
        display: flex;
        justify-content: space-between;
        max-width: 100%;
        .navbar{
            width: 100%;
            max-width: 1100px;
            margin: 0 auto;
            justify-content: space-between;
            align-items: center;
            vertical-align: middle;
        }
        img {
            height: 30px;
            width: 200px;
        }
    }
    
    ul {
        list-style-type: none;
        margin-bottom: 0px;
        li {
            padding: 5px;
            a {
                color: rgb(99, 1, 99);
            }
        }
    }
    
    a {
        text-decoration: none;
        color: black;
        padding: 10px;
    }
    
    .loghi {
        margin-left: 50px;
    }

    .jumbotron {
        display: flex;
        margin: 0 auto;
        justify-content: space-between;
        align-items: center;
        vertical-align: middle;
        max-width: 1100px;

        .lead {
            font-size: 3rem;
        }
        
        img {
            margin-top: 50px;
            background-image: url(../assets/images/home-movation-shape-face-600x534.png);
            background-image: 500px;
        }

        .btn {
            color: white;
            background-color: #20ac97;
            border: none;
            font-size: 0.8rem;
            padding: 15px 50px;
        }
    }

</style>