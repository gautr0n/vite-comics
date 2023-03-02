<script>
</script>

<template>
    <div class="shop-list">
        <div class="card"><img src="../assets/buy-comics-digital-comics.png" alt="">DIGITAL COMICS</div>
        <div class="card"><img src="../assets/buy-comics-merchandise.png" alt="">DC MERCHANDISE</div>
        <div class="card"><img src="../assets/buy-comics-subscriptions.png" alt="">SUBSCRIPTION</div>
        <div class="card"><img src="../assets/buy-comics-shop-locator.png" alt="">COMIC SHOP LOCATOR</div>
        <div class="card"><img src="../assets/buy-dc-power-visa.svg" alt="">DC POWER VISA</div>
    </div>
    <div class="nav-bar">
        <div class="link-list">
            <div class="link-box">
                <div>DC COMICS</div>
                <ul>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                </ul>
                <div>DC COMICS</div>
                <ul>
                    <li>Characters</li>
                    <li>Characters</li>
                </ul>
            </div>
            <div class="link-box">
                <div>DC COMICS</div>
                <ul>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                </ul>
            </div>
            <div class="link-box">
                <div>DC COMICS</div>
                <ul>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                </ul>
            </div>
        </div>
        <img src="../assets/dc-logo-bg.png" alt="">
    </div>
    <div class="social-list">
        <div class="button"> SIGN-UP NOW</div>
        <div class="social-link">
            <div>FOLLOW US</div>
            <img src="../assets/footer-facebook.png" alt="">
            <img src="../assets/footer-twitter.png" alt="">
            <img src="../assets/footer-youtube.png" alt="">
            <img src="../assets/footer-pinterest.png" alt="">
            <img src="../assets/footer-periscope.png" alt="">
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .shop-list{
        background-color: #0282F9;
        padding: 10px 220px;
        display: flex;
        .card{
            color: white;
            text-align: center;
            display: flex;
            align-items: center;
            font-size: 10px;
            width: 20%;
            img{
                height: 25%;
                margin-right: 15px;
                margin-left: 15px;
            }
        }
    }
    .nav-bar{
        background-image: url(../assets/footer-bg.jpg);
        padding: 10px 220px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 300px;
        overflow: hidden;
        img{
            height: 130%;
        }
        .link-list{
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            div{

                div{
                    color: white;
                    padding: 10px 10px 10px 0;
                }
                ul{
                    padding: 0;
                    margin: 0;
                    li{
                        list-style: none;
                        color: #8b8d8b;
                    }
                }
            }             
        }
 
    }
    .social-list{
        background-color: #303030;
        padding: 10px 220px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        .button{
            color: white;
            background-color: #303030;
            border: 3px solid #0876DC;
            padding: 5px 10px;
        }
        .social-link{
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: #0876DC;
            width: 50%;
        }
    }

</style>