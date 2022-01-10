<template>
    <section>
        <div class="container">
            <h2>Service your customers around the world from 12 regions</h2>
            <div class="row">
                <div class="col-12 col-md-6 mb-4 mb-md-0">
                    <div class="line">
                        <div class="left">
                            <span class="sign">AMS2</span>
                            <span class="region">Amsterdam, Netherlands</span>
                        </div>
                        <div class="right">
                            <a href="#" class="text-decoration-none">Test speed<span class="ms-2">></span></a>
                        </div>
                    </div>
                    <div class="line">
                        <div class="left">
                            <span class="sign">AMS3</span>
                            <span class="region">Amsterdam, Netherlands</span>
                        </div>
                        <div class="right">
                            <a href="#" class="text-decoration-none">Test speed<span class="ms-2">></span></a>
                        </div>
                    </div>
                    <div class="line">
                        <div class="left">
                            <span class="sign">BLR1</span>
                            <span class="region">Bangalore, India</span>
                        </div>
                        <div class="right">
                            <a href="#" class="text-decoration-none">Test speed<span class="ms-2">></span></a>
                        </div>
                    </div>
                    <div class="line">
                        <div class="left">
                            <span class="sign">FRA1</span>
                            <span class="region">Frankfurt, German</span>
                        </div>
                        <div class="right">
                            <a href="#" class="text-decoration-none">Test speed<span class="ms-2">></span></a>
                        </div>
                    </div>
                    <div class="line">
                        <div class="left">
                            <span class="sign">LON1</span>
                            <span class="region">London, UK</span>
                        </div>
                        <div class="right">
                            <a href="#" class="text-decoration-none">Test speed<span class="ms-2">></span></a>
                        </div>
                    </div>
                    <div class="line">
                        <div class="left">
                            <span class="sign">NYC1</span>
                            <span class="region">New York, USA</span>
                        </div>
                        <div class="right">
                            <a href="#" class="text-decoration-none">Test speed<span class="ms-2">></span></a>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-6">
                    <div class="line">
                        <div class="left">
                            <span class="sign">AMS2</span>
                            <span class="region">Amsterdam, Netherlands</span>
                        </div>
                        <div class="right">
                            <a href="#" class="text-decoration-none">Test speed<span class="ms-2">></span></a>
                        </div>
                    </div>
                    <div class="line">
                        <div class="left">
                            <span class="sign">AMS3</span>
                            <span class="region">Amsterdam, Netherlands</span>
                        </div>
                        <div class="right">
                            <a href="#" class="text-decoration-none">Test speed<span class="ms-2">></span></a>
                        </div>
                    </div>
                    <div class="line">
                        <div class="left">
                            <span class="sign">BLR1</span>
                            <span class="region">Bangalore, India</span>
                        </div>
                        <div class="right">
                            <a href="#" class="text-decoration-none">Test speed<span class="ms-2">></span></a>
                        </div>
                    </div>
                    <div class="line">
                        <div class="left">
                            <span class="sign">FRA1</span>
                            <span class="region">Frankfurt, German</span>
                        </div>
                        <div class="right">
                            <a href="#" class="text-decoration-none">Test speed<span class="ms-2">></span></a>
                        </div>
                    </div>
                    <div class="line">
                        <div class="left">
                            <span class="sign">LON1</span>
                            <span class="region">London, UK</span>
                        </div>
                        <div class="right">
                            <a href="#" class="text-decoration-none">Test speed<span class="ms-2">></span></a>
                        </div>
                    </div>
                    <div class="line">
                        <div class="left">
                            <span class="sign">NYC1</span>
                            <span class="region">New York, USA</span>
                        </div>
                        <div class="right">
                            <a href="#" class="text-decoration-none">Test speed<span class="ms-2">></span></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Regions'
}
</script>

<style lang="scss" scoped>

    section {
        background: rgb(0,65,190);
        background: linear-gradient(180deg, rgba(0,65,190,1) 0%, rgba(17,23,182,1) 100%);
        padding: 60px 0;

        h2 {
            text-align: center;
            color: white;
            margin-bottom: 20px;
        }

        .line {
            font-size: 14px;
            display: flex;
            justify-content: space-between;
            padding: 6px 10px;
            border-bottom: 1px solid white;

            @media (max-width: 992px) {
                font-size: 12px;
            }

            @media (max-width: 400px) {
                font-size: 11px;
            }

            &:last-child {
                border-bottom: none;
            }

            .left {
                .sign {
                    display: inline-block;
                    min-width: 40px;
                    margin-right: 50px;
                    color: white;
                }

                .region {
                    color: #c6cbdf;
                }
            }

            .right {
                a {
                    color: #00acca;
                }
            }
        }
    }

</style>