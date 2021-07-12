<template>
    <div class="options-stripe">
        <nav>
            <ul>
                <li>
                    <div class="img-container"><img src="../assets/buy-comics-digital-comics.png" alt=""></div>
                    <div class="text">DIGITAL COMICS</div>
                </li>
                <li>
                    <div class="img-container"><img src="../assets/buy-comics-merchandise.png" alt=""></div>
                    <div class="text">DC MECHANDISE</div>
                </li>
                <li>
                    <div class="img-container"><img src="../assets/buy-comics-subscriptions.png" alt=""></div>
                    <div class="text">SUBSCRIPTION</div>
                </li>
                <li>
                    <div class="img-container"><img src="../assets/buy-comics-shop-locator.png" alt=""></div>
                    <div class="text">COSMIC SHOP LOCATOR</div>
                </li>
                <li>
                    <div class="img-container"><img src="../assets/buy-dc-power-visa.svg" alt=""></div>
                    <div class="text">DC POWER VISA</div>
                </li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    name: 'Stripes'
}
</script>

<style lang="scss" scoped>
    .options-stripe{
        background-color: dodgerblue;
        display: flex;
        justify-content: center;
        nav {
            ul {
                list-style: none;
                font-size: 14px;
                flex-grow: 1;
                display: flex;
                align-items: center;
                li {
                    height: 120px;
                    margin: 0 30px;
                    cursor: pointer;
                    color: white;
                    display: flex;
                    vertical-align: center;
                    .img-container{
                        height: 120px;
                    
                        img{
                            height: 50%;
                            margin-right: 20px;
                            margin-top: 24px;
                        }
                    }    
                    .text{
                        line-height: 120px;
                        vertical-align: middle;
                    }
                }
            }
        }
    }    
    
</style>