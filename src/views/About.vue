<template>
  <div>
      <div class="container">
    <div class="content-block">
<h1>new text</h1>
    </div>
</div>
    <router-view />
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style lang="scss">
.content-block{
    background: rgb(168, 29, 29);
    display: flex;
    justify-content: center;
    align-items: center;
    width: 70%;
    height: 66vh;
    h1{
      color:white;
    }
}
</style>
