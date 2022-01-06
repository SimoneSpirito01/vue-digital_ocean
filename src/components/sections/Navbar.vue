<template>
    <!-- <nav>
        <ul class="navbar-nav left">
            <li v-for="(liLeft, i) in navLeft" :key="i" v-html="liLeft" class="nav-item"></li>
            
        </ul>
        <ul class="navbar-nav right">
            <li  v-for="(liRight, i) in navRight" :key="'A' + i" v-html="liRight" class="nav-item"></li>
        </ul>
    </nav> -->
    <nav class="navbar navbar-expand-lg navbar-light">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <ul class="navbar-nav left">
                <li v-for="(liLeft, i) in navLeft" :key="i" v-html="liLeft" class="nav-item"></li>
                
            </ul>
            <ul class="navbar-nav right">
                <li  v-for="(liRight, i) in navRight" :key="'A' + i" v-html="liRight" class="nav-item"></li>
                <li>
                    <button>Sign Up</button>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>
export default {
    name: 'Navbar',
    data() {
        return {
            navLeft: [
                `Products <i class="fas fa-chevron-down"></i>`,
                'Customers',
                `Community <i class="fas fa-chevron-down"></i>`,
                'Pricing'
            ],
            navRight: [
                'Docs',
                `Support <i class="fas fa-chevron-down"></i>`,
                'Login'
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../../assets/global.scss';

    nav {
        width: 70%;
        height: 100%;

        > div {
            display: flex;
            justify-content: space-between;
        }

        ul {
            height: 100%;
            display: flex;
            list-style: none;
            align-items: center;

            li {
                margin: 0 10px;
                cursor: pointer;

                button {
                    color: $blue;
                    background-color: white;
                    padding: 5px 10px;
                    border: 1px solid $blue;
                    border-radius: 5px;
                }
            }
            
        }
    }

</style>