<template>
  <div class="home">
    <section id="home">
      <br />
      <br />
      <div class="bgimages">
        <div class="heroText">
          <h1 class="text-white mb-lg-5">Home Section</h1>
        </div>
      </div>
      <br />
      <div class="text-center container-fluid col-9">
        <div class="card border-0 shadow">
          <div class="card-body">
            <h3>Heading</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit. Vel distinctio
              eaque perferendis. Doloribus, deserunt. Inventore quia quos ad laboriosam
              ratione commodi a atque accusamus magni quidem, sit cum asperiores pariatur?
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam
              exercitationem possimus delectus magni eveniet. Ullam exercitationem dolore
              recusandae obcaecati nesciunt iste, quas iure eligendi! Provident facilis
              quam libero fugiat aut.
            </p>
          </div>
        </div>
      </div>
      <br /><br />
      <div class="container-fluid col-9 d-flex">
        <div class="row">
          <div class="col-md-6">
            <div class="card border-0 shadow">
              <div class="card-body">
                <span class="text-muted fst-italic">Quality & Style</span>
                <h2>MARKET FORMULA</h2>
                <p class="text-muted">
                  These types of formula are for general construction and individual
                  customers. It came in two different classes, Which are
                  CII42.5,CI52.5(or) CI52.5. These Cement formulas provide high
                  compressive strength and significantly increase in drying shrinkage;
                  therefore it is an ideal solution for today’s schedule and budget driven
                  projects.
                </p>
              </div>
            </div>
            <br />
            <div class="card border-0 shadow">
              <div class="card-body">
                <span class="text-muted fst-italic">Feature & Aggresive</span>
                <h2>Our Content Includes</h2>
                <p class="text-muted">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis
                  odit eaque aut tempore temporibus provident nulla quibusdam perspiciatis
                  quisquam nostrum! Culpa magnam eius possimus unde iste excepturi laborum
                  quidem neque!
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <br />
            <img
              class="img-fluid rounded"
              src="../assets/images/digital-art.jpg"
              alt=""
            />
          </div>
        </div>
      </div>
      <br />
      <br />
      <div class="text-center container-fluid col-9">
        <div class="card border-0 shadow">
          <div class="card-body">
            <h3>Heading</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit. Vel distinctio
              eaque perferendis. Doloribus, deserunt. Inventore quia quos ad laboriosam
              ratione commodi a atque accusamus magni quidem, sit cum asperiores pariatur?
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam
              exercitationem possimus delectus magni eveniet. Ullam exercitationem dolore
              recusandae obcaecati nesciunt iste, quas iure eligendi! Provident facilis
              quam libero fugiat aut.
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script></script>
<style scoped>
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
