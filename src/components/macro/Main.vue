<template>
    <main>
        <Hero/>
        <Customers/>
        <Deploy/>
        <Slider/>
        <Features/>
        <Regions/>
        <Slider2/>
        <Start/>
    </main>
</template>

<script>
import Hero from '../sections/Hero.vue'
import Customers from '../sections/Customers.vue'
import Deploy from '../sections/Deploy.vue'
import Slider from '../commons/Slider.vue'
import Slider2 from '../commons/Slider2.vue'
import Features from '../sections/Features.vue'
import Regions from '../sections/Regions.vue'
import Start from '../sections/Start.vue'

export default {
    name: 'Main',
    components: {
        Hero,
        Customers,
        Deploy,
        Slider,
        Slider2,
        Features,
        Regions,
        Start
    }
}
</script>

<style lang="scss" scoped>

</style>