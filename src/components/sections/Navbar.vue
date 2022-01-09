<template>
    <nav class="navbar navbar-expand-lg navbar-light">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse my_collapse" id="navbarNavDropdown">
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

        @media (max-width: 992px) {
            justify-content: flex-end !important;

            .my_collapse {
                position: absolute;
                top: 70px;
                right: 0;
                background-color: white;
                padding: 5px;
                border-radius: 10px;
                box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;

                

                ul {
                    align-items: flex-start !important;

                    @media (max-width: 400px) {


                        font-size: 10px;
                    }

                    &.right {
                        margin-top: 8px;
                    }

                    li {
                        margin: 5px 10px !important;
                    }
                }
            }

            

            
        }

        


        > div {
            display: flex;
            justify-content: space-between;
        }

        ul {
            height: 100%;
            display: flex;
            list-style: none;
            align-items: center;
            font-size: 14px;

            @media (max-width: 1200px) {
                font-size: 13px;
            }

            @media (max-width: 1040px) {
                font-size: 12px;
            }

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