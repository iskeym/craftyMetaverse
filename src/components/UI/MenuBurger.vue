<template>
<div class="Menu-burger">
    <div class="burger-button" @click="menu" v-if="menuToggle == false">
        <div class="line1 lines"></div>
        <div class="line2 lines"></div>
        <div class="line3 lines"></div>
    </div>
    <div class="menu" v-if="menuToggle == true">
        <img src="@/assets/Logo.png" alt="logo">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About us</a></li>
            <li><a href="#">White paper</a></li>
            <li><a href="#">Tokenomics</a></li>
            <li><a href="#">Road Map</a></li>
            <li><a href="#">How to buy</a></li>
            <li><a href="#">Buy</a></li>
        </ul>
    </div>
    <div class="cross" @click="menu" v-if="menuToggle == true"></div>
</div>

</template>

<script>
export default {
    data() {
        return {
            menuToggle: false
        }
    },
    methods: {
        menu() {
            this.menuToggle = !this.menuToggle
        }
    },
}
</script>

<style scoped lang="scss">
.cross:after {
    position: fixed;
    display: inline-block;
    content: "\00d7";
    font-size: 300%;
}
.menu {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: url('@/assets/Hero.png') no-repeat -350px 0;
    img {
        margin-top: 40px;
        margin-left: 20px;
    }
    ul {
        list-style-type: none;
        margin-left: 20px;
        margin-top: 50px;
        li {
            margin-bottom: 40px;
            a {
                color: #FFFFFF;
                text-decoration: none;
                font-family: "Plus Jakarta Sans", sans-serif;
                font-size: 150%;
                font-weight: 500;
                line-height: 28px;
                letter-spacing: 0em;
                text-align: left;
                white-space: nowrap;
            }
        } 
    }

}
.burger-button{
    display: none;
}
.lines {
    background-color: black;
    margin-left: auto; 
    margin-right: 2px;
}
.line1 {
    width: 32px;
    height: 2px;
}
.line2 {
    width: 19px;
    height: 2px;
    margin-top: 8px;
}
.line3 {
    width: 25px;
    height: 2px;
    margin-top: 8px;
}
@media (max-width: 1100px) {
.burger-button{
    display: block;
    float: right;
    cursor: pointer;
    margin-top: 40px;
    margin-right: 20px;
}
.cross {
    display: block;
    float: right;
    cursor: pointer;
    margin-top: 25px;
    margin-right: 50px;
    color: #FFFFFF;
} 
}
</style>