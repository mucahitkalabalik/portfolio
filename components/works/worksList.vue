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
    color: rgba(0, 0, 0, 0.411) !important;
    text-shadow: 0px 24px 7px rgba(150, 150, 150, .3);
    transition: all .5s ease;
    &:hover{
       color: rgba(0, 0, 0, 0.811) !important;
        text-shadow: 0px 24px 7px rgba(150, 150, 150, 1);
    }
  }
}
</style>