<template>
    <div class="footer">
        <p class="footer__copyright">
            2017-2022 Международный Арт-Центр ШАГ ЗА ШАГОМ
        </p>
        <div class="footer__links">
            <Links />
        </div>
    </div>
</template>

<script>
export default {
};
</script>

<style lang="scss">
    .footer {
        display: flex;
        justify-content: space-between;
        width: 90%;
        height: 50px;
        margin: 10px auto;

        &__copyright {
            font-family: Oswald, Arial, sans-serif;
            font-size: 18px;
            font-weight: 200;
            margin-top: 30px;
        }

        &__copyright::before {
            content: '\00a9';
        }

        &__links {
            float: right;
            width: 20%;
            font-family: Oswald, Arial, sans-serif;
        }
    }
</style>
