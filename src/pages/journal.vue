<template>
  <Layout>
    <div class="slot-container">
      <div class="container">
        <div class="journal-hero">
          <h1 class="journal-header">a wise person once said...</h1>
        </div>
      </div>
      <a href="" class="journal-post">
        <div class="container journal">
          <h2 class="journal-title">Gridsome with Forestry CMS</h2>
          <p class="journal-excerpt">
            Get up and running with Forestry CMS, a git-backed headless CMS with a slick
            editing interface.
          </p>
        </div>
      </a>
    </div>
  </Layout>
</template>

<script>
export default {
  name: "Journal",
};
</script>

<style scoped>
.journal-hero {
  padding: 4rem 0;
  text-align: center;
  color: #f3f3f3;
}
.journal-header {
  font-size: 3rem;
  font-weight: 700;
  padding: 0;
  margin: 0;
}
.journal-post {
  display: block;
  padding: 2rem 0;
  text-decoration: none;
  transition: background 0.5s ease;
}
.journal-post h1,
.journal-post h2 {
  margin: 0;
  padding: 0;
}
.container .journal {
  max-width: 720px;
}
.journal-excerpt {
  color: #2b2b2b;
}
.journal-title {
  font-size: 2rem;
  color: #2b2b2b;
}
</style>
