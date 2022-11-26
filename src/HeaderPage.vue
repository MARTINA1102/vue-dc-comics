<template>
  <div>
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
    <div class="container"><button class="current_btn">CURRENT SERIES</button></div>
  </div>

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
  .container{
    background-image: url('./img/jumbotron.jpg');
    height: 25rem;
    background-position: top;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
  }
  .current_btn{
    background-color: rgb(5,147,255);
    font-size: 1.5rem;
    padding: 0.5rem;
    color: white;
    border: 1px solid rgb(5, 147, 255);
    position:absolute;
    bottom:-1rem;
    left:10rem;
  }
</style>
