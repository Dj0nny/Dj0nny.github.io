<template>
  <b-row> 
    <b-col md="6" class="box-pic">
      <img src="https://avatars3.githubusercontent.com/u/17474236?s=460&v=4" class="me">
    </b-col>
    <b-col md="6" class="box-info">
      <div class="who">
        {{ dj0nny.complete_name }}
        <span class="work">{{ dj0nny.work }}</span>
      </div>
      <div class="about-me">
        <div class="bio-item">
          <strong>Age: </strong><span class="info">{{ dj0nny.age }}</span> <br>
        </div>
        <div class="bio-item">
          <strong>City: </strong><span class="info">{{ dj0nny.city }}</span> <br>
        </div>
        <div class="bio-item">
          <strong>Email: </strong><span class="info">{{ dj0nny.email }}</span> <br>
        </div>
        <div class="bio-item">
          <strong>Website: </strong><span class="info"><a href="https://dj0nny.github.io/">{{ dj0nny.website }}</a></span> <br>
        </div>
        <div class="bio-item">
          <strong>GitHub: </strong><span class="info"><a href="https://github.com/dj0nny">{{ dj0nny.github }}</a></span> <br>
        </div>
      </div>
    </b-col>
  </b-row>
</template>

<script>
export default {
  name: 'Bio',
  data: () => ({
    dj0nny: {
      complete_name: 'Francesco Giambruno',
      work: 'Web Developer',
      age: '23',
      city: 'Jesolo',
      email: 'francesco.giambruno96@gmail.com',
      website: 'dj0nny.github.io',
      github: 'https://github.com/dj0nny'
    }
  })
}
</script>

<style lang="scss" scoped>
.bio-item {
  margin-bottom: 15px;
}

.who {
  font-size: 35px;

  .work {
    display: block;
    font-size: 20px;
  }
}

.about-me {
  margin-top: 30px;
  text-align: left;
    @media screen and (max-width: 768px) {
      text-align: center;
    }
  
    @media screen and (max-width: 767px) {
      text-align: center;
    }
}

img.me {
    width: 70%;
}
</style>
