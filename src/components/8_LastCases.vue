<template>
    <div class="block7">
        <div class="last_cases">Последние кейсы</div>
        <div class="galary1">
            <figure>
                <a href="#"><img src="@/img/image_6_2.png">
                    <figcaption><h3>Настройка кэширования данных. Апгрейд сервера. 
                        Ускорение работы сайта в 30 раз!</h3>
                        <h6>04.05.2020</h6>
                        <h4>Влияние скорости загрузки страниц сайта на отказы и конверсии. Кейс ускорения...</h4>
                    </figcaption></a>
            </figure>
            <figure>
                <a href="#"><img src="@/img/image_11_1.png">
                    <figcaption>
                        <h4 class="using">Использование отчётов Ecommerce в Яндекс.Метрике</h4>
                    </figcaption></a> 
            </figure>
        </div>
        <div class="galary2">
            <figure>
                <a href="#"><img src="@/img/image_7_3.png">
                    <figcaption><h3>Повышение конверсий страницы с формой заявки с применением АВ-тестирования</h3>
                        <h6>24.10.2020</h6>
                    </figcaption></a>
            </figure>
            <figure>
                <a href="#"><img src="@/img/image_8_3.png">
                    <figcaption><h3>Drupal 7: ускорение времени генерации страниц интернет-магазина на 32%</h3>
                        <h6>23.09.2019</h6>
                    </figcaption></a>
            </figure>
            <figure>
                <a href="#"><img src="@/img/image_9_2.png">
                    <figcaption><h3 class="change">Обмен товарами и заказами интернет-магазинов на Drupal 7 с 1C: Предприятие, МойСклад, Класс365</h3>
                        <h6>22.08.2019</h6>
                        <h4><span>Опубликован </span><a href="#" class="relise">релиз модуля...</a></h4>
                    </figcaption></a>
            </figure>

        </div>
    </div>
  </template>
  
  <script>
  export default {
  }
  </script>
  
  <style scoped>

.block7 .last_cases{
    font-size: 32px;
    font-family: Montserrat-Bold;
    text-align: center;
}

.block7 h3{
    font-family: Montserrat-Bold;
    font-size: 18px;
    margin-bottom: 10px;
}

.block7 h6{
    color: #050C33;
    font-weight: 100;
    margin-top: 0;
}

.block7 h4{
    color: #4E5A73;
    text-decoration: none;
}

.block7 .galary1{
    display: flex;
    justify-content: center;
    margin-top: 30px;
}

.block7 .galary1 h3{
    margin-top: 0;
    color: black;

}

.block7 .galary1 figure:first-child{/* псевдокласс на первый flex */
    width: 30%;/* ширина первой figure */
    margin: 0;
    /* outline: #040613 1px solid; */
}

.block7 .galary1 h4{
    margin-bottom: 0;
}
.block7 .galary1 figure:first-child img{
    width: 100%;
    object-fit: cover; /* масштабируется картинка в блоке под изменяемый размер */
}
/* cover - по ширине */
/* сcontain - по высоте */

.block7 .galary1 figure:first-child figcaption{
    padding: 10%;
}

.block7 .galary1 figure:last-child{/* псевдокласс на второй flex */
    width: 60%;/* ширина второй figure */
    margin: 0;
    margin-left: 2%;
}

.block7 .galary1 figure:last-child img{
    width: 100%;
    object-fit: cover; /* масштабируется картинка в блоке под изменяемый размер */
}

.block7 .galary1 figure:last-child figcaption h4{
    margin-top: -85px;
    color: white !important;
    margin-left: 5%;
    width: 50%;
    margin-bottom: 0;
}

.block7{
    width: 98vw;
    /* outline: #f14d34 1px solid; */
}

.block7 .galary2{
    display: flex;
    justify-content: center;
    margin-top: 0;
}

.block7 .galary2 figure{
    margin: 0;
    margin-right: 2%;
    width: 29.5%;
}

.block7 .galary2 img{
    width: 100%;
    object-fit: cover;
}

.block7 .galary2 figure:last-child{
    margin-right: 0;
}

.block7 .galary2 figure:first-child figcaption{
    margin-top: -170px;
    color: white;
    margin-left: 10%;
    margin-right: 10%;
}

.block7 .galary2 figure:nth-child(2) figcaption{
    margin-top: -170px;
    color: white;
    margin-left: 10%;
    margin-right: 15%;
}

.block7 .galary2 figure:first-child figcaption h6{
    color: rgba(255, 255, 255, 0.548);
}

.block7 .galary2 figure:nth-child(2) figcaption h6{
    color: rgba(255, 255, 255, 0.548);
}

.block7 .galary2 figure:last-child figcaption{
    padding: 10%;
}

.block7 .relise{
    text-decoration: none;
    color:rgb(59, 143, 195);
}

.block7 a{
    text-decoration: none;
}

.block7 .relise:hover{
    text-decoration: underline;
}

.block7 h3:hover{
    text-decoration: underline;
}

.block7 .using:hover{
    text-decoration: underline;
}

.block7 .change{
    text-decoration: none;
    color: black;
}

.block7 .change:hover{
    text-decoration: underline;
}

.block7 span{
    color: #4E5A73 !important;
}

@media (max-width: 500px) {
  
  .block7 .galary1 {
        flex-direction: column;
    }

    .block7 .galary1>* {
        width: 95% !important;
    }

    .block7 .galary2 {
        flex-direction: column;
    }

    .block7 .galary2>* {
        width: 95% !important;
        margin-bottom: 20px !important;
        margin-top: 50px !important;
    }

}
  </style>