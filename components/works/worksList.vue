<template>
  <div id="works-list">
    <div class="d-flex align-center justify-center mb-15">
      <a
        class="mr-15"
        href="https://pipeline-hexaverse.herokuapp.com/"
        target="_blank"
        >HexaVerse</a
      >
      <a class="mr-15" href="https://yepas.com/" target="_blank">Yepaş</a>
      <a href="https://ahmetcalik.blackstudio.agency/" target="_blank"
        >Ahmet Çalık Vakfı</a
      >
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
#works-list {
  padding: 50px 0 100px 0;
  a {
    font-size: 35px;
    color: #d36b00 !important;
    transition: all 0.5s ease;
    @media screen and (max-width: 769px) {
          font-size: 20px !important;
      }
       @media screen and (max-width: 600px) {
          font-size: 14px !important;
      }
  }
}
</style>