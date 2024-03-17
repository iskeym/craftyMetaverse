<template>
    <div class="craftyMetaverse">
        <TheNavbar/>
        <MenuBurger/>
    </div>
</template>

<script>
import TheNavbar from '@/components/UI/TheNavbar.vue'
import MenuBurger from '@/components/UI/MenuBurger.vue'

export default {
    components: {
        TheNavbar,
        MenuBurger
    }
}
</script>

<style scoped lang="scss">
.craftyMetaverse {
    min-height: 100%;
    background: url('@/assets/Hero.png') no-repeat center;
}
</style>