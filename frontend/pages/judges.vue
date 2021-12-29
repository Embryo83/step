<template>
    <div class="main">
        <Nav />
        <div class="main__sector">
            <Judges />
            <Sidebar />
        </div>
        <Footer />
    </div>
</template>

<script>
import Nav from '@/components/Nav.vue';
import Footer from '@/components/Footer.vue';

export default {
    components: {
        Nav,
        Footer,
    },
};
</script>

<style lang="scss">
    .main__sector {
        display: flex;
        flex-direction: row;
        width: 100%;
        border-radius: 25px;
    }
</style>
