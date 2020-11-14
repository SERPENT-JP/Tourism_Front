<template>
    <div>
        <Header />
        <div class="wrapper">
        <Nuxt />
        </div>
        <Footer />
    </div>
</template>

<script>
export default {
  data () {}
}
</script>
<style>
body {
  background-color: #EDF2F7 !important;
}
.wrapper {
  min-height: calc(100vh - 30vh - 70px);
}
</style>