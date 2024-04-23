<template>
    <!-- header -->
    <header class="header ">
        <!-- div contentente il logo  -->
        <div class="container d_flex">
            <div>
                <img class="logo" src="/public/logo.png" alt="">
            </div>
            <!-- lista contenente 6 list-item  cliccabili e un bottone con un icon lente vicino   -->
            <ul class="d_flex_menu  menu_list">
                <li><a href="">Home</a></li>
                <li><a href="">Apple</a></li>
                <li><a href="">Microsoft</a></li>
                <li><a href="">Android</a></li>
                <li><a href="">Forums</a></li>
                <li><a href="">Contact us</a></li>
                <li><button class="button black">JOIN US</button></li>
                <li><a href="">lente</a></li>
            </ul>
        </div>

    </header>
</template>

<script>
export default {
    data() {


        return {}
    }
}
</script>

<style lang="scss" scoped>
.header {
    background-color: rgb(40, 175, 195);
    padding: 10px;
    color: white;
}

.d_flex {
    display: flex;
    justify-content: space-between;
}

.logo {
    width: 180px;
    cursor: pointer;
}

.menu_list {
    flex-grow: 1;
}

.d_flex_menu {
    display: flex;
    justify-content: flex-end;
    gap: 40px;
    align-items: center;
}
</style>