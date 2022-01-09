<template>
    <section>
        <div class="container">
            <strong>Innovative businesses trust digitalocean</strong>
            <div class="row customers">
                <div class="col-6 col-md-2 logo">
                    <img src="../../assets/img/docker.svg" alt="docker-logo">
                </div>
                <div class="col-6 col-md-2 logo">
                    <img src="../../assets/img/gitlab.svg" alt="gitlab-logo">
                </div>
                <div class="col-6 col-md-2 logo">
                    <img src="../../assets/img/slack.svg" alt="slack-logo">
                </div>
                <div class="col-6 col-md-2 logo">
                    <img src="../../assets/img/hashicorp.svg" alt="hashicorp-logo">
                </div>
                <div class="col-6 col-md-2 logo">
                    <img src="../../assets/img/wework.svg" alt="wework-logo">
                </div>
                <div class="col-6 col-md-2 logo">
                    <img src="../../assets/img/splunk.svg" alt="splunk-logo">
                </div>
            </div>
            <a href="#" class="text-decoration-none">View customers stories <span class="ms-2">></span></a>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Customers'
}
</script>

<style lang="scss" scoped>

    section {
        font-size: 14px;
        background-color: #f3f5f9;
        text-align: center;
        padding: 35px 0;

        strong {
            text-transform: uppercase;
            color: #707d9a;
        }

        .customers {
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 16px 0;

            .logo {
                transition: transform 0.5s;
                cursor: pointer;
                
                &:hover {
                    transform: scale(1.2);
                }

                img {
                    width: 100%;
                }
            }
        }

        p {
            color: #0051ff;
            margin: 0;
        }
    }

</style>