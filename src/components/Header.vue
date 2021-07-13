<template>
    <div class="header-full container">
        <div class="logo-container">
            <img src="../assets/dc-logo.png" />
        </div>
        <nav>
            <ul>
                <li><a href="http://">CHARACTERS</a></li>
                <li><a href="http://">COMICS</a></li>
                <li><a href="http://">MOVIES</a></li>
                <li><a href="http://">TV</a></li>
                <li><a href="http://">GAMES</a></li>
                <li><a href="http://">COLLECTIBLES</a></li>
                <li><a href="http://">VIDEOS</a></li>
                <li><a href="http://">FANS</a></li>
                <li><a href="http://">NEWS</a></li>
                <li><a href="http://">SHOP</a></li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style lang="scss" scoped>
    
    .header-full {
        background-color: white;
        display: flex;
        justify-content: center;
        .logo-container {
            text-align: left;
            height: 100px;
            width: 40%;
            img{
                height: 90%;
                padding-top: 10px;
            }
        }
        nav {
            ul {
                display: flex;
                list-style: none;
                font-size: 14px;
                font-weight: bold;
                flex-grow: 1;
                align-items: center;
                li {
                    height: 100px;
                    line-height: 100px;
                    margin: 0 10px;
                    cursor: pointer;
                    &:hover {
                        border-bottom: 3px solid dodgerblue;
                    }
                    a {
                        color: #333;
                        text-decoration: none;
                        &:hover {
                            color: dodgerblue ;
                        } 
                    }
                }
            }
        }
    }
</style>