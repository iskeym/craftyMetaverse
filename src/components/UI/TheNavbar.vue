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
@import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:ital,wght@0,200..800;1,200..800&display=swap');

img {
    position: absolute;
    margin-left: 7.5%;
    margin-top: 41px;
}
ul {
    display: flex;
    justify-content: right;
    margin-right: 7%;
    list-style-type: none;
    li {
        display: inline-flex;
        a {
            color: #FFFFFF;
            text-decoration: none;
            margin-left: 45px;
            margin-top: 46px;
            font-family: "Plus Jakarta Sans", sans-serif;
            font-size: 20px;
            font-weight: 500;
            line-height: 28px;
            letter-spacing: 0em;
            text-align: left;
            white-space: nowrap;

        }
}  
}
@media (max-width: 1100px) {
    .navbar {
        display: none;
    }
}

</style>