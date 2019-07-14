<template>
  <b-row>
    <b-col md="12">
      <h1 class="title">Skills</h1>
      <hr>
      <div class="skill languages">
        <h3 class="skill-title">Languages</h3>
        <SkillsSlider type="languages"></SkillsSlider>
      </div>
      <div class="skill js-frameworks">
        <h3 class="skill-title">Frameworks</h3>
        <SkillsSlider type="frameworks"></SkillsSlider>
      </div>
      <div class="skill dbms">
        <h3 class="skill-title">Database Management System</h3>
        <SkillsSlider type="dbms"></SkillsSlider>
      </div>
      <div class="skill cms">
        <h3 class="skill-title">Content Management System</h3>
        <SkillsSlider type="cms"></SkillsSlider>
      </div>
    </b-col>
  </b-row>
</template>

<script>
import SkillsSlider  from './SkillsSlider'

export default {
  name: 'Skills',
  components: {
    SkillsSlider
  }
}
</script>

<style>

</style>
