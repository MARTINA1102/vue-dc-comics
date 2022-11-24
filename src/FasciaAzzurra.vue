<template>
  <div>
    <div class="black_cont"> Content goes here </div>
    <ul class="azure_cont">
      <li><img class="img" src="./img/buy-comics-digital-comics.png" alt=""> DIGITAL COMICS</li>
      <li><img class="img" src="./img/buy-comics-merchandise.png" alt=""> DC MERCHANDISE</li>
      <li><img class="img" src="./img/buy-comics-subscriptions.png" alt=""> SUBSCRIPTION</li>
      <li><img class="img" src="./img/buy-comics-shop-locator.png" alt="">COMIC SHOP LOCATOR</li>
      <li><img class="img" src="./img/buy-dc-power-visa.svg" alt="">DC POWER VISA</li>
    </ul>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  .black_cont{
    background-color: black;
    height: 5rem;
    color: white;
    padding: 2rem 1rem;
  }
  .azure_cont{
    background-color: rgb(5, 147, 255);
    list-style: none;
    height: 5rem;
    display: flex;
    justify-content: space-around;
    align-items: center;
    gap: 1rem;
    margin: 0;
    padding: 2rem 1rem;
  }
  li{
    display: flex;
    flex-direction: row;
    align-items: center;
    align-content: space-between;
  }
  .img{
    height: 50px;
  }

</style>
