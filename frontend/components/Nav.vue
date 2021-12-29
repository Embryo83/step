<template>
    <div class="header">
        <div class="header__search">
            <p class="header__subtitle">МЕЖДУНАРОДНЫЙ АРТ-ЦЕНТР</p>
            <p class="header__title">ШАГ ЗА ШАГОМ<i><img class="header__logo" src="~/static/img/cup.svg" alt="cup" /></i></p>
            <p class="header__description">многожанровые конкурсы</p>
        </div>
        <nav class="header__menu">
            <NLink class="header__menu-item" to="/">ГЛАВНАЯ</NLink>
            <NLink class="header__menu-item" to="/table">ГРАФИК</NLink>
            <NLink class="header__menu-item" to="/judges">ЖЮРИ</NLink>
            <NLink class="header__menu-item" to="/application">ЗАЯВКА</NLink>
        </nav>
    </div>
</template>

<script>
export default {
};
</script>

<style lang="scss">
    .header {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        margin: 25px;

        &__search {
            top: 33px;
            left: 33%;
            color: #f80000;
        }

        &__logo {
            width: 23px;
            height: 23px;
            padding-top: 5px;
            color: #bbb;
            fill: #aaa;
        }

        &__title {
            font-family: Oswald, Arial, sans-serif;
            font-size: 20px;
            font-weight: 700;
        }

        &__subtitle {
            font-family: Oswald, Arial, sans-serif;
            font-size: 12px;
            font-weight: 700;
            color: #020;
            opacity: 0.8;
        }

        &__description {
            font-family: Oswald, Arial, sans-serif;
            font-size: 14px;
            font-weight: 600;
            color: #020;
            opacity: 0.9;
        }

        &__menu {
            top: 40px;
            right: 100px;
            font-family: Oswald, Arial, sans-serif;
            font-size: 24px;
            line-height: 1.15;
            font-weight: 100;
            text-align: right;
        }

        &__menu-item {
            margin-left: 20px;
        }

        &__menu-item:hover {
            color: #e36b21;
        }
    }
</style>
