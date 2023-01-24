<template>
    <div class="block9">
        <div class="work">С нами работают</div>
        <h4>Десятки компаний доверяют нам самое ценное, что у них есть
            в интернете - свои сайты. Мы делаем всё, чтобы наше сотрудничество
            было долгим.</h4>
        <div class="slider">
            <div class="row1">
                <split-carousel :height="200" :interval="1000">
                    <split-carousel-item>
                        <img src="@/img/farbors_ru.jpg"/>
                    </split-carousel-item>
                    <split-carousel-item>
                        <img src="@/img/Frame_3_(1).png"/>
                    </split-carousel-item>
                    <split-carousel-item>
                        <img src="@/img/Frame_3_2.png" />
                    </split-carousel-item>
                    <split-carousel-item>
                        <img src="@/img/Frame_3_3.png" />
                    </split-carousel-item>
                    <split-carousel-item>
                        <img src="@/img/logo_2.png" />
                    </split-carousel-item>
                    <split-carousel-item>
                        <img src="@/img/logo-estee.png"/>
                    </split-carousel-item>
                    <split-carousel-item>
                        <img src="@/img/logo-estee.png" />
                    </split-carousel-item>
                    <split-carousel-item>
                        <img src="@/img/nashagazeta_ch.png" />
                    </split-carousel-item>
                    <split-carousel-item>
                        <img src="@/img/farbors_ru.jpg" />
                    </split-carousel-item>
                    <split-carousel-item>
                        <img src="@/img/logo_0.png" />
                    </split-carousel-item>
                    <split-carousel-item>
                        <img src="@/img/Frame_3.png" />
                    </split-carousel-item>
                </split-carousel>
                
            </div>
            <div class="row2"></div>
        </div>
        
    </div>
</template>
<script>

export default {
    components: {
    },
    data() {
        return {
            imgs: [
                    '<img src="@/img/farbors_ru.jpg/>',
                    '<img src="@/img/Frame_3_(1).png/>',
                    '<img src="@/img/Frame_3_2.png/>',
                    '<img src="@/img/Frame_3_3.png/>',
                    '<img src="@/img/logo_2.png/>',
                    '<img src="@/img/logo-estee.png/>',
                    '<img src="@/img/logo-estee.png/>',
                    '<img src="@/img/nashagazeta_ch.png/>',
                    '<img src="@/img/farbors_ru.jpg/>',
                    '<img src="@/img/logo_0.png/>',
                    '<img src="@/img/Frame_3.png/>',
            ],
        };
    },
    
}


</script>
<style scoped>


.block9{
    width: 100vw; /* vw - view width - видимая  ширина окна просмотра браузера */
}

.block9 h4{
    color: #4E5A73;
    text-align: center;/* внутри блока текст по центру */
    width: 60%;
    margin: auto;
    margin-top: 20px;
}

.block9 .work{
    font-size: 32px;
    font-family: Montserrat-Bold;
    text-align: center;
}

.block9 .row1{
    display: flex;
    align-items: center;
}

.block9 .row1 img{
  margin-right: 10px;
  width: 20vw;
}

</style>