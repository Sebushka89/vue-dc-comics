<template>
  <div class="jumbo-pic">
      <div class="container">
            <div class="button-container">
                <button>CURRENT SERIES</button>
            </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Jumbotron',
}
</script>

<style lang="scss" scoped>

.jumbo-pic{
    background-image: url(../assets/jumbotron.jpg);
    height: 485px;
    .container{
            width: 1200px;
            margin: auto;
            .button-container{
                position: relative;
                top: 460px;
                button{
                    padding: 6px 14px;
                    color: white;
                    background-color: dodgerblue;
                    cursor: pointer;
                    margin: 12px 0;
                }
            }    
        }
}
    
</style>