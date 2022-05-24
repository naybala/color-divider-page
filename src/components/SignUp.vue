<template>
  <div action="#" class="sign-up">
    <h2 class="title">Hello</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit hic, non impedit
      aspernatur assumenda sit quisquam veritatis magnam maxime nisi vitae soluta adipisci
      quibusdam? Ut nisi quo sed libero nobis.
    </p>
    <a href="#home"><button class="btn transparent">More About Us</button></a>
    <br />
    <i
      class="fa-solid fa-2xl fa-angles-down fa-bounce"
      style="--fa-bounce-start-scale-y: 1; --fa-animation-duration: 2s"
    ></i>
  </div>
</template>

<script></script>

<style scoped>
input {
  font-family: "Poppins", sans-serif;
}

div {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  padding: 0rem 5rem;
  transition: all 0.2s 0.7s;
  overflow: hidden;
  margin-top: 8rem;
  grid-column: 1 / 2;
  grid-row: 1 / 2;
}

.title {
  font-size: 2.2rem;
  color: #444;
  margin-bottom: 10px;
}

.btn {
  width: 150px;
  background-color: var(--first-color);
  border: none;
  outline: none;
  height: 49px;
  border-radius: 49px;
  color: #fff;
  text-transform: uppercase;
  font-weight: 600;
  margin: 10px 0;
  cursor: pointer;
  transition: 0.5s;
}

.btn.transparent {
  margin: 0;
  background: var(--first-color);
  border: none;
  /* width: 130px; */
  height: 41px;
  font-weight: 600;
  font-size: 0.8rem;
}
.btn.transparent:hover {
  transform: translateY(-3px);
  box-shadow: 3px 3px 10px black;
}

@media (max-width: 570px) {
  div {
    padding: 0 1.5rem;
  }
  .title {
    margin-top: 10rem;
  }
}
</style>
