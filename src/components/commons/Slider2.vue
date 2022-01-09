<template>
    <section>
        <div class="container text-center">
            <div class="text">
                <h2>Development teams love DigitalOcean</h2>
            </div>
            <div class="slider">
                <i class="fas fa-chevron-left"></i>
                <div class="rockerbox py-3 py-md-0">
                    <img src="../../assets/img/rockerbox.png" alt="logo_rockerbox">
                    <p class="quote">"We have been able to make scaling the technical infrastructure of our business cost effective and efficient."</p>
                    <p class="name">Rick O'Toole</p>
                    <p class="work">Co-founder and CTO</p>
                    <a href="#" class="text-decoration-none">Read story <span class="ms-2">></span></a>
                </div>
                <i class="fas fa-chevron-right"></i>
            </div>
            <div class="dots">
                <div class="dot active"></div>
                <div class="dot"></div>
                <div class="dot"></div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Slider2'
}
</script>

<style lang="scss" scoped>

    section {
        background-color: #f3f5f9;
        padding: 60px 0;

        .text {
            margin-bottom: 70px;

            h2 {
                font-size: 27px;
                margin-bottom: 20px;
                color: #041d4e;
            }
        }

        .slider {
            display: flex;
            justify-content: center;
            align-items: center;

            svg {
                font-size: 30px;
                color: #041d4e;
                cursor: pointer;

                &:hover {
                    color: #4f6da9;
                }
            }

            .rockerbox {
                width: 70%;
                max-width: 500px;
                aspect-ratio: 1.54;
                background-color: #ffffff;
                margin: 0 20px;
                padding: 0 10px;
                border-radius: 5px;
                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;

                img {
                    width: 80%;
                    max-width: 270px;
                    margin-bottom: 20px;
                }

                .quote, .work {
                    color: #5f6d8c;
                }

                .quote {
                    margin-bottom: 10px;
                }

                .name {
                    color: #2b2d58;
                    font-size: 15px;
                    margin-bottom: 2px;
                }

                .work {
                    font-size: 14px;
                    margin-bottom: 20px;
                }
            }
        }

        .dots {
            display: flex;
            justify-content: center;
            margin-top: 27px;

            .dot {
                width: 10px;
                aspect-ratio: 1;
                border-radius: 50%;
                border: 1px solid #006aff;
                margin: 0 2px;
                cursor: pointer;

                &.active {
                    background-color: #006aff;
                }
            }
        }
    }

</style>