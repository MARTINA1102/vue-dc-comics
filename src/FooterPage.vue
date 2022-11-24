<template>
  <footer>
    <button>SIGN-UP NOW!</button>
    <ul>
      <li>FOLLOW US</li>
      <li><img src="./img/footer-facebook.png" alt=""></li>
      <li><img src="./img/footer-twitter.png" alt=""></li>
      <li><img src="./img/footer-youtube.png" alt=""></li>
      <li><img src="./img/footer-pinterest.png" alt=""></li>
      <li><img src="./img/footer-periscope.png" alt=""></li>
    </ul>

  </footer>
</template>

<script>
export default {

};
</script>

<style leng="scss" scoped>
  footer{
    background-color: rgb(31, 30, 30);
    color: white;
    display: flex;
    justify-content: space-around;
    height: 4rem;
  }
  button{
    color: white;
    border: 1px solid rgb(5,147,255);
    background-color: rgb(31, 30, 30);
    margin: .5rem;
  }
  ul{
    list-style: none;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 1rem;
  }
  li{
    color: rgb(5,147,255);
  }
</style>
