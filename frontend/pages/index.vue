<template>
    <div class="main">
        <Nav />
        <div class="main__sector">
            <Bio />
            <Sidebar />
        </div>
        <Footer />
    </div>
</template>

<script>
import Nav from '@/components/Nav.vue';
import Bio from '@/components/Bio.vue';
import Sidebar from '@/components/Sidebar.vue';
import Footer from '@/components/Footer.vue';

export default {
    components: {
        Nav,
        Bio,
        Sidebar,
        Footer,
    },
};
</script>

<style lang="scss">
    .main {
        &__sector {
            display: flex;
            flex-direction: row;
        }
    }
</style>
