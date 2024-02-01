<template>
  <section class="row justify-content-center">
    <div class="col-12 text-center fs-1 py-5"> Web Developer </div>
  </section>

  <section class="row justify-content-center pb-5">
    <div class="col-12 text-center fs-1 pb-5"> Links </div>
    <div class="col-6 d-flex justify-content-between">
      <a href="https://github.com/DavidLiamB" class="mdi mdi-github fs-1" target="_blank"></a>
      <a href="https://github.com/DavidLiamB" class="mdi mdi-linkedin fs-1"></a>
      <a href="https://github.com/DavidLiamB" class="mdi mdi-file-document fs-1"></a>
    </div>
  </section>

  <section class="row justify-content-center">
    <div class="col-12 text-center fs-1 pb-5"> Projects </div>
  </section>

  <section class="row justify-content-center">
    <div class="col-12 text-center fs-1 pb-5"> Education </div>
    <div></div>
    <p></p>
  </section>

  <section class="row justify-content-center">
    <div class="col-4 text-center fs-1 pb-5"> About </div>
  </section>
</template>

<script>
export default {
  setup() {
    return {

    }
  }
}
</script>

<style scoped lang="scss">
.home {
  display: grid;
  height: 80vh;
  place-content: center;
  text-align: center;
  user-select: none;

  .home-card {
    width: clamp(500px, 50vw, 100%);

    >img {
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
</style>
