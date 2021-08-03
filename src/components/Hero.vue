<template>
  <div class="hero">
    <div class="d-none d-md-block">
      <div class="row mt-4">
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Foods Recomended, <br /></strong> in our place
              </h2>
              <router-link class="btn btn-success" to="/foods">
                <b-icon-arrow-right></b-icon-arrow-right>Pesan</router-link
              >
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <img src="../assets/images/hero.svg" alt="" width="100%" />
        </div>
      </div>
    </div>

    <div class="d-sm-block d-md-none">
      <div class="row-mt-4">
        <div class="col-md-6 mb-2">
          <img src="../assets/images/hero.svg" alt="" width="100%" />
        </div>
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Foods Recomended, <br /></strong> in our place
              </h2>
              <button class="btn btn-success">
                <b-icon-arrow-right></b-icon-arrow-right>Pesan
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
