<template>
  <div class="page container">
    <div class="header">
      <div class="top-banner container">
        <div class="left">
          <g-link to="/"><img src="../../static/pic/logo.svg" alt="" /></g-link>
        </div>
        <nav class="nav right">
          <g-link to="/journal">Journal</g-link>
          <g-link to="/contact">Say Hi!</g-link>
        </nav>
      </div>
    </div>
    <slot />
    <div class="footer">
      <div class="container">
        <span>Copyright © 2019</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.header {
  background: transparent;
  height: 100px;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
}
.top-banner {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 100%;
  color: aliceblue;
}
.top-banner .left img {
  height: 1.5rem;
  width: 100%;
}
.nav a {
  font-size: 0.9rem;
  font-weight: 600;
  text-decoration: none;
  margin-top: 4px;
  margin-right: 3rem;
  padding-bottom: 4px;
  border-bottom: 1px solid;
  border-color: transparent;
  transition: border 0.15s;
}

.bottom-banner {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 100%;
  color: burlywood;
}
.footer {
  font-size: 0.8rem;
  padding: 6rem 0;
}
</style>
