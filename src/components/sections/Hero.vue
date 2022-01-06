<template>
    <div class="hero">
        <div class="container">
            <div class="row">
                <div class="col-12 col-md-7 hero-left">
                    <h1>The simplest cloud platform for developers & teams</h1>
                    <p>Deploy,manage, and scale cloud applications faster and more efficiently on DigitalOcean. We make managing infrastructure easy for teams and business, whether you're running one virtual machine or ten thousand.</p>
                </div>
                <div class="col-12 col-md-4 offset-md-1 hero-right">
                    <h2>Deploy your app in seconds.</h2>
                    <h2>Get started now.</h2>
                    <form action="#">
                        <input type="email" placeholder="Email">
                        <input type="password" placeholder="Password">
                    </form>
                    <div class="buttons">
                        <button class="create">Create your account</button>
                        <button class="sign">
                            <img src="../../assets/img/google-icon.png" alt="google-logo">
                            Sign up with google
                        </button>
                    </div>
                    <p>By signing up you agree to the <a href="#">Terms of Service</a></p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Hero'
}
</script>

<style lang="scss" scoped>
@import '../../assets/global.scss';

    .hero {
        background-image: url('../../assets/img/bg-banner-home.jpg');
        background-size: cover;
        background-position: center;
        padding: 60px 0;

        .container {
            display: flex;

            .hero-left {

                h1 {
                    font-size: 60px;
                    color: white;
                } 

                p {
                    font-size: 20px;
                    color: #bccfff;
                }
            }

            .hero-right {
                background-color: #ffffff;
                border-radius: 5px;
                padding: 40px 20px;
                box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;

                h2 {
                    font-size: 30px;
                    text-align: center;

                    &:nth-of-type(2) {
                        color: $blue;
                    }
                }

                form {
                    padding-top: 10px;

                    input {
                        width: 100%;
                        display: block;
                        padding: 8px 5px;
                        border-radius: 5px;
                        border: 1px solid #f7f7f7;
                        margin-bottom: 10px;
                    } 
                }

                .buttons {
                    button {
                        font-size: 14px;
                        width: 100%;
                        display: block;
                        border-radius: 5px;
                        padding: 4px 0;
                        margin-bottom: 10px;
                        border: 1px solid transparent;

                        &.create {
                            color: white;
                            background-color: $blue;
                        }

                        &.sign {
                            background-color: #ffffff;
                            box-shadow: rgba(136, 165, 191, 0.48) 6px 2px 16px 0px, rgba(255, 255, 255, 0.8) -6px -2px 16px 0px;
                            position: relative;

                            img {
                                width: 20px;
                                position: absolute;
                                top: 50%;
                                bottom: 50%;
                                transform: translateY(-50%);
                                left: 10px;
                            }
                        }
                    }
                }

                p {
                    text-align: center;
                    font-size: 14px;
                }
            }
        }
    }

</style>