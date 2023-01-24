<template>
    <div>
        
        <v-navbar></v-navbar>
        <v-header></v-header>
        <history></history>
        <support></support>
        <expert></expert>
        <tariffs></tariffs>
        <any-tasks></any-tasks>
        <team></team>
        <last-cases></last-cases>
        <reviews></reviews>
        <works></works>
        <faq></faq>
        <v-footer></v-footer>
        <div class="form">
            <v-form :isVisible="formVisible"
                @close="formVisible = false"
            />
        </div>
        <button class="btn-for-form" @click="formAppear">
            СВЯЗЬ С НАМИ
        </button>
    </div>
</template>

<script>
import VNavbar from './components/0_Navbar.vue';
import VHeader from './components/1_Header.vue';
import History from './components/2_History.vue';
import Support from './components/3_Support.vue';
import Expert from './components/4_Expert.vue';
import Tariffs from './components/5_Tariffs.vue';
import AnyTasks from './components/6_AnyTasks.vue';
import Team from './components/7_Team.vue';
import LastCases from './components/8_LastCases.vue';
import Reviews from './components/9_Reviews.vue';
import Works from "./components/10_Works.vue";
import Faq from "./components/11_Faq.vue";
import VFooter from "./components/12_Footer.vue";
import VForm from "./components/VForm.vue";

export default {
    components:{
        VNavbar,
        VHeader,
        History,
        Support,
        Expert,
        Tariffs,
        AnyTasks,
        Team,
        LastCases,
        Reviews,
        Works,
        Faq,
        VFooter,
        VForm,
    },
    data(){
        return {
            formVisible: false,
        }
    },
    methods: {
        formAppear(){
            if (this.formVisible)
                this.formVisible = false;
            else
                this.formVisible = true;
        }
    }
}

</script>

<style>
.form{
    position: fixed;
    top: 20%;
    left: 35%;
}

.btn-for-form{
    color: white;
    position: fixed;
    top: 90%;
    left: 85%;
    z-index: 3000;
    border: 2px solid #f14d34;
    border-radius: 4px;
    padding: 15px;
    padding-left: 25px;
    padding-right: 25px;
    background-color: rgba(0, 0, 0, 0.747);
}
.btn-for-form:hover{
    color: black;
    background-color: #f14d34;
    transition: 0.5s;
    cursor: pointer;
}

@font-face {   
    font-family: Montserrat;
    src: url(@/fonts/Montserrat-VariableFont_wght.ttf);
}

@font-face {  
font-family: Montserrat-Bold;
    src: url(@/fonts/Montserrat-Bold.ttf);
}

html {
    font-family: Montserrat;
}
:root{
    --font-block:14px;
}


html {
    font-family: Montserrat;
}
:root{
    --font-block:14px;
}

a {
    text-decoration: none;
}

</style>
