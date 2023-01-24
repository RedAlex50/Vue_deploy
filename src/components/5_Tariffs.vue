<template>
    <div id="block4">
        <img src="@/img/back-d.svg" alt="">
        <div class="header">
            Тарифы
        </div>
        <div class="tarif-list desktop-flex">
            <div class="tarif" id="tarif-start">
                <p class="tarif-header">
                    Стартовый
                </p>
                <hr>
                <ul class="tarif-specs">
                    <li>Консультации и работы по SEO</li>
                    <li>Услуги дизайнера</li>
                    <li>Неиспользованные оплаченные часы переносятся на следующий месяц</li>
                    <li>Предоплата от 6 000 рублей в месяц</li>
                </ul>
                <div class="tarif-btn">
                    <button>
                        СВЯЖИТЕСЬ С НАМИ!
                    </button>
                </div>
            </div>
            <div class="tarif" id="tarif-business">
                <p class="tarif-header">
                    Бизнес
                </p>
                <hr>
                <ul class="tarif-specs">
                    <li>Консультации и работы по SEO</li>
                    <li>Услуги дизайнера</li>
                    <li>Высокое время реакции - до 2 рабочих дней</li>
                    <li>Неиспользованные часы не переносятся</li>
                    <li>Предоплата от 30 000 рублей в месяц</li>
                </ul>
                <div class="tarif-btn">
                    <button>
                        СВЯЖИТЕСЬ С НАМИ!
                    </button>
                </div>
            </div>
            <div class="tarif" id="tarif-vip">
                <p class="tarif-header">
                    VIP
                </p>
                <hr>
                <ul class="tarif-specs">
                    <li>Консультации и работы по SEO</li>
                    <li>Услуги дизайнера</li>
                    <li>Максимальное время реакции - в день обращения</li>
                    <li>Неиспользованные часы не переносятся</li>
                    <li>Предоплата от 270 000 рублей в месяц</li>
                </ul>
                <div class="tarif-btn">
                    <button>
                        СВЯЖИТЕСЬ С НАМИ!
                    </button>
                </div>
            </div>
        </div>
        <div class="tarif-other">
            <p>Вам не подходят наши тарифы? Оставьте заявку и 
                мы предложим вам индивидуальные условия!
            </p>
            <a href="">
                ПОЛУЧИТЬ ИНДИВИДУАЛЬНЫЙ ТАРИФ
            </a>
        </div>
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
.header{
    width: 400px;
    margin: 5rem auto;
    font-size: 38px;
    font-family: Montserrat-Bold;
    font-weight: bold;
    text-align: center;
}

#block4{
    margin-bottom: 10rem;
    position: relative;
}

#block4 img{
    position: absolute;
    top: -80px;
    right: 0;
    z-index: -10;
}


.tarif-list{
    width: 1200px;
    margin: 0 auto;
}

.tarif{
    margin: auto 10px;
    border: 1px solid rgb(204, 204, 204);
    border-radius: 4px;
    padding: 2rem 2rem;
    width: 330px;
    background-color: white;

    transition: all 0.5s ease;
}

#tarif-start{
    height: fit-content;
}

#tarif-business{
    height: 500px;
    padding-top: 20px;
}

#tarif-vip{
    height: fit-content;
}

.tarif-header{
    font-size: 22px;
    color: #f14d34;
    font-family: Montserrat-Bold;
    margin: 2rem 0;
}


.tarif hr{
    height: 2px;
    background-color: rgb(204, 204, 204);
    border: none;
}


.tarif-specs{
    list-style-image: url(../img/Vector.svg);
}

.tarif-specs li{
    margin: 1rem 0;
}


.tarif-btn{
    margin: 2rem auto;
    width: fit-content;
}

.tarif-btn button{
    width: 15rem;
    height: 3rem;
    border: 1px solid #f14d34;
    border-radius: 4px;
    color: #f14d34;
    background-color: white;
}

.tarif-other{
    margin: 0 auto;
    text-align: center;
    width: 500px;
    margin-top: 3rem;
}

.tarif-other p{
    color:#4f5a73;
    margin-bottom: 1rem;
}

.tarif-other a{
    color:black;
    text-decoration: underline;
}

.tarif:hover {
    z-index: 1000;
    scale: 1.1;
    box-shadow: 0px 0px 200px #8b8b8b5e;
}

.tarif:hover button{
    transition: 500ms   ;
    color: #ffffff;
    background-color: #f14d34;
}
</style>