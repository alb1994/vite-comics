<script>
import array_dc from '../dc-comics.js'
export default {
    data() {
        return {
            serie: array_dc
        }
    },
}
</script>
<template>
    <!--img jumbotron-->
    <div>
        <img class="jumbo" src="../img/jumbotron.jpg" alt="">
    </div>
    <!-- inizio sezione card-->
    <div class="container">
        <div class="flex wrap">
            <div class="card" v-for="(item, index) in serie" :key="index">
                <img :src="item.thumb" :alt="item.series" class="img">
                <h3>{{ item.series }}</h3>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.card {
    padding: 10px;
    margin: 10px;
    width: calc(100% / 6 - 20px);
    height: 300px;
}

.img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.jumbo {
    width: 100%;
    height: 400px;
}
</style>