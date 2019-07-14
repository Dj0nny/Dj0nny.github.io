<template>
  <div class="main-content">
    <div class="bio">
      <Bio></Bio>
    </div>
    <div class="skills">
      <Skills></Skills>
    </div>
  </div>
</template>

<script>
import Bio from './Bio'
import Skills from './Skills'

export default {
  name: 'Content',
  components: {
    Bio,
    Skills
  }
}
</script>


<style lang="scss">
.main-content {
  margin-top: 130px;
  text-align: center;

  @media screen and (max-width: 768px) {
    margin-top: 190px;
  }

  @media screen and (max-width: 767px) {
    margin-top: 145px;
  }

  .bio {
    text-align: center;
    margin-bottom: 30px;
  }

  .skills {
    .skill-title, .title {
      margin-bottom: 40px;
    }
    .skill {
      margin-top: 50px;
      margin-bottom: 50px;
    }
  }
}
</style>
