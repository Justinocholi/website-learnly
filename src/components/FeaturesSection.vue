<template>
  <section class="features">
    <div class="feature-box student">
      <h2>Students</h2>
      <p>Master complex topics faster with interactive, gamified lessons designed to boost retention and engagement.</p>
    </div>
    <div class="feature-box educator">
      <h2>Educators</h2>
      <p>Transform your content into dynamic, bite-sized learning experiences that keep students engaged and improve outcomes.</p>
    </div>
  </section>
</template>

<script>
export default {
  name: 'FeaturesSection'
}
</script>

<style scoped>
.features {
  display: flex;
  justify-content: center;
  gap: 20px;
  padding: 50px 20px;
}
.feature-box {
  padding: 30px;
  width: 40%;
  border-radius: 10px;
  color: white;
}
.student {
  background: #7a28cb;
}
.educator {
  background: #1e40af;
}
</style>