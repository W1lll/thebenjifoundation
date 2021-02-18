<template>
  <div class="container">
    <Header />
    <div>
      <Logo />
      <h1 class="title text-4xl">
        The <span class="font-medium">Benji</span> Foundation
      </h1>
      <div class="links">
        <p>Helping children currently suffering with Vitamin D deficiency.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  user-select: none;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  color: #35495e;
  opacity: 0;
  animation: 2s appear linear 1s forwards;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
  opacity: 0;
  animation: 2s appear linear 2s forwards;
}
</style>
