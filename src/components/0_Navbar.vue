<template>
    <header class="navbar mx-auto">
        <div class="container mx-auto">
            <div class="nav-1 flex">
                <div class="nav-logo">
                    <a href=""><img src="@/img/drupal-coder.svg" alt="Drupal Coder"></a>
                </div>
                <a href="javascript:void(0);" class="icon" onclick="myFunction()">
                    <i class="fa fa-bars"></i>
                </a>
            </div>
            <div class="nav-btns color-white fs-12 closed" id="nav-btns">
                <ul class="nav-list">
                    <li class="mx-2"><a class="btn color-white" href="">ПОДДЕРЖКА DRUPAL</a></li>
                    <li class="mx-2">
                        <div class="menu">
                            <a class="btn color-white" href="">АДМИНИСТРИРОВАНИЕ &#9660;</a>
                            <div class="menu-links color-white">
                                <a href="#">МИГРАЦИЯ</a>
                                <a href="#">БЭКАПЫ</a>
                                <a href="#">АУДИТ БЕЗОПАСНОСТИ</a>
                                <a href="#">ОПТИМИЗАЦИЯ СКОРОСТИ</a>
                                <a href="#">ПЕРЕЕЗД НА HTTPS</a>
                                </div>
                        </div>
                    </li>
                    <li class="mx-2"><a class="btn color-white" href="">ПРОДВИЖЕНИЕ</a></li>
                    <li class="mx-2"><a class="btn color-white" href="">РЕКЛАМА</a></li>
                    <li class="mx-2">
                        <div class="menu">
                            <a class="btn color-white" href="">О НАС &#9660;</a>
                            <div class="menu-links color-white">
                                <a href="#">КОМАНДА</a>
                                <a href="#">DRUPALGIVE</a>
                                <a href="#">БЛОГ</a>
                                <a href="#">КУРСЫ DRUPAL</a>
                                
                            </div>
                        </div>
                    </li>
                    <li class="mx-2"><a class="btn color-white" href="">ПРОЕКТЫ</a></li>
                    <li class="mx-2"><a class="btn color-white" href="">КОНТАКТЫ</a></li>
                </ul>
            </div>
        </div>
        
    </header>
</template>
<script>
export default {
}

</script>
<style scoped>

@media (min-width: 1200px) {
    .container{
        width: 1400px;
    }
}
.color-white {
    color: white;
}
ul{
    list-style: none;
}
.navbar {
    background-color: rgb(0, 0, 0);
    width: 100%;
    position: fixed;
    bottom: 0;
    padding-bottom:0;
    padding-top:10px;
    z-index: 1000;
  }

.nav-list{
margin-left:-60px;
display: flex;
}
.fa-bars{
font-size:200%;
margin-right:10px;
margin-bottom:20px;
}
a{
border-bottom:solid 1px rgb(69, 68, 68);

}
.btn{
padding:10px;
}
a {
color: white;
text-decoration: none;
display: block;
}

a.icon {
background: black;
display: block;
position: absolute;
right: 0;
}
.nav-1{
margin-top: auto;
order:2;
}
.closed{
display:none;
overflow: hidden;
transition: max-height 0.3s ease-out;
    }
img{
    height: 2rem;
}
.nav-btns{
    order:1;
}
a:hover {
    color:#f14d34;
}
.menu-links {
    min-width: 160px;
    position:relative;
    cursor: pointer;
  }
a {
    padding: 10px 16px;
    text-decoration: none;
    display: block;
    color:white;
}

.menu-links:hover {
     max-height: 300px;
  transition: max-height 0.3s ease-in;
}


@media (min-width: 768px) {
    a:hover {
        color:white;
    }
    a.icon{
        display:none;
    }
    .navbar{
        background:transparent;
        position:absolute;
        top:0;
    }
    .nav-btns{
        display:block;
    }
    .btn{
        border:0;
        padding:0;
        padding-bottom:10px;
    }
     .menu-links{
        background-color: #f14d34;
        position:absolute;
        max-height: 0;
        overflow: hidden;
        transition: max-height 0.3s ease-in;
    }
    a{
        border:0;
    }
    a:hover {
        background-color: rgb(192, 67, 13);
    }
}


.mx-auto {
    margin-left: auto;
    margin-right: auto;
}
.flex {
    display: flex;
}
.fs-12 {
    font-size: 12px;
}
.mx-2 {
    margin-left: 2rem;
    margin-right: 2rem;
}
</style>