<template>
    <div class="box">
        <head-box></head-box>
        <menu-box></menu-box>
        <bo-box></bo-box>
    </div>
</template>

<script>
    import HeadBox from "../phone/components/header/Header.vue";
    import MenuBox from "../phone/components/main/menu.vue";
    import BoBox from "../phone/components/bottom/boBox.vue";

    export default {
        name: "home",
        components: {
            HeadBox,
            MenuBox,
            BoBox,
        }
    };
</script>

<style scoped lang="scss">

</style>