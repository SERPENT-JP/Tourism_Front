<template>
    <div class="header">
        <nuxt-link to="/"
            ><img class="logo" src="~/assets/serpent-new.png"
        /></nuxt-link>
        <div class="page-title">
            SERPENT BLOG
        </div>
    </div>
</template>

<script>
export default {
    data() {},
};
</script>

<style scoped>
.header {
    padding: 0 20%;
    height: 70px;
    display: flex;
    justify-content: space-between;
    background-color: white;
    border-bottom: 5px orange solid;
}
.logo {
    height: 60px;
    margin: 5px;
    background-color: inherit;
}
.page-title {
    font-family: "Henny Penny", cursive;
    height: min-content;
    top: 0;
    bottom: 0;
    margin: auto 0;
    font-size: 40px;
    font-weight: bold;
    background-color: inherit;
}
</style>