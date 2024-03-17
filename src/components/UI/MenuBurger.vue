<template>
<div class="Menu-burger">
    <div class="burger-button">
        <div class="line1 lines"></div>
        <div class="line2 lines"></div>
        <div class="line3 lines"></div>
    </div>
</div>

</template>

<script>

</script>

<style scoped lang="scss">
.burger-button {
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
@media (max-width: 900px) {
.burger-button {
    display: block;
    float: right;
}

}
</style>