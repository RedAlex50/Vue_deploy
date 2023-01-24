<template>
    <div id="block6">
        <div class="header">
            Команда
        </div>
        <div class="team">
            <div class="desktop-flex">
                <div class="team-member">
                    <img src="@/img/IMG_2472_0.jpg" alt="Сергей Синица">
                    <div class="member-name">
                        Сергей Синица
                    </div>
                    <div class="member-text">
                        Руководитель отдела веб-разработки,
                        канд. техн. наук, заместитель директора
                    </div>
                </div>
                <div class="team-member">
                    <img src="@/img/IMG_2539_0.jpg" alt="Роман Агабеков">
                    <div class="member-name">
                        Роман Агабеков
                    </div>
                    <div class="member-text">
                        Руководитель отдела DevOPS, директор
                    </div>
                </div>
                <div class="team-member">
                    <img src="@/img/IMG_2474_1.jpg" alt="Алексей Синица">
                    <div class="member-name">
                        Алексей Синица
                    </div>
                    <div class="member-text">
                        Руководитель отдела поддержки сайтов
                    </div>
                </div>
            </div>
            <div class="desktop-flex">
                <div class="team-member">
                    <img src="@/img/IMG_2522_0.jpg" alt="Дарья Бочкарёва">
                    <div class="member-name">
                        Дарья Бочкарёва
                    </div>
                    <div class="member-text">
                        Руководитель отдела продвижения, 
                        контекстной рекламы и 
                        контент-поддержки сайтов
                    </div>
                </div>
                <div class="team-member">
                    <img src="@/img/IMG_9971_16.jpg" alt="Ирина Торкунова">
                    <div class="member-name">
                        Ирина Торкунова
                    </div>
                    <div class="member-text">
                        Менеджер по работе с клиентами
                    </div>
                </div>
                <div class="team-member">
                    <img src="" alt="">
                    <div class="member-name">

                    </div>
                    <div class="member-text">

                    </div>
                </div>
            </div>
        </div>
        
        <div class="team-btn">
            <button>
                ВСЯ КОМАНДА
            </button>
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

.team{
    width: 1200px;
    margin: 0 auto;
}

.team-member{
    width: 330px;
    margin: 2rem;
    margin-top: 0;
}

.team-member img{
    width: 330px;
}

.member-name{
    font-family: Montserrat-Bold;
    font-size: larger;
    margin-top: 1rem;
}

.member-text{
    margin-top: 1rem;
    color: #4f5a73;
}

.team-btn{
    margin: 2rem auto;
    width: fit-content;
}

.team-btn button{
    width: 15rem;
    height: 3rem;
    border: 1px solid gray;
    border-radius: 4px;
    color: #111111;
    background-color: white;
}

.team-btn button:hover{
    transition: 100ms;
    color: #ffffff;
    background-color: #111111;
}


</style>