<template>
  <footer>
    <section class="footerTop">
        <div class="topFooterContainer">
            <div class="topFooterMenu">
                <h3>DC COMICS</h3>
                <ul>
                    <li><a href="#">CHARACTERS</a></li>
                    <li><a href="#">COMICS</a></li>
                    <li><a href="#">MOVIES</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">GAMES</a></li>
                    <li><a href="#">VIDEOS</a></li>
                    <li><a href="#">NEWS</a></li>
                </ul>
                <h3>SHOP</h3>
                <ul>
                    <li><a href="#">SHOP DC</a></li>
                    <li><a href="#">SHOP DC COLLECTIBLES</a></li>
                </ul>
                <h3>DC</h3>
                <ul>
                    <li><a href="#">TERMS OF USE</a></li>
                    <li><a href="#">PRIVACY POLICY</a></li>
                    <li><a href="#">AD CHOICES</a></li>
                    <li><a href="#">ADVERTISING</a></li>
                    <li><a href="#">JOBS</a></li>
                    <li><a href="#">SUBSCRIPTIONS</a></li>
                    <li><a href="#">TALENT WORKSHOPS</a>
                    <li><a href="#">CPSC CERTIFICATES</a>
                    <li><a href="#">RATINGS</a>
                    <li><a href="#">SHOP HELPS</a>
                    <li><a href="#">CONTACT US</a>
                </ul>
                 <h3>SITES</h3>
                <ul>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD MAGAZINE</a></li>
                    <li><a href="#">DC KIDS</a></li>
                    <li><a href="#">DC UNIVERSE</a></li>
                    <li><a href="#">DC POWER VISA</a></li>
                </ul>
            </div>
        </div>
        <div class="bgLogo">
            <img src="../assets/img/dc-logo-bg.png" alt="dc logo">
        </div>
        <div class="footerBottom">
            <div class="bottomFooterContainer">
                <button>SIGN UP NOW</button>
                <ul>
                    <li><a href="#"><img src="../assets/img/footer-facebook.png" alt="fb logo"></a></li>
                    <li><a href="#"><img src="../assets/img/footer-twitter.png" alt="tw logo"></a></li>
                    <li><a href="#"><img src="../assets/img/footer-youtube.png" alt="yt logo"></a></li>
                    <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt="pi logo"></a></li>
                    <li><a href="#"><img src="../assets/img/footer-periscope.png" alt="per logo"></a></li>
                </ul>
            </div>
        </div>
    </section>
  </footer>
</template>

<script>
export default {
    name: 'MyFooter'
}
</script>

<style lang="scss">
    footer{
        color: white;
        .footerTop{
            background-image: url('../assets/img/footer-bg.jpg');
            .topFooterContainer{
                margin: auto;
                width: 80%;
                height: 360px;
                display: flex;
                justify-content: space-between;

                .topFooterMenu{
                    display: flex;
                    li{
                        list-style: none;
                        color: lightgray;
                    }
                }
                .bgLogo{overflow: hidden;}
            }
        }
        .footerBottom{
            background-color: rgb(48, 48, 48);
            .bottomFooterContainer{
                display: flex;
                justify-content: space-between;
                margin: auto;
                width: 80%;
                padding: 20px;
                button{
                    border: .5px solid white;
                    background-color: rgb(48, 48, 48);
                    padding: 10px;
                    color: white;
                }
                ul{
                    display: flex;
                    align-items: center;
                }
                ul li {
                    padding: 0px 8px;
                    display: inline-block;
                }
            }
        }
    }
</style>