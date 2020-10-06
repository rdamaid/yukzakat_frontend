<template>
  <div :style="jumbotron" class="jumbotron jumbotron-fluid jumbot">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-5 pt-4">
          <h1 class="py-2">YukZakat</h1>
          <nav aria-label="breadcrumb">
            <ol class="breadcrumb">
              <!-- <li class="breadcrumb-item bread-text"><a href="#">Home</a></li> -->
              <li class="breadcrumb-item active bread-text">
                Beranda
              </li>
            </ol>
          </nav>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Jumbotron",
  data() {
    return {
      jumbotron: {
        backgroundImage: `url(${require("@/assets/sites/img/bg.png")})`,
      },
    };
  },
};
</script>
