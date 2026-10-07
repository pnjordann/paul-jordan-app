<script setup>
</script>

<template>
  <div class="page">

    <header class="hero">
      <div class="container">
        <p class="academics">Academics</p>
        <h1>Central Philippine University</h1>
        <h3>Scientia Et Fides</h3>
        <p class="lead">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto recusandae, nostrum cum maiores molestiae sed totam quam qui tempora placeat odio praesentium consequuntur enim nemo incidunt, voluptatum minus rerum ex!
        </p>
      </div>
    </header>

    <main class="container main">

      <section class="card">
        <h2>Academic Programs</h2>

        <div class="programs">
          <div class="program">
            <h3>College of Arts and Sciences</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto recusandae, nostrum cum maiores molestiae sed totam quam qui tempora placeat odio praesentium consequuntur enim nemo incidunt, voluptatum minus rerum ex!</p>
          </div>

          <div class="program">
            <h3>College of Computer Studies</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto recusandae, nostrum cum maiores molestiae sed totam quam qui tempora placeat odio praesentium consequuntur enim nemo incidunt, voluptatum minus rerum ex!</p>
          </div>

          <div class="program">
            <h3>College of Business</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto recusandae, nostrum cum maiores molestiae sed totam quam qui tempora placeat odio praesentium consequuntur enim nemo incidunt, voluptatum minus rerum ex!</p>
          </div>

          <div class="program">
            <h3>College of Education</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto recusandae, nostrum cum maiores molestiae sed totam quam qui tempora placeat odio praesentium consequuntur enim nemo incidunt, voluptatum minus rerum ex!</p>
          </div>
        </div>
      </section>

      <section class="card">
        <h2>Academic Information</h2>
        <ul>
          <li>Lorem ipsum dolor sit amet</li>
          <li>Lorem ipsum dolor sit amet</li>
          <li>Lorem ipsum dolor sit amet</li>
          <li>Lorem ipsum dolor sit amet</li>
        </ul>
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

.academics {
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
  display: flex;
  flex-direction: column;
  gap: 24px;
}

.card {
  background-color: #fff;
  border: 1px solid #eee0b8;
  border-radius: 12px;
  padding: 24px;
  box-shadow: 0 4px 12px rgba(43, 27, 94, .06);
}

.card h2 {
  font-size: 20px;
  margin: 0 0 20px;
  color: #2B1B5E;
}

.programs {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 16px;
}

.program {
  padding: 16px;
  border: 1px solid #eee0b8;
  border-radius: 8px;
}

.program h3 {
  color: #2B1B5E;
  margin: 0 0 8px;
  font-size: 16px;
}

.program p {
  margin: 0;
  font-size: 14px;
  line-height: 1.5;
}

.card ul {
  margin: 0;
  padding-left: 20px;
  line-height: 1.8;
  color: #2B1B5E;
}

</style>