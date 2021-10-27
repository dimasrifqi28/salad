<template>
  <div class="pesanan-sukses">
    <Navbar />
<div class="container">
    <div class="row justify-content-center mt-5">
        <div class="col text-center">
            <img src="/assets/image/tunggu.png" width="800" />
            <h2><strong>Sukses!!</strong></h2>
            <h4>Pesanan Anda Segera Diproses <br> Silahkan Menunggu </h4>
        </div>
    </div>
    </div>
    </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
export default {
  name: "PesananSukses",
  components: {
    Navbar,
  },
};
</script>

<style>
</style>