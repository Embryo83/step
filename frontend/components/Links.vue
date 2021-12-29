<template>
    <div class="links">
        <ul class="links__items">
            <li class="links__item"><a href="https://vk.com/fest_stepbystep" target="_blank"><img src="~/static/img/vk.svg" class="links__logo" alt="Логотип VK" /></a></li>
            <li class="links__item"><a href="https://www.instagram.com/adam.nora/" target="_blank"><img class="links__logo" src="~/static/img/instagram.png" alt="Логотип Instagram" /></a></li>
            <li class="links__item"><a href="http://noraadam.ru" target="_blank">Сайт Норы Адам</a></li>
        </ul>
    </div>
</template>

<script>
export default {
};
</script>

<style lang="scss">
    .links {
        width: 100%;
        margin-top: 20px;

        &__items {
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            align-items: flex-end;
        }

        &__logo {
            width: 30px;
            margin-right: 10px;
        }

        &__item:hover {
            opacity: 0.7;
            cursor: pointer;
        }
    }
</style>
