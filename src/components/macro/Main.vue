<template>
    <main>
        <Hero/>
        <Customers/>
        <Deploy/>
    </main>
</template>

<script>
import Hero from '../sections/Hero.vue'
import Customers from '../sections/Customers.vue'
import Deploy from '../sections/Deploy.vue'

export default {
    name: 'Main',
    components: {
        Hero,
        Customers,
        Deploy
    }
}
</script>

<style lang="scss" scoped>

</style>