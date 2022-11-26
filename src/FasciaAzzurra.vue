<template>
  <div class="fasciazz">
    <div class="img-bg"></div>
    <div class= "black_cont">
      <CardPage
      v-for= "objDc in arrDc"
      :key= objDc.titolo
      :folder= "objDc"
      class= "card-dc"
      />
    <div class="botton_load"><button>LOAD MORE</button></div>
    </div>
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
import CardPage from './components/CardPage.vue';

export default {
  name: 'FasciaAzzurra',
  components: {
    CardPage,
  },
  data() {
    return {
      arrDc: [
        {
          thumb:
          'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX',
          price: '$19.99',
          series: 'Action Comics',
          type: 'comic book',
        },
        {
          thumb:
          'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01',
          price: '$3.99',
          series: 'American Vampire 1976',
          type: 'comic book',
        },
        {
          thumb:
          'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb',
          price: '$16.99',
          series: 'Aquaman',
          type: 'graphic novel',
        },
        {
          thumb:
          'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76',
          price: '$2.99',
          series: 'Batgirl',
          type: 'comic book',
        },
        {
          thumb:
          'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ',
          price: '$3.99',
          series: 'Batman',
          type: 'comic book',
        },
        {
          thumb:
          'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ',
          price: '$2.99',
          series: 'Batman Beyond',
          type: 'comic book',
        },
        {
          thumb:
          'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8',
          price: '$3.99',
          series: 'Batman/Superman',
          type: 'comic book',
        },
        {
          thumb:
          'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk',
          price: '$4.99',
          series: 'Batman/Superman Annual',
          type: 'comic book',
        },
        {
          thumb:
          'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8',
          price: '$5.99',
          series: 'Batman: The Joker War Zone',
          type: 'comic book',
        },
        {
          thumb:
          'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY',
          price: '$6.99',
          series: 'Batman: Three Jokers',
          type: 'comic book',
        },
        {
          thumb:
          'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX',
          price: '$4.99',
          series: 'Batman: White Knight Presents: Harley Quinn',
          type: 'comic book',
        },
        {
          thumb:
          'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLD',
          price: '$16.99',
          series: 'Catwoman',
          type: 'graphic novel',
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
  .img-bg{
    background-image: url('./img/jumbotron.jpg');
  }
  .fasciazz{
    background-color: black;
  }
  .black_cont{
    background-color: black;
    max-width: 1300px;
    height: 70vh;
    color: white;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    margin: 0 auto;
    .card-dc {
      flex: 0 0 5%;
    }
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
  .botton_load{
    max-width: 300px;
    margin: 0 auto;
  }
  button{
    background-color: rgb(5,147,255);
    align-self: center;
    padding: 0.5rem;
    color: white;
    border: 1px solid rgb(5, 147, 255);
  }

</style>
