<template>
  <div class="product-card col-2 px-15">
    <div
      class="card-container"
      :style="{ backgroundImage: 'url(' + thumb + ')' }"
    ></div>
    <h4>{{ title }}</h4>
    <h5>{{ price }}</h5>
    <h6>{{ type }}</h6>
  </div>
</template>


<script>
export default {
    name: 'Card',
    props: {
    thumb: String,
    price: String,
    title: String,
    type: String,
  },
}
</script>

<style lang="scss" scoped>
    
</style>