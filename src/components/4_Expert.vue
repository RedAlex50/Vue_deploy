<template>
    <div id="block3">
        <div class="img-pc">
            <img src="@/img/laptop.png" id="@/img-pc" heigth="100px">
        </div>
        <div class="expertise">
            <div class="exp-header"><h1>Экспертиза в Drupal, опыт 14 лет!</h1></div>
            <div class="block-spec">
                <div class="flex">
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
</template>
<script>
export default {
    
}
</script>
<style scoped>
#block3{
    background: linear-gradient(254.72deg,rgba(255,255,255,.276) -114.85%,rgba(255,255,255,0) 69.04%),#040613;
    background-image: url(../img/druplicon.svg);
    background-repeat: no-repeat;
    background-position: right 270px;/* по оси x и y */
    padding-top: 300px;
    margin-top: -200px;
    background-size: 50%;

}

.spec{
    padding-left: 1rem;
    width: 250px;
    height: fit-content;/* по контенту */
    border-left: 3px solid #f14d34;
    /* margin: 2rem; */
    padding-top: 5px;
    padding-bottom: 5px;
}
.flex{
    display: flex;
    margin-top: 2rem;
    margin-bottom: 2rem;
}
#block3 {
    display: flex;
    color: white;
}

#block3 .mx-2 {
    margin-left: 2rem;
    margin-right: 2rem;
}

#block3 #img-pc {
    margin-top: 200px;
}

.img-pc {
    width: 40%;
}

#img-pc {
    margin-top: 10rem;
    width: 100%;
}

.exp-header {
    font-weight: bold;
}

.expertise {
    margin: auto;
}

</style>