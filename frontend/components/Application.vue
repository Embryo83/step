<template>
    <div class="application">
        <div class="application__form">
            <h2 class="application__title">Подать заявку участника</h2>
            <p class="application__add"><span class="application__add_red">*</span> - поля, обязательные для заполнения.</p>
            <script src="https://yastatic.net/s3/frontend/forms/_/embed.js">
                Заявка
            </script>
            <iframe src="https://forms.yandex.ru/u/5ca9ed1e19621d29781c9161/?iframe=1" frameborder="0" name="ya-form-5ca9ed1e19621d29781c9161" width="650">
                Форма
            </iframe>
        </div>
    </div>
</template>

<script>
export default {
    components: {

    },
};
</script>

<style lang="scss">
    .application {
        width: 70%;
        color: #fff;
        border-radius: 25px;
        background: radial-gradient(ellipse farthest-corner at top left, #e36b21 31%, #f6f652 90%);
        margin-left: 50px;

        &__form {
            margin: 10% 15%;
        }

        &__title {
            font-family: Oswald, Arial, sans-serif;
            font-size: 36px;
        }

        &__add {
            font-family: Oswald, Arial, sans-serif;
            font-size: 16px;
            font-weight: 300;
            margin-bottom: 5px;

            &_red {
                text-shadow: 0 0 5px #fff;
                color: #f80000;
            }
        }
    }
</style>
