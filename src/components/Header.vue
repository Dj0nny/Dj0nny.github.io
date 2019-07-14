<template>
  <div id="navbar" class="navbar-custom">
    <b-container fluid>
      <b-row>
        <b-col md="4">
          <img src="https://raw.githubusercontent.com/dj0nny/dj0nny.github.io/source/src/assets/logo.png" id="logo">
        </b-col>
        <b-col md="8" class="social">
          <a href="https://www.facebook.com/francesco.giambruno.9" target="_blank"><i class="fa fa-facebook"></i></a>
          <a href="https://twitter.com/Dj0nny96" target="_blank"><i class="fa fa-twitter"></i></a>
          <a href="https://www.instagram.com/francesco_giambruno/" target="_blank"><i class="fa fa-instagram"></i></a>
          <a href="https://github.com/Dj0nny" target="_blank"><i class="fa fa-github"></i></a>
          <a href="mailto:francesco.giambruno96@gmail.com" target="_blank"><i class="fa fa-envelope"></i></a>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>



<style lang="scss" scoped>
.navbar-custom {
  background-color: #fff;
	box-shadow: 1px 1px 1px 1px rgba(0, 0, 0, 0.4);
	padding: 8px;
	position: fixed;
	top: 0;
	width: 100%;
  z-index: 100;
  text-align: center;

  #logo {
    width: 300px;
  }

  .social {
		margin-top: 20px;

    @media screen and (max-width: 768px) {
      margin-top: 20px;
    }
    
    @media screen and (max-width: 767px) {
      margin-top: 10px;
    }

		i {
			margin-right: 20px;
			color: #284b63;
			font-size: 30px;
		}
	}
}
</style>
