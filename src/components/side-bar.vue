<template>
  <div>
      <div class="container">
<div class="side-bar">
      <div class="side-bar-content">
          <h1>side-bar</h1>
      </div>
  </div>
      </div>
  </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
.side-bar{
    display: flex;
    justify-content: center;
    position: absolute;
    right: 122px;
    top: 101px;
    height: 66vh;
    background: red;
    width: 312px;
    align-items: center;
    h1{
        color: white;
    }
}
</style>