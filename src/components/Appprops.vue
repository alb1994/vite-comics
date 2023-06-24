<script>
export default {
    props: {
        image: String,
        series: String
    }
}
</script>
<template lang="">
    <div class="card">
      <img :src="image">
      <h3>{{ series }}</h3>
    </div>
</template>
<style lang="">
    
</style>