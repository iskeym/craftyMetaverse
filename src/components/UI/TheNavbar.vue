<template>
    <div class="navbar">
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
</template>

<script>

</script>

<style scoped lang="scss">
img {
    position: absolute;
    margin-left: 7.5%;
    margin-top: 41px;
}
ul {
    display: flex;
    justify-content: right;
    margin-right: 7%;
    li {
        display: inline-flex;
        a {
            color: #FFFFFF;
            text-decoration: none;
            margin-left: 45px;
            margin-top: 46px;
        }
}  
}
@media (max-width: 900px) {
    .navbar {
        display: none;
    }
}

</style>