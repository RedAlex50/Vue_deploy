<template>
    <div id="video-block">
        <div id="video-filter"></div>
        <video class="video-background"
            src="https://res.cloudinary.com/dpyzh619e/video/upload/v1606770179/video_bjr0b7.mp4" playsinline=""
            autoplay="autoplay" loop="" preload="auto" muted="">
        </video>
        </div>
        <div class="main">
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
                        <h1>#1 <span><img src="@/img/cup.png" alt=""></span></h1>
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
</template>
<script>
export default {
    
}
</script>
<style scoped>


@media (max-width: 1200px){
    #block0 {
        background-color: #111111;
        height: 1000px;
    }
    .spec{
        margin: 1rem auto;
    }
    .main-specs{
        display: grid;
        grid-template-columns: 1fr 1fr;
    }
}

@media(min-width: 1201px){
    .main-specs{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
    }
}
.main{
    width: 1200px;
    margin: 30px auto;
    color: white;
    position: relative;
    display: flex;
}
.drupal-main {
    margin: 2rem auto;
    width: 400px;
}

.drupal-main h1{
    font-family: Montserrat-Bold;
    font-size: 48px;
}

.main-btn{
    margin: 2rem 0;
    width: fit-content;
}

.main-btn button{
    width: 15rem;
    height: 3rem;
    border: 2px solid #f14d34;
    background-color: transparent;
    border-radius: 4px;
    color: #ffffff;
}

.main-btn button:hover{
    background-color: #f14d34;
    color: white;
    transition: 100ms;
}

.main-specs{
    margin: 0 auto;
    padding: 3rem;
}

.main-spec{
    padding-left: 1rem;
    width: 200px;
    height: 100px;
    border-left: 3px solid #f14d34;
    margin: 10px;
}

.main-spec img{
    position: relative;
    top: -6px;
}

.main-spec p{
    font-size: 11px;
    opacity: 0.8;
    margin: 0;
}

#video-block {
  z-index: -10;
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 550px;
  overflow: hidden;
}

#video-filter {
  z-index: 1;
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.7);
}

#video-block video {
  min-height: 100%;
  min-width: 100%;
  filter: blur(2px);
}

</style>