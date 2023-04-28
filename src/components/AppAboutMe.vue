<script>
    export default {
        name: "AppAboutMe"
    }
</script>

<template>
    <section>
        <div class="container">
            <h6 class="title">ABOUT ME</h6>
        </div>
    
        <div class="container">
            <div class="row">
                <h2>How To Be an Alpha <br> Male: The 15 Habits of <br> True Alphas</h2>
            </div>
            <div class="row">
                <h6><strong> Want to learn how to be <span>an aplha male?</span> How to be more masculine? How to be the man you've always wanted to be?</strong></h6>
                <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe blanditiis sed libero provident eveniet tempore sequi. Nam doloremque rem ipsum tempore ipsam aliquam ad, cumque repellendus quaerat. Repellendus, libero adipisci?</p>
            </div>
        </div>        
    </section>

    <section>
        <div class="container">
            <div class="row-left row">    
                <a class="youtube" href=""><img src="../assets/images/icon-youtube-play.png" alt=""></a>
            </div>
            <div class="row-right row">
                <p class="dreams">"Every morning you have two choises: continue to sleep with your dreams, or wake up and chase them."</p>
                <img class="logo" src="../assets/images//home-movation-shape-01.png" alt="">
                <p class="kaixa"><strong>Kaixa Stark</strong></p>
                <p class="win">WIN<span class="G">G</span>MAN</p>
            </div>
        </div>    
    </section>

</template>

<style lang="scss" scoped>

    .title {
        max-width: 1100px;
        margin-top: 100px;
        color: #20ac97;
    }
    .container {
        padding: 0;
        display: flex;
        max-width: 1100px;
        .row {
            display: block;
            width: 50%;
            margin-top: 20px;
        }

        .row-left {
            margin-top: 50px;
            width: 60%;
            height: 400px;
            margin-right: 40px;
            border-radius: 10px;
            background-image: url(../assets/images/home-movation-video-poster-670x450.jpg);
            .youtube {
                position: relative;
                left: 40%;
                top: 40%;
            }
        }

        .row-right {
            width: 40%;
            margin-left: 20px;
            margin-top: 50px;
            display: flex;
            vertical-align: middle;
            align-items: center;
            align-content: center;  
            
            .dreams{
                line-height: 3rem;
                font-size: 1.7rem;
            }

            .logo {
                width: 12%;
                margin-top: 30px;
                margin-bottom: 20px;
            }

            .kaixa {
                font-size: 1.4rem;
            }

            .win {
                font-size: 0.8rem;
                letter-spacing: 2px;
                color: gray;

                .G {
                    color: gray;
                    font-size: 1rem;
                }
            }
        }
    }

    .text {
        margin-top: 10px;
        font-size: 0.9rem;
    }
    span {
        color: #20ac97;
    }

</style>