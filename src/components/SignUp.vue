<template>
  <div action="#" class="sign-up">
    <h2 class="title">Hello</h2>
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
  grid-column: 1 / 2;
  grid-row: 1 / 2;
}

.title {
  font-size: 2.2rem;
  color: #444;
  margin-bottom: 10px;
}

@media (max-width: 870px) {
  .btn.transparent {
    width: 110px;
    height: 35px;
    font-size: 0.7rem;
  }
}

@media (max-width: 570px) {
  div {
    padding: 0 1.5rem;
  }
}
</style>
