<template>
  <div class="about container">
    <h1>About me</h1>
    <div class="about-me">
      <p></p>
    </div>
  </div>
  <div class="skill-list">
    <h2>Meine Skills</h2>
    <div class="skill" v-for="skill in skills" :key="skill.name">
      <p>{{ skill.name }}</p>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      skills: [
        { name: "HTML 5" },
        { name: "CSS 3" },
        { name: "Javscript" },
        { name: "Datenbanken" },
        { name: "Wordpress" },
        { name: "PHP" }
      ]
    };
  }
};
</script>

<style></style>
