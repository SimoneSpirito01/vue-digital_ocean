<template>
    <section>
        <div class="container text-center">
            <div class="text">
                <h2>Designed for developers</h2>
                <p>Build more and spend less time managing your infrastructure with our easy-to-use control panel and API.</p>
            </div>
            <div class="content">
                <div class="slider">
                    <i class="fas fa-chevron-left"></i>
                    <img src="../../assets/img/slide.jpg" alt="slider">
                    <i class="fas fa-chevron-right"></i>
                </div>
                <div class="bottom">
                    <p>Create compute servers in 55 seconds or less.</p>
                    <div class="dots">
                        <div class="dot active"></div>
                        <div class="dot"></div>
                        <div class="dot"></div>
                        <div class="dot"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Slider'
}
</script>

<style lang="scss" scoped>

    section {
        background-color: #f3f5f9;
        padding: 60px 0;

        .text {
            margin-bottom: 60px;
            color: #485d80;

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

            img {
                width: 70%;
                max-width: 500px;
                margin: 0 20px;
            }
        }

        .bottom {
            margin-top: 17px;

            p {
                color: #070968;
                font-size: 14px;
            }

            .dots {
                display: flex;
                justify-content: center;

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
    }

</style>