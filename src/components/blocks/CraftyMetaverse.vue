<template>
    <div class="craftyMetaverse">
        <TheNavbar/>
        <div class="content">
            <div class="lines">
                <div class="lines__line"></div>
                <div class="lines__small_lines">
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                    <div class="lines__small_lines__line2"></div>
                </div>
            </div>

            <div class="text">

            </div> 
        </div>
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
    background-image: url('@/assets/Hero.png');
    background-size: cover;
    background-position: center;
    min-height: 300px;
    width: 100%;
    padding-bottom: 275px;
    .lines {
        margin-top: 200px;
        margin-left: 4.5%;
        display: flex;
        &__line {
            height: 475px;
            width: 6px;
            background: #7F5CFF;
            border-radius: 41px;
            position: absolute;
        }
        &__small_lines {
            &__line2 {
                height: 1px;
                width: 100vh;
                margin-bottom: 17px;
                background: rgb(160,52,217);
                background: linear-gradient(90deg, rgba(160,52,217,0.19931722689075626) 74%, rgba(255,255,255,0) 100%);
            }
        }
    }

} 
</style>