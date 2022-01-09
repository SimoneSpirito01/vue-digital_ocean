<template>
    <header>
        <div class="container-fluid">
            <Logo/>
            <Navbar/>
        </div>
    </header>
</template>

<script>
import Logo from '../commons/Logo.vue'
import Navbar from '../sections/Navbar.vue'

export default {
    name: 'Header',
    components: {
        Logo,
        Navbar
    }
}
</script>

<style lang="scss" scoped>

    .container-fluid {
        height: 70px;
        padding: 0 80px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        position: relative;

        @media (max-width: 640px) {
            padding: 0 20px;
        }

    }

</style>