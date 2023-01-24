<template>
    <div id="block5">
        <div class="text-bold">Наши профессиональные разработчики выполняют быстро любые задачи</div>
        <div class="flex">
            <div class="spec_alt mx-auto">
                <div><img src="@/img/competency-20.svg" alt=""></div>
                <div class="spec-upper">от 1ч</div>
                <div class="spec-bot">Настройка события GA в интернет-магазине</div>
            </div>
            <div class="spec_alt mx-auto">
                <div><img src="@/img/competency-21.svg" alt=""></div>
                <div class="spec-upper">от 20ч</div>
                <div class="spec-bot">Разработка мобильной версии сайта</div>
            </div>
            <div class="spec_alt mx-auto">
                <div><img src="@/img/competency-22.svg" alt=""></div>
                <div class="spec-upper">от 8ч</div>
                <div class="spec-bot">Интеграция модуля оплаты</div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
@media (min-width: 1200px) {
    #block5{
        
    width: 1200px;
    }
    
}

.text-bold{
    font-family: Montserrat-Bold;
    font-size:30px;
}

#block5{
    padding: 75px;
    margin-left: auto;
    margin-right: auto;
}

.flex{
    justify-content: space-between;
    margin-top: 30px;
    margin-left: -50px;
   
}

.mx-auto{
    margin-left: 0;/* переопределение стилей Саши! */
    margin-right: 0;/* переопределение стилей Саши! */
}

.spec_alt{
    /* outline: 1px red solid; */
    width: 20%; /* от ширины родителя */
    background-image: url(../img/Vector.png);
    background-position: 0 12%;
    background-repeat: no-repeat;
    padding-left: 50px;
}

.spec_alt img{
    width: 40%;
}

.spec-upper{
    font-family: Montserrat-Bold;/* переопределение стилей Саши! */
}

.spec-bot{
    font-size: 18px;
}
.flex{
    display: flex;
}

@media (max-width:500px) {
    .text-bold {
        font-size: 28px;
    }

    #block5 {
        padding: 15px;
        margin-top: -100px;
    }
    .flex {
        /* justify-content: space-between;
        margin-top: 30px;
        margin-left: -50px; */
        flex-direction: column;

    }

    .mx-auto {
        margin-left: 0;
        /* переопределение стилей Саши! */
        margin-right: 0;
        /* переопределение стилей Саши! */
    }

    .spec_alt {
        /* outline: 1px red solid; */
        width: 35%;
        /* от ширины родителя */
        background-image: url(../img/Vector.png);
        background-position: 0 12%;
        background-repeat: no-repeat;
        /* padding-left: 10px; */
        background-size: 45%;
        /* margin-left: 2rem; */
        margin-left: 37%;
        margin-top: 20px;
        box-sizing: border-box;

    }

    .spec_alt img {
        width: 40%;
        margin: auto;
    }

    .spec-bot {
        font-size: 13px;
        margin: 0;
        padding: 0;
        margin-left: -50px;
    }


}
</style>