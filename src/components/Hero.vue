<template>
  <div>
    <div class="hero">
      <!-- desktop -->
      <div class="d-none d-md-block">
        <div class="row mt-4">
          <div class="col-md-6">
            <div class="d-flex h-100">
              <div class="justify-content-center align-self-center">
                <h2>
                  <strong>Delicius Food Menu</strong> <br />in your Gadged
                </h2>
                <p>Ayo makan dengan nikmat</p>
                <router-link to="/food" class="btn btn-lg btn-success"
                  ><b-icon-arrow-right></b-icon-arrow-right>Pesan</router-link
                >
              </div>
            </div>
          </div>
          <div class="col">
            <img src="/img/hero.png" class="w-100" alt="" />
          </div>
        </div>
      </div>

      <!-- mobile -->
      <div class="d-sm-block d-md-none">
        <div class="row mt-4 ">
          <div class="col">
            <img src="/img/hero.png" class="w-100" alt="" />
          </div>
          <div class="col-md-6 mt-5">
            <div class="d-flex h-100">
              <div class="justify-content-center align-self-center">
                <h2>
                  <strong>Delicius Food Menu</strong> <br />in your Gadged
                </h2>
                <p>Ayo makan dengan nikmat</p>
                <router-link to="" class="btn btn-lg btn-success"
                  ><b-icon-arrow-right></b-icon-arrow-right>Pesan</router-link
                >
              </div>
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

<style lang="scss" scoped></style>
