<template>
    <footer>
        <div class="container">
            <div class="row">
                <div class="col-12 col-lg-4 mb-4 mb-lg-0 left">
                    <img src="../../assets/img/logo-small.svg" alt="">
                    <p class="copy"><i class="far fa-copyright"></i> 2018 DigitalOcean, LLC. All rights reserved.</p>
                    <p class="made">Proudly made in NY</p>
                    <div class="social">
                        <i class="fab fa-twitter"></i>
                        <i class="fab fa-facebook-square"></i>
                        <i class="fab fa-instagram"></i>
                        <i class="fab fa-youtube"></i>
                        <i class="fab fa-linkedin"></i>
                    </div>

                </div>
                <div class="col-12 col-lg-8 right">
                    <div class="row">
                        <div class="col-12 col-md-6 col-lg-3 mb-3 mb-lg-0">
                            <ul>
                                <li>Company</li>
                                <li>About</li>
                                <li>Leadership</li>
                                <li>Link</li>
                                <li>Blog</li>
                                <li>Careers</li>
                                <li>Partner Network</li>
                                <li>Referral Program</li>
                                <li>Events</li>
                                <li>Press</li>
                                <li>Legal & Security</li>
                            </ul>
                        </div>
                        <div class="col-12 col-md-6 col-lg-3 mb-3 mb-lg-0">
                            <ul>
                                <li>Products</li>
                                <li>Droplets</li>
                                <li>Spaces</li>
                                <li>Kubernetes</li>
                                <li>Load Balancers</li>
                                <li>Block Storage</li>
                                <li>Tools & Integrations</li>
                                <li>One-Click Apps</li>
                                <li>API</li>
                                <li>Pricing</li>
                                <li>Documentation</li>
                                <li>Release Notes</li>
                            </ul>
                        </div>
                        <div class="col-12 col-md-6 col-lg-3">
                            <ul>
                                <li>Community</li>
                                <li>Tutorials</li>
                                <li>Meetups</li>
                                <li>Q&A</li>
                                <li>Write for Donations</li>
                                <li>Droplets for Demos</li>
                                <li>Hatch</li>
                                <li>Shop Swag</li>
                                <li>Research Program</li>
                                <li>Currents Research</li>
                                <li>Open Source</li>
                            </ul>
                        </div>
                        <div class="col-12 col-md-6 col-lg-3">
                            <ul>
                                <li>Support</li>
                                <li>Contact support</li>
                                <li>FAQ</li>
                                <li>Network Status</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>

    footer {
        background-color: #031c4e;
        padding: 60px 0;

        .left {
            font-size: 14px;
            img {
                width: 40px;
            }

            .copy {
                color: #7f8aa2;
                margin: 10px 0 0;
            }

            .made {
                color: #4f5e7f;
            }

            .social {
                svg {
                    color: #7f8aa2;
                    font-size: 18px;
                    margin-right: 7px;
                    cursor: pointer;
                    transition: transform 0.5s;

                    &:hover {
                        transform: scale(1.2);
                    }
                }
            }
        }

        .right {

            ul {
                list-style: none;
                color: #78829a;
                font-size: 14px;
                padding: 0;

                li {
                    margin-bottom: 8px;
                    cursor: pointer;

                    &:not(:first-child):hover {
                        text-decoration: underline;
                    }

                    &:first-child {

                        font-size: 16px;
                        color: white;
                    }
                }
            }
        }
    }

</style>