<template>
  <div class="hero">

    <!-- Desktop -->
    <div class="d-none d-md-block">
      <div class="row mt-4">
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Ayo Beli</strong> <br />
                Salad Sehat
              </h2>
              <p>Pilih Menu Salad Disini</p>
              <router-link class="btn btn-lg btn-success" to="/menu">
                <b-icon-arrow-right></b-icon-arrow-right> Order
              </router-link>
            </div>
          </div>
        </div>

        <div class="col-md-6">
          <img src="../assets/image/hero.png" width="100%" />
        </div>
      </div>
    </div>

    <!-- Mobile -->
    <div class="d-sm-block d-md-none">
      <div class="row mt-4 ">
        <div class="col-md-6">
          <img src="/assets/image/1.jpeg" width="100%" />
        </div>
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Ayo Beli</strong> <br />
                Salad Sehat
              </h2>
              <p>Pilih Menu Salad Disini</p>
              <button class="btn btn-lg btn-success">
                <b-icon-arrow-right></b-icon-arrow-right> Order
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style></style>
