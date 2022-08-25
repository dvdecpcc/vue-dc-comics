<template>
  <section id="jumbo">
    <div class="currentSeries">CURRENT SERIES</div>
  </section>
</template>

<script>
export default {
    name: 'MySection'
}
</script>

<style>
    #jumbo{
        background-image: url('@/assets/img/jumbotron.jpg');
        height: 300px;
        width: 100%;
    }
    .currentSeries{
            background-color: rgb(1, 130, 249);
            color: white;
            width: 150px;
            position: relative;
            left: 100px;
            bottom: -280px;
        }
</style>