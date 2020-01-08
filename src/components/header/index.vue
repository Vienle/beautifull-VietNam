<template>
    <div class="container"> 
        <div class="wrap-nav">
            <div class="nav-logo">
                <a href="#">
                    <img class="logo" src="../../assets/img/logo.png" alt="logo">
                </a>
                <ul class="menu">
                    <li class="item">
                        <a href="#">Fanpage</a>
                    </li>
                    <li class="item">
                        <a href="#">Youtube</a>
                    </li>
                    <li class="item">
                        <a href="#">Instagram</a>
                    </li>
                    <li class="item">
                        <a href="#">Group Facebook</a>
                    </li>
                </ul>
            </div>
        </div>
        <div class="wrap-content">
            <h1>Khám phá <br>những địa điểm tuyệt vời <br>ở Việt Nam</h1>
            <p>
                Bạn còn trẻ, xăng còn rẻ, đôi chân còn khỏe.<br> 
                Một lần trong đời, hãy xách ba lô lên và đi, tìm kiểu cho mình những niềm vui và trải nghiệm mới,<br>
                đừng sợ mệt, đừng sợ ngày mai, đừng ngại không có tiền.
            </p>
        </div>
        <div class="search">
            <form action="" class="group" method="POST">
                <input type="text" class="form-input" placeholder="Bạn thích làm gì?">
                <input type="text" class="form-input" placeholder="Bạn muốn đi đâu?">
                <input type="Submit" class="button">
            </form>
        </div>
    </div>
</template>
<style scoped>
    .container {
        position: static;
        max-width: 80%;
        margin-left: 20%;
        
    }

    .logo{
        margin-top: 30px;
        width: 120px;
        
    }
    .menu{
        margin-left: 50px;
    }
    ul{
        list-style-type: none;
        margin-left: 5px;
        display: inline;
    }
    .item{
        display: inline;
        margin-left: 80px;
    }
    .item a{
        font-size: 20px;
        text-decoration: none;
        color: white;
    }

    .wrap-content{
        margin-top: 120px;
    }
    h1{
        font-size: 40px;
        color: white;
        line-height: 1.5;
        padding-bottom: 0px;
        margin-bottom: 0px;
    }
    p{
        margin-top: 10px;
        color: white;
    }

    .form-input{
        background: url('../../assets/img/oval.png') no-repeat;
        width: 250px;
        margin-left: 10px;
        background-position: 10px 10px;
        padding: 10px 10px  10px 40px;
        color: white;
        border: none;
        border-bottom: 1px solid blue;
    }
</style>