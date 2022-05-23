<template>
  <div action="#" class="sign-in">
    <h2 class="title">Welcome</h2>
  </div>
</template>

<script></script>

<style scoped>
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

@media (max-width: 570px) {
  div {
    padding: 0 1.5rem;
  }
  .title {
    margin-bottom: 10rem;
  }
}
</style>
