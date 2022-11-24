<template>
  <header>
    <img src="./img/dc-logo.png" alt="">
    <ul class="nav_list">
      <li>CHARACTERS</li>
      <li>COMICS</li>
      <li>MOVIES</li>
      <li>TV</li>
      <li>GAMES</li>
      <li>COLLECTIBLES</li>
      <li>VIDEOS</li>
      <li>FANS</li>
      <li>NEWS</li>
      <li>SHOP</li>
    </ul>

  </header>
</template>

<script>
export default {

};
</script>

<style lang="scss" scooped>
  header{
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 8rem;
    padding: .5rem;
  }
  .nav_list{
    display: flex;
    list-style: none;
    gap: 1rem;

  }
</style>
