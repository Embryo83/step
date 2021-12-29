<template>
    <div class="bio">
        <div class="bio__promo">
            <div class="bio__promo_left">
                <img class="bio__logo" src="~/static/img/logo.png" alt="Logo" />
                <div class="bio__presentation">
                    <p class="bio__description">
                        представляет
                    </p>
                    <p class="bio__title">
                        НОВЫЕ
                    </p>
                    <p class="bio__subtitle">
                        Международные конкурсы в 2022-м году.
                    </p>
                </div>
            </div>
            <div class="bio__promo_right">
                <img class="bio__pic" src="~/static/img/bio.jpg" alt="Нора Адам" />
            </div>
        </div>
        <p class="bio__text">
            В 2022-м году наш Арт-Центр открывает 7-й сезон
            Международных конкурсов для вокалистов, инструменталистов,
            концертмейстеров, хореографических коллективов и солистов,
            артистов  и учащихся оригинального жанра, ведущих, учащихся
            театрального и актерского мастерства, изобразительного и
            прикладного искусства, театров мод. Идейный вдохновитель
            проекта и его основатель, Нора Адам, как никто знает,
            что молодому таланту необходима творческая реализация,
            как важна поддержка со стороны профессионалов музыкальной
            индустрии, готовых поделиться своими ценными навыками
            и опытом.
        </p>
        <p class="bio__text">
            Нора – профессиональный музыкант, скрипач, альтист, певица
            и топ-педагог разножанрового вокала, а также вокальный
            саунд-продюсер.
            За плечами профессионала два высших музыкальных образования,
            огромный многолетний опыт профессиональной концертной
            деятельности.
        </p>
        <p class="bio__text">
            "Наш Арт-Центр является стартовой площадкой для развития
            талантов из всех уголков нашей страны. Это мощный старт-ап
            для развития творческой личности. У нас нет возрастных
            ограничений. У нас нет ограничений в музыкальных форматах.
            Успех приходит к тем, кто имеет цель и без остатка отдает
            себя любимому делу. Ждем Вас на наших конкурсах и желаем
            большой удачи!"
        </p>
        <p class="bio__text">
            С уважением, председатель жюри, генеральный директор
            Международного Арт-Центра «Шаг за Шагом» <span class="bio__text_bold">Нора АДАМ</span>.
        </p>
    </div>
</template>

<script>

export default {
    components: {

    },
};
</script>

<style lang="scss">
    .bio {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        box-sizing: border-box;
        width: 70%;
        border-radius: 25px;
        background: radial-gradient(ellipse farthest-corner at top left, #e36b21 31%, #f6f652 90%);
        margin-left: 50px;

        &__promo {
            display: flex;
            flex-direction: row;
            justify-content: space-around;
            width: 100%;
        }

        &__logo {
            width: 500px;
            margin-top: 40px;
        }

        &__pic {
            max-width: 460px;
            height: 75vh;
            border-radius: 25px;
            margin-top: 30px;
        }

        &__container {
            padding: 40px 6.95% 40px 3%;
        }

        .bio__info {
            display: flex;
            flex-direction: row;
            flex-wrap: nowrap;
            justify-content: center;
            align-items: flex-start;
            max-width: 640px;

            &--left {
                width: 59px;
                white-space: nowrap;
                -webkit-transform: rotate(-90deg); // разворот элемента для разных бразуеров
                -moz-transform: rotate(-90deg);
                -ms-transform: rotate(-90deg);
                -o-transform: rotate(-90deg);
                transform: rotate(-90deg);
            }

            &--right {
                margin-left: 10px;
            }
        }

        .bio__date {
            width: 302px;
            height: 59px;
            font-size: 64px;
            line-height: 0.9;
            font-weight: 400;
        }

        &__presentation {
            width: 340px;
            color: #fff;
            margin-top: 20px;
            margin-left: 80px;
        }

        &__title {
            font-family: Oswald, Arial, sans-serif;
            font-size: 48px;
            font-weight: 700;
            text-shadow: 0 0 5px #fff;
            color: #f80000;
        }

        &__subtitle {
            font-family: Oswald, Arial, sans-serif;
            font-size: 32px;
            line-height: 1.3;
            font-weight: 500;
        }

        &__description {
            max-width: 320px;
            font-family: Oswald, Arial, sans-serif;
            font-size: 30px;
            line-height: 1.3;
            font-weight: 600;
            opacity: 0.9;
        }

        &__text {
            width: 80%;
            font-family: Oswald, Arial, sans-serif;
            font-size: 18px;
            line-height: 1.8;
            font-weight: 200;
            margin-top: 30px;
            margin-left: 50px;

            &_bold {
                font-weight: 500;
            }
        }

        &__text:last-child {
            margin-bottom: 50px;
        }
    }
</style>
