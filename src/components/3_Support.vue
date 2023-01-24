<template>
<div id="block2">
    <div class="header">
        Поддержка от Drupal-coder
    </div>
    <div class="table-4x2">
        <div class="table-row desktop-flex">
            <div class="table-item">
                <div class="item-logo">
                    <img src="@/img/support1.svg" alt="support1">
                </div>
                <div class="item-id">
                    01.
                </div>
                <div class="item-header">
                    Постановка задачи по Email
                </div>
                <div class="item-text">
                    Удобная и привычная модель постановки задач,
                    при которой задачи фиксируются и никогда не теряются.
                </div>
            </div>
            <div class="table-item">
                <div class="item-logo">
                    <img src="@/img/support2.svg" alt="support2">
                </div>
                <div class="item-id">
                    02.
                </div>
                <div class="item-header">
                    Система Helpdesk - отчетность, прозрачность
                </div>
                <div class="item-text">
                    Возможность посмотреть все заявки в работе
                    и отработанные часы в личном кабинете через браузер.
                </div>
            </div>
            <div class="table-item" id="item-3">
                <div class="item-logo">
                    <img src="@/img/support3.svg" alt="support3">
                </div>
                <div class="item-id">
                    03.
                </div>
                <div class="item-header">
                    Расширенная техническая поддержка
                </div>
                <div class="item-text">
                    Возмодность организации расширенной техподдержки
                    с 6:00 до 22:00 без выходных.
                </div>
            </div>
            <div class="table-item" id="item-4">
                <div class="item-logo">
                    <img src="@/img/support4.svg" alt="support4">
                </div>
                <div class="item-id">
                    04.
                </div>
                <div class="item-header">
                    Персональный менеджер проекта
                </div>
                <div class="item-text">
                    Ваш менеджер проекта всегда в курсе текущего состояния
                    проекта и в любой момент готов ответить на любые вопросы.
                </div>
            </div>
        </div>

        <div class="table-row desktop-flex">
            <div class="table-item" id="item-5">
                <div class="item-logo">
                    <img src="@/img/support5.svg" alt="support5">
                </div>
                <div class="item-id">
                    05.
                </div>
                <div class="item-header">
                    Удобные способы оплаты
                </div>
                <div class="item-text">
                    Безналичный расчет по договору или электронные деньги:
                    WebMoney, Яндекс.Деньги, Paypal.
                </div>
            </div>
            <div class="table-item" id="item-6">
                <div class="item-logo">
                    <img src="@/img/support6.svg" alt="support6">
                </div>
                <div class="item-id">
                    06.
                </div>
                <div class="item-header">
                    Работаем с SLA и NDA
                </div>
                <div class="item-text">
                    Работа в рамках соглашений о конфиденциальности и
                    об уровне качества работ.
                </div>
            </div>
            <div class="table-item" id="item-7">
                <div class="item-logo">
                    <img src="@/img/support7.svg" alt="support7">
                </div>
                <div class="item-id">
                    07.
                </div>
                <div class="item-header">
                    Штатные специалисты
                </div>
                <div class="item-text">
                    Надежные штатные специалисты, никаких фрилансеров.
                </div>
            </div>
            <div class="table-item" id="item-8">
                <div class="item-logo">
                    <img src="@/img/support8.svg" alt="support8">
                </div>
                <div class="item-id">
                    08.
                </div>
                <div class="item-header">
                    Удобные каналы связи
                </div>
                <div class="item-text">
                    Консультация по телефону, скайпу, в мессенджерах.
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
@media (min-width: 1200px){
.desktop-flex {
        display: flex;
    }
}

#block2{
    margin-bottom: 0;
    height: 750px;
}

.header{
    width: 400px;
    margin: 5rem auto;
    font-size: 38px;
    font-family: Montserrat-Bold;
    font-weight: bold;
    text-align: center;
}

.table-4x2{
    width: 1200px;
    margin: 0 auto;
}

.table-item{
    border-radius: 5px;
    width: 260px;
    height: 290px;
    margin: 4px;
    background-color: white;
    box-shadow: 100px 50px 100px rgba(0, 0, 0, 0.04); /* Параметры тени */
    padding: 14px;
    z-index: 0;
}


.item-logo{
    height: 0px;
    position: relative;
    left: 193px;
    top: 224px;
    z-index: -1;
}

.item-logo img{
    height: 80px;
    width: 80px;
    border-radius: 5px;
}

.item-id{
    font-size: 10px;
    font-family: Montserrat-Bold;
    color: gray;
    margin-bottom: 1rem;
}

.item-header{
    font-size: 20px;
    font-family: Montserrat-Bold;
    margin-bottom: 1rem;
}

.item-text{
    color:gray;
    font-size: 20px;
    z-index: 10;
}

@media (max-width: 1200px) {   
    #block2{
        margin-bottom: 0;
        height: 2150px;
    }
    .header{
        display: block;
        position: static;
        text-align: center;
        font-size: 28px;
        width: fit-content;
        margin:auto;
        padding: 10%;
    }

    .table-item{
        width: 95vw;
        height: 25vh;
        position: relative;
        padding: 20px 10px;
        box-sizing: border-box;
        margin-right: 5vw;
        margin-bottom: 5px;
        padding-bottom: 40px;
    }

    .item-logo{
        z-index: 10;
        position: absolute;
        top: 70%;
        left: 80%;
        transform: scale(0.7);
    }

    .item-text{
        font-size: 13px;
    }
}


</style>