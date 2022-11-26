<template>
  <div class="card">
    <div class="contents">
      <img
        :src="folder.thumb"
        :alt="folder.titolo"
      >
      <h2> {{folder.series}} </h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CardPage',
  props: {
    folder: Object,
  },
};
</script>

<style lang="scss" scoped>
  .card {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  img {
    width: 130px;
    height: 130px;

  }
  .contents {
    background-color: black;
    padding: .5em;
    width: 200px;
    color: white;
  }
  h2 {
   font-size: 12px;
  }
</style>
