<template>
  <div class="gift">
    <div class="gift-tie-1"></div>
    <div class="gift-tie-2"></div>
    <div class="gift-top"></div>
    <div class="gift-body"></div>
  </div>
</template>

<script>
export default {
    name:'Gift'
}
</script>

<style>
.gift {
    position: relative;
    display: flex;
    flex-direction: column;
    align-items: center;
    z-index: 10;
}

.gift-top {
    width: 100px;
    height: 25px;
    background-color: rgb(100, 6, 6);
}
.gift-body {
    width: 90px;
    height: 60px;
    background-color:rgb(53, 3, 3) ;
}
.gift-tie-1 {
    position: absolute;
    width: 15px;
    height: 85px;
    background-color: green;
}
.gift-tie-2 {
    position: absolute;
    top: 40px;
    width: 90px;
    height: 15px;
    background-color: green;
}
</style>