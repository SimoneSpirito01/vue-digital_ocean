<template>
    <section>
        <div class="container">
            <div class="text text-center">
                <h2>Deploy and scale seamlessly</h2>
                <p>Our optimized configuration process saves your team time when running and scaling distributed applications, AI & Machine learnin workloads, hosted services, client websites, or CI/CD environments</p>
            </div>
            <div class="row content">
                <div class="col-12 offset-md-1 col-md-3 mb-3">
                    <ul>
                        <li>Deploy</li>
                        <li>Manage</li>
                        <li>Secure</li>
                        <li>Scale</li>
                        <li>Monitor</li>
                    </ul>
                </div>
                <div class="col-12 col-md-7">
                    <div class="row">
                        <div class="col-12 col-md-6 ps-3 ps-lg-5 mb-3">
                            <div class="image">
                                <img src="../../assets/img/cluster-deploy.svg" alt="">
                            </div>
                            <div class="title">
                                <span>Cluster deployments</span>
                            </div>
                            <div class="text">
                                <p>
                                    Provision multiple Droplets (virtual
                                    machines) in seconds with our control
                                    panel, CLI, or directly against our API
                                </p>
                            </div>
                        </div>
                        <div class="col-12 col-md-6 ps-3 ps-lg-5 mb-3">
                            <div class="image">
                                <img src="../../assets/img/one-click.svg" alt="">
                            </div>
                            <div class="title">
                                <span>One-click apps</span>
                            </div>
                            <div class="text">
                                <p>
                                    Skip the install and configuration process
                                    with pre-built open source images
                                    supporting Rails, Cassandra, Docker, and
                                    more.
                                </p>
                            </div>
                        </div>
                        <div class="col-12 col-md-6 ps-3 ps-lg-5 mb-3">
                            <div class="image">
                                <img src="../../assets/img/cluster-deploy.svg" alt="">
                            </div>
                            <div class="title">
                                <span>Optimized compute types</span>
                            </div>
                            <div class="text">
                                <p>
                                    Get the compute resources you need with
                                    Standard or Optimized Droplets.
                                </p>
                            </div>
                        </div>
                        <div class="col-12 col-md-6 ps-3 ps-lg-5 mb-3">
                            <div class="image">
                                <img src="../../assets/img/cluster-deploy.svg" alt="">
                            </div>
                            <div class="title">
                                <span>Global availability</span>
                            </div>
                            <div class="text">
                                <p>
                                    Deploy to any of our data center regions
                                    around the world.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Deploy' 
}
</script>

<style lang="scss" scoped>

    section {
        color: #485d80;
        padding: 60px 0;
        
        h2 {
            color: #041d4e;
        }

        .content {
            margin-top: 60px;
        }

        ul {
            list-style: none;
            border-left: 2px solid #c9c9c9;
            padding: 1px 10px;

            li {
                margin: 13px 0;
            }
        }

        img {
            margin-bottom: 10px;
        }

        .title {
            color: #041d4e;
            font-weight: bold;
            margin-bottom: 5px;
        }
    }

</style>