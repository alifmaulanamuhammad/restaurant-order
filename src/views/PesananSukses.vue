<template>
  <div class="pesanan-baru">
    <Navbar />
    <div class="container">
      <div class="row justify-content-center mt-5">
        <div class="col text-center">
          <img src="/assets/images/waiting.svg" alt="" width="300" />
          <br />
          <h2>Sukses</h2>
          <h4>Pesanan Anda sedang di proses</h4>
          <strong>Mohon bersabar</strong>
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

<style></style>
