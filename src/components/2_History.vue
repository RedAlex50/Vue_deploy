<template>
    <div class="main">
        <div class="header">13 лет совершенствуем<br>компетенции в Друпал<br>поддержке!</div>
        <h3>Разрабатываем и оптимизируем модули,<br>расширяем<br>функциональность 
        сайтов, обновляем дизайн</h3>
        <div class="figures">
            <figure>
                <img src="@/img/competency-1.svg">
                <figcaption><h3>Добавление информации на сайт, создание новых
                    разделов</h3></figcaption>
            </figure>
            
            <figure>
                <img src="@/img/competency-2.svg">
                <figcaption><h3>Разработка и<br>оптимизация модулей<br>сайта</h3></figcaption>
            </figure>

            <figure>
                <img src="@/img/competency-3.svg">
                <figcaption><h3>Интеграция с CRM, 1C,<br>платёжными системами,
                    <br>любыми веб-сервисами</h3></figcaption>
            </figure>

            <figure>
                <img src="@/img/competency-4.svg">
                <figcaption><h3>Любые доработки<br>функционала и дизайна</h3></figcaption>
            </figure>

            <figure>
                <img src="@/img/competency-5.svg">
                <figcaption><h3>Аудит и мониторинг<br>безопасности Drupal<br>сайтов</h3></figcaption>
            </figure>

            <figure>
                <img src="@/img/competency-6.svg">
                <figcaption><h3>Миграция, импорт<br>контента и апгрейд<br>Drupal</h3></figcaption>
            </figure>

            <figure>
                <img src="@/img/competency-7.svg">
                <figcaption><h3>Оптимизация и<br>ускорение Drupal-сайтов</h3></figcaption>
            </figure>
            
            <figure>
                <img src="@/img/competency-7.svg">
                <figcaption><h3>Веб-маркетинг,<br>консультации и работа<br>по SEO</h3></figcaption>
            </figure>
        </div>   
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>


.header{
    width: 600px;
    font-size: 38px;
    font-family: Montserrat-Bold;
    font-weight: bold;
}

h3 {
    font-weight: normal;
}

.main{
    width: 1200px;
    margin: 50px auto;
}

.figures{
    display:flex;
    justify-content: flex-start;
    margin-top: 60px;
    flex-wrap: wrap; /* разрешить переход на новую строку */
}

.figures figure{
    background-image: url(../img/Vector.png);
    background-position: 10% 8%;
    background-repeat: no-repeat;
    width: 20%;
    text-align: center;
    margin: 0;
    margin-right: 5%;
    /* outline: 1px solid green; */
}

.figures figcaption{
    text-align: left;
    font-size: 18px;
    padding-left: 12px;
    width: 100%;
}

.figures figure img{
    width: 40%;
}

</style>