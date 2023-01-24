<template>
    <div class="header">
        <div class="container">
            <div class="nav-logo">
                <a href=""><img src="@/img/drupal-coder.svg" alt="Drupal Coder"></a>
            </div>
            <div>
                <ul>
                    <li><a href="">ПОДДЕРЖКА DRUPAL</a></li>
                    <li><a href="">АДМИНИСТРИРОВАНИЕ</a></li>
                    <li><a href="">ПРОДВИЖЕНИЕ</a></li>
                    <li><a href="">РЕКЛАМА</a></li>
                    <li><a href="">О НАС #</a></li>
                    <li><a href="">ПРОЕКТЫ</a></li>
                    <li><a href="">КОНТАКТЫ</a></li>
                </ul>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
a{
    color: white;
    font-size: smaller;
    margin-right: 15px;
}
.header{
    width: 1200px;
    margin: 0 auto;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    padding-top: 30px;
    padding-bottom: 30px;
    background: transparent;
    z-index: 10;
}
.container{
    width: 1400px;
    display: flex;
    margin-left: auto;
    margin-right: auto;
}

.nav-logo a img{
    height: 2rem;
}

ul{
    color: white;
    list-style: none;
    display: flex;
}
</style>