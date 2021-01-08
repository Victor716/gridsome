<template>
  <Layout>
    <div class="slot-container">
      <div class="hero">
        <h1 class="hero-title">Simplicity. Aesthetics. Value.</h1>
        <h2 class="hero-subtitle">
          Hi there, I'm an independent Digital Designer & Art Director focused on digital
          design for brands that like to have fun.
        </h2>
      </div>
      <div class="projects">
        <div class="project">
          <img alt="Banana" src="../../static/pic/banana.jpg" class="thumbnail g-image" />
          <h3 class="project-title">Banana</h3>
          <div class="categories">
            <span class="category">photography</span><span class="category">pink</span>
          </div>
        </div>
      </div>
      <div>
        <div class="latest-journals-heading">
          <span class="label">Latest and greatest</span>
        </div>
        <div class="latest-journals">
          <g-link class="journal" to="/">
            <h3 class="journal-title">Gridsome with Forestry CMS</h3>
          </g-link>
          <g-link class="journal" to="/">
            <h3 class="journal-title">VueJS for your next project</h3>
          </g-link>
          <g-link class="journal" to="/">
            <h3 class="journal-title">macOS development environment</h3>
          </g-link>
          <g-link class="journal" to="/">
            <h3 class="journal-title">About Typography</h3>
          </g-link>
        </div>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Hello, world!",
  },
};
</script>

<style>
a {
  text-decoration: none;
}
.home-links a {
  margin-right: 1rem;
}
body {
  font-family: -apple-system, system-ui, BlinkMacSystemFont, Segoe UI, Roboto,
    Helvetica Neue, Arial, sans-serif;
}

.slot-container {
  display: block;
  position: relative;
  margin-top: 100px;
}
.hero {
  text-align: center;
  width: 480px;
  max-width: 100%;
  margin: 0 auto;
  padding: 4rem 0 8rem;
}
.hero-title {
  font-size: 3rem;
  font-weight: 700;
  padding: 0;
  margin: 0 0 2rem;
}
.hero-subtitle {
  font-size: 1.15em;
  font-weight: 400;
  line-height: 1.68;
  opacity: 0.6;
}
.projects {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-gap: 4rem;
}
.project-link {
  text-decoration: none;
}
.thumb-nail {
  height: 560px;
  -o-object-fit: cover;
  object-fit: cover;
  transition: all 0.15s ease;
  box-shadow: 0 0 40px -20px rgba(0, 0, 0, 0.25);
}
.g-image {
  max-width: 100%;
}
.latest-journals-heading {
  margin-top: 6rem;
  margin-bottom: 1rem;
  font-size: 0.6rem;
  font-weight: 400;
  text-transform: uppercase;
}
.label {
  display: block;
  font-weight: 700;
  margin-bottom: 0.5rem;
}
.latest-journals {
  max-width: 100%;
  margin: 0 2rem;
  border: 1px solid #f3f3f3;
  display: flex;
}
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

@media (min-width: 860px) {
  .container {
    padding: 0 6rem;
  }
}
.journal {
  flex: 0 0 100%;
  display: block;
  padding: 2rem;
  transition: background 0.25s ease;
  text-decoration: none;
  border-bottom: 1px solid #f3f3f3;
}
.journal:hover {
  background: #f3f3f3;
}
.journal-title {
  font-size: 1rem;
  line-height: 1.35;
}
@media (min-width: 580px) {
  .journal {
    flex: 1;
  }
  .journal:first-child,
  .journal:nth-child(2) {
    border-bottom: 1px solid #f3f3f3;
  }
  .journal:first-child {
    border-right: 1px solid #f3f3f3;
  }
}
p {
  line-height: 1.5;
  font-size: 1.15rem;
}

</style>
