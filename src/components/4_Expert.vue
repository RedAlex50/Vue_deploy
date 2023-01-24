<template>
        <div id="block3">
        <div class="flex color-white">
            <div class="img-pc">
                <img src="@/img/laptop.png" id="img-pc">
            </div>
            <div class="expertise">
                <div class="exp-header"><h1>Экспертиза в Drupal, опыт 14 лет!</h1></div>
                <div class="block-spec">
                    <div class="flex my-2">
                        <div class="spec mx-2">Только системный подход - контроль версий, резервирование и тестирование</div>
                        <div class="spec mx-2">Только Drupal сайты, не берем на поддержку сайты на других CMS!</div>
                    </div>
                    <div class="flex">
                        <div class="spec mx-2">Участвуем в разработке ядра Drupal и модулей на Drupal.org, разрабатываем <span class="orange-text">свои модули Drupal</span></div>
                        <div class="spec mx-2">Поддерживаем сайты на Drupal 5, 6, 7 и 8</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>

.spec{
    padding-left: 1rem;
    width: 250px;
    height: fit-content;/* по контенту */
    border-left: 3px solid #f14d34;
    /* margin: 2rem; */
    padding-top: 5px;
    padding-bottom: 5px;
}.my-2 {
    margin-top: 2rem;
    margin-bottom: 2rem;
}
.flex{
    display: flex;
}
.expertise {
    margin: auto;
    color: white;
}

.mx-2 {
    margin-left: 2rem;
    margin-right: 2rem;
}

#block3{
    position: relative;
    z-index: -1;
}

.img-pc #img-pc{
    margin-top: 200px;
    position: relative;
    z-index: 10 !important;
}
#block3{
    background: linear-gradient(254.72deg,rgba(255,255,255,.276) -114.85%,rgba(255,255,255,0) 69.04%),#040613;
    background-image: url(../img/druplicon.svg);
    background-repeat: no-repeat;
    background-position: right 270px;/* по оси x и y */
    padding-top: 300px;
    margin-top: -200px;
    background-size: 50%;

}
@media (max-width:500px) {
    
    #block3 {
        margin: 0;
        padding: 0;
        height: fit-content;
        background-position: right calc(400px + 60vh);
        background-size: 75%;
        margin-top: -25vh;
        width: 100vw;
        padding-top: 25vh;
    }

    .flex {
        flex-direction: column;
        width: 80%;
        height: fit-content;
        margin-top: 0;
        margin-bottom: 0;
    }

    .spec {
        width: 100%;
        margin-left: 1rem;
    }

    .exp-header h1 {
        font-size: 28px;
        margin-left: 1rem;
    }

    .color-white {
        display: flex;
        flex-direction: column-reverse;
        /* img-pc и expertise поменяли местами(первые дочерние элементы) */
    }

    #img-pc {
        margin-top: 20px;
        width: 100%;
    }

    .img-pc {
        width: 95%;
        top: 20px;
    }

    #img-pc {
        margin-top: 100px !important;
        /* position: relative;
        z-index: 10 !important; */
    }

}
</style>