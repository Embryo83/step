<template>
    <div class="sidebar">
        <div class="sidebar__contacts">
            <p class="sidebar__text">
                КОНТАКТЫ
            </p>
            <ul class="sidebar__items">
                <li>
                    8-963-602-24-10
                </li>
                <li>
                    8-903-149-27-14
                </li>
                <li>
                    8-916-522-94-84
                </li>
                <li>
                    center-stepbystep@yandex.ru
                </li>
            </ul>
            <Links />
        </div>
        <div class="sidebar__contacts">
            <p class="sidebar__text">
                НАШИ ПАРТНЁРЫ
            </p>
            <img class="sidebar__pic" src="~/static/img/partner-fur.jpg" alt="Меховая мастерская" />
        </div>
    </div>
</template>

<script>
export default {
};
</script>

<style lang="scss">
    .sidebar {
        width: 20%;
        color: #fff;
        border-radius: 25px;
        background: radial-gradient(ellipse farthest-corner at top left, #e36b21 31%, #f6f652 90%);
        margin-right: 50px;
        margin-left: 20px;

        &__items {
            font-size: 16px;
            line-height: 1.3;
            font-weight: 300;
            color: #f6f652;
            margin-top: 10px;
        }

        &__contacts {
            font-family: Oswald, Arial, sans-serif;
            background-color: #000, transparent 20%;
            margin-top: 20px;
            margin-left: 10%;
        }

        &__text {
            font-size: 20px;
            font-weight: 400;
        }

        &__pic {
            color: #000;
            border-radius: 25px;
            box-shadow: 1px 1px 5px;
            margin-top: 10px;
        }
    }
</style>
