<template>
  <div class="container main-content">
    <div class="columns bio">
      <div class="column is-12">
        Hi-Oh! I'm 23 years old dude that lives in Jesolo, near Venice, Italy. I'm studing CS at Padua University and I'm working as Web Developer.<br>
        Love HTML, CSS and Javascript. I'm a Vue.js enthusiast and a Drupal man.
      </div>
    </div>
    <div class="columns skills">
      <div class="column is-12">
        <h1 class="title is-3">Skills</h1>
        <hr>
        <div class="skill languages">
          <h3 class="title is-3">Languages</h3>
          <SkillsSlider type="languages"></SkillsSlider>
        </div>
        <div class="skill css-frameworks">
          <h3 class="title is-3">CSS Frameworks</h3>
          <SkillsSlider type="css-frameworks"></SkillsSlider>
        </div>
        <div class="skill js-frameworks">
          <h3 class="title is-3">Javascript Frameworks</h3>
          <SkillsSlider type="js-frameworks"></SkillsSlider>
        </div>
        <div class="skill dbms">
          <h3 class="title is-3">Database Management System</h3>
          <SkillsSlider type="dbms"></SkillsSlider>
        </div>
        <div class="skill cms">
          <h3 class="title is-3">Content Management System</h3>
          <SkillsSlider type="cms"></SkillsSlider>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import SkillsSlider  from './SkillsSlider'

export default {
  name: 'Content',
  components: {
    SkillsSlider
  }
}
</script>


<style lang="scss" scoped>
.main-content {
  margin-top: 130px;
  text-align: center;

  @media screen and (max-width: 768px) {
    margin-top: 190px;
  }

  @media screen and (max-width: 767px) {
    margin-top: 145px;
  }

  .skills {
    
    .title {
      margin-bottom: 40px;
    }

    .skill {
      margin-top: 50px;
      margin-bottom: 50px;
    }
  }
}
</style>
