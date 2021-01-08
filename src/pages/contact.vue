<template>
  <Layout>
    <div class="slot-container">
      <div class="container">
        <div class="contact-header">
          <h1 class="contact-title">Say hi!</h1>
          <p>
            Leave me a note with any questions you might have, I'll get back to you as
            soon as possible.
          </p>
        </div>
        <form action="" name="contact" class="contact-form">
          <div class="sender-info">
            <div>
              <label for="name" class="label">Your name</label>
              <input type="text" name="name" />
            </div>
            <div>
              <label for="email" class="label">Your email</label>
              <input type="text" name="email" />
            </div>
          </div>
          <div class="message">
            <label for="message" class="label">Message</label>
            <textarea type="text" name="message" />
          </div>
          <button class="button">Submit form</button>
        </form>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Contact",
  },
};
</script>
<style scoped>
.contact-header {
  padding: 2rem 0 4rem;
}
.contact-title {
  font-size: 4rem;
  margin: 0 0 4rem;
  padding: 0;
}
.sender-info {
  display: flex;
  flex-wrap: wrap;
  margin-bottom: 2rem;
}
.sender-info div {
  flex: 1;
  margin-right: 4rem;
}
.sender-info div:last-of-type {
  margin: 0;
}
.label {
  display: block;
  font-weight: 700;
  margin-bottom: 0.5rem;
}
input {
  background: transparent;
  border: 1px solid #f3f3f3;
  outline: none;
  border-radius: 0.3rem;
  padding: 0.8rem 1rem;
  color: inherit;
  font-size: 1rem;
  width: 100%;
}
textarea {
  background: transparent;
  border: 1px solid #f3f3f3;
  outline: none;
  border-radius: 0.3rem;
  padding: 0.8rem 1rem;
  color: inherit;
  font-size: 1rem;
  width: 100%;
  resize: none;
  height: 140px;
}
.button {
  color: #fff;
  background: #000;
  outline: none;
  border: 0;
  font-size: 0.8rem;
  padding: 0.8rem 1.6rem;
  border-radius: 0.3rem;
  margin-top: 2rem;
  cursor: pointer;
  transition: opacity 0.25s ease;
  font-size: 500;
  letter-spacing: 0.035em;
}
</style>
