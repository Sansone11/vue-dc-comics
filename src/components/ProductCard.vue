<template>
  <main>
    <div class="container">
        <article class="card">
            <img :src="thumb" :alt="serie">
            <h2>{{serie}}</h2>
        </article>
    </div>
  </main>
</template>

<script>

export default {
    props:{
        thumb: String,
        serie: String,
    },
 data(){
    
 }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .card{
        text-align: center;
        h2{
            color: white;
        }
    }


</style>
