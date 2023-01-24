<template>
<div id="block0">
        <div class="main">
            <div class="desktop-flex">
                <div class="drupal-main">
                    <h1>Поддержка сайтов на Drupal</h1>
                    <p>Сопровождение и поддержка сайтов
                        на CMS Drupal любых версий и запущенности
                    </p>
                    <div class="main-btn">
                        <button>
                            ТАРИФЫ
                        </button>
                    </div>
                </div>
                <div class="main-specs">
                        <div class="main-spec">
                            <h1 id="h1">#1 <span><img src="@/img/cup.png" alt=""></span></h1>
                            <p>Drupal-разработчик в России по версии Рейтинга Рунета</p>
                        </div>
                        <div class="main-spec">
                            <h2>3+</h2>
                            <p>средний опыт специалистов более 3 лет</p>
                        </div>
                        <div class="main-spec">
                            <h2>14</h2>
                            <p>лет опыта в сфере Drupal</p>
                        </div>
                        <div class="main-spec">
                            <h2>50+</h2>
                            <p>модулей и тем в формате DrupalGive</p>
                        </div>
                        <div class="main-spec">
                            <h2>90 000+</h2>
                            <p>часов поддержки сайтов на Drupal</p>
                        </div>
                        <div class="main-spec">
                            <h2>300+</h2>
                            <p>Проектов на поддержке</p>
                        </div>
                </div>
            </div>
        </div>
        <video loop muted autoplay id="video">
            <source src="@\img\header_video.mp4" type="video/mp4">
        </video>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
@media (min-width: 1200px){
.desktop-flex {
        display: flex;
    }
}
#block0{
    color: white;
    position: relative;
    overflow: hidden;
    z-index: -100;
}

#h1{
    margin: 0;
}

.main{
    position: absolute;
    top:20%;
    left:15%;
    height: 100%;
    z-index: 1200;
}

@media (max-width: 1200px){
    #block0 {
        background-color: #111111;
        height: 800px;
    }
    .spec{
        margin: 1rem auto;
    }
    .main-specs{
        display: grid;
        grid-template-columns: 1fr 1fr;
    }
    #video {
        display: none;
}
}

@media(min-width: 1201px){
    .main{
        
    width: 1200px;
    }
    .main-specs{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
    }
}
    
#video {
    filter: brightness(30%);
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
}


.drupal-main {
    margin: 2rem auto;
    font-size:75%;
}

h1{
    font-family: Montserrat-Bold;
    font-size: 44px;
}

.main-btn{
    margin: 2rem 0;
    width: fit-content;
    margin-left:auto;
    margin-right:auto;
}

.main-btn button{
    width: 15rem;
    height: 3rem;
    border: 2px solid #f14d34;
    background-color: transparent;
    border-radius: 4px;
    color: #ffffff;
    z-index: 2000;
}

.main-btn button:hover{
    background-color: #f14d34;
    color: white;
    transition: 100ms;
}

.main-specs{
    margin: 0 auto;
}

.main-spec{
    padding-left: 1rem;
    width: 200px;
    height: 100px;
    border-left: 3px solid #f14d34;
    margin: 10px;
}

h2{
    font-family: Montserrat-Bold;
    margin: 0;
}

img{
    position: relative;
    top: -6px;
}

p{
    font-size: 11px;
    opacity: 0.8;
    margin: 0;
}

@media (min-width: 1200px) {
    #block0{
        padding-top:45%;
    }
    .main{
        width: 1300px;
    }
    .main-btn{
        margin-left:0;
        margin-right:0;
    }
    .drupal-main {
        width: 400px;
    }
}
@media (min-width: 500px) {
    .drupal-main{
        width: 500px;
        margin: 0;
    }
}

</style>