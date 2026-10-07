<script setup>
</script>

<template>
  <div class="page">

    <header class="hero">
      <div class="container">
        <p class="about">About</p>
        <h1>Central Philippine University</h1>
        <h3>Scientia Et Fides</h3>
        <p class="lead">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto recusandae, nostrum cum maiores molestiae sed totam quam qui tempora placeat odio praesentium consequuntur enim nemo incidunt, voluptatum minus rerum ex!
        </p>
      </div>
    </header>

    <main class="container main">
      <section class="card">
        <h2>Our University</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit.
          Architecto recusandae, nostrum cum maiores molestiae sed totam
          quam qui tempora placeat odio praesentium consequuntur enim nemo
          incidunt, voluptatum minus rerum ex!
        </p>
      </section>
    </main>

  </div>
</template>

<style scoped>
* {
  box-sizing: border-box;
}

.page {
  min-height: 100vh;
  background-color: #f5f6fa;
  color: #444;
  font-family: Arial, Helvetica, sans-serif;
}

.container {
  max-width: 960px;
  margin: 0 auto;
  padding: 0 24px;
}

.hero {
  background: linear-gradient(135deg, #432080 0%, #c8a100 100%);
  color: #fff;
  padding: 50px 0;
}

.about {
  font-size: 13px;
  text-transform: uppercase;
  letter-spacing: 3px;
  color: #c8a100;
  margin: 0 0 8px;
  font-weight: 600;
}

.hero h1 {
  font-size: 32px;
  margin: 0 0 12px;
}

.lead {
  max-width: 640px;
  margin: 0;
  line-height: 1.6;
}

.main {
  padding: 40px 24px;
}

.card {
  background-color: #fff;
  border: 1px solid #eee0b8;
  border-radius: 12px;
  padding: 30px;
  box-shadow: 0 4px 12px rgba(43, 27, 94, 0.06);
}

.card h2 {
  font-size: 22px;
  margin: 0 0 16px;
  color: #2b1b5e;
}

.card p {
  margin: 0;
  font-size: 15px;
  line-height: 1.7;
  color: #555;
}
</style>