<template>
    <section>
        <div class="container">
            <h2>The features your business needs</h2>
            <div class="row features">
                <div class="col-12 col-md-4 mb-4 mb-md-0">
                    <div class="image">
                        <img src="../../assets/img/pred-pricing.svg" alt="">
                    </div>
                    <div class="title">
                        <span>Predictable pricing</span>
                    </div>
                    <div class="text">
                        <p>
                            Leave complex pricing structures behind. Always
                            know what youIl pay per month with a flat,
                            industry-leading pricing structure.
                        </p>
                        <a href="#" class="text-decoration-none">Pricing <span class="ms-2">></span></a>
                    </div>
                </div>
                <div class="col-12 col-md-4 mb-4 mb-md-0">
                    <div class="image">
                        <img src="../../assets/img/world-class.svg" alt="">
                    </div>
                    <div class="title">
                        <span>World-class service</span>
                    </div>
                    <div class="text">
                        <p>
                            Free round-the-clock technical support for all
                            customers. Youill feel the love.                        
                        </p>
                        <a href="#" class="text-decoration-none">Support <span class="ms-2">></span></a>
                    </div>
                </div>
                <div class="col-12 col-md-4 mb-4 mb-md-0">
                    <div class="image">
                        <img src="../../assets/img/reliable-platform.svg" alt="">
                    </div>
                    <div class="title">
                        <span>Reliable platform</span>
                    </div>
                    <div class="text">
                        <p>
                            More than 100,000 developer teams worldwide
                            trust DigitalOcean to support their business with
                            a 99.99% uptime SLA for all services.
                        </p>
                        <a href="#" class="text-decoration-none">Security <span class="ms-2">></span></a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Features'
}
</script>

<style lang="scss" scoped>

    section {
        padding: 60px 0;

        h2 {
            color: #041d4e;
            text-align: center;
            margin-bottom: 30px;
        }

        img {
            margin-bottom: 10px;
        }

        .title {
            color: #041d4e;
            font-weight: bold;
            margin-bottom: 5px;
        }

        .text {
            font-size: 14px;
        }
    }

</style>