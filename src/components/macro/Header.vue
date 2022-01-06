<template>
    <header>
        <div class="container">
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

    .container {
        height: 70px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

</style>