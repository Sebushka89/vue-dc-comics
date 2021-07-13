<template>
    <div class="bg">
        <div class="container">
            <div class="row">
                <Card  v-for="(element, index) in comics"
                :key="index"
                :thumb="element.thumb"
                :price="element.price"
                :title="element.series"
                :type="element.type"
                />
            </div>
            <div class="button-container">
                <button>LOAD MORE</button>
            </div>
        </div>
    </div>
</template>

<script>
import Card from './Card.vue'
export default {
    name: 'Main',
    components: {
    Card,
  },
  props: {
    comics: Array,
  },
}
</script>

<style lang="scss" scoped>
    
    .bg {
        background-color: black;
        color: white;
        display: flex;
        justify-content: left;
        align-items: center;
        .container{
            width: 1200px;
            margin: auto;
            .button-container{
                text-align: center;
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