<template>
  <section class="upload">
    <h2>Convert your <span class="highlight">pdf</span> into an engaging experience.</h2>
    <div class="upload-box">
      <p>Drag & drop your files here</p>
      <p>or</p>
      <p>Paste URL to Course Material</p>
      <input type="file" />
    </div>
  </section>
</template>

<script>
export default {
  name: 'UploadSection'
}
</script>

<style scoped>
.upload {
  text-align: center;
  padding: 50px 20px;
}
.highlight {
  color: red;
}
.upload-box {
  border: 2px dashed #ccc;
  padding: 30px;
  margin-top: 20px;
  max-width: 500px;
  margin: 20px auto;
}
</style>