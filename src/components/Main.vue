<template>
    <div class="bg">
        <div class="container">
            --> Content Goes here 
        </div>
    </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style lang="scss" scoped>
    
    .bg {
        background-color: black;
        color: white;
        height: 100px;
        display: flex;
        justify-content: left;
        align-items: center;
        .container{
            width: 1200px;
            margin: auto;
        }
    }
</style>