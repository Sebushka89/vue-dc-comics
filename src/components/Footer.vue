<template>
    <div>
        <footer>
            <div class="container">
                <div class="lista">
                    <h2>DC COMICS</h2>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>
                    <h2>DC SHOP</h2>
                    <ul>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>
                </div>
                <div class="lista">
                    <h2>DC</h2>
                    <ul>
                        <li><a href="#">Terms of Use</a></li>
                        <li><a href="#">Privacy policy(New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates </a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>
                <div class="lista">
                    <h2>SITES</h2>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </div>
                <div class="logo-container">
                    <img src="../assets/dc-logo-bg.png">
                </div>
            </div>
        </footer>
        <div class="bottom">
            <div class="container">
                <div class="under-footer">
                    <button>Sign-up now!</button>
                    <div class="social">
                        <span><strong>Follow Us</strong></span>
                        <img src="../assets/footer-facebook.png" alt="">
                        <img src="../assets/footer-periscope.png" alt="">
                        <img src="../assets/footer-pinterest.png" alt="">
                        <img src="../assets/footer-twitter.png" alt="">
                        <img src="../assets/footer-youtube.png" alt="">
                    </div>
                </div> 
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>
footer{
    background-image: url(../assets/footer-bg.jpg);
    height: 495px;
    display: flex;
    background-size: cover;
    .container{
        width: 1200px;
        margin: auto;
        .lista{
            display: inline-block;
            padding-right: 20px;
            margin-top: 30px;
            vertical-align: top;
            ul{
                list-style: none;        
                li{
                    margin: 10px 0;
                    a {
                        color: grey;
                        text-decoration: none;
                        &:hover{
                            color: white;
                        } 
                    }
                }    
            }
        }
        .logo-container {
            display: inline-block;
            height: 500px;
            padding-left: 130px;
            overflow: hidden;
            width: 740px;
            img{
                height: 600px;
                margin-top: -50px;
            }
        }    
    }
}        

.bottom{
    background-color: #1C1C1C;
    .under-footer{
        padding: 40px; 
        display: flex;
        justify-content: space-between;
        img{
            margin-right: 20px;
        }
        span{
            color: #0282F9;
            vertical-align: super;
            margin-right: 10px;
            font-size: 20px;
            text-transform: uppercase;
        }
    }
}
button{
    border: 3px solid #0282F9;
    padding: 10px;
    background-color: #1C1C1C;
    color: white;
    cursor: pointer;
    &:hover{
        transform: scale(1.5);
    }
} 
h2{
    text-transform: uppercase;
    margin: 20px 0;
    color: white;
}
    
</style>