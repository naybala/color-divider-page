<template>
  <div class="home">
    <div class="home1">
      <div class="home2">
        <section id="home">
          <div class="bgimages">
            <div class="heroText">
              <h1 class="text-white mb-lg-5">Home Section</h1>
            </div>
          </div>
          <br /><br /><br /><br />
        </section>
      </div>
      <br /><br />
    </div>
    <br /><br />
  </div>
</template>

<script></script>
<style scoped>
.home {
  background-color: aqua;
}
.home1 {
  background-color: blueviolet;
}
.home2 {
  background-color: brown;
}
/* bg with image  */
.bgimages {
  width: 100%;
  height: 420px;
  background: url("../../src/assets/images/artwork.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  background-attachment: fixed;
}

.heroText {
  position: absolute;
  z-index: 9;
  top: 120%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: auto;
}
</style>
