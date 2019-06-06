<template>
  <div class="container is-fluid">
    <div class="navbar-custom">
      <div class="columns">
        <div class="column is-4">
          <img src="https://raw.githubusercontent.com/dj0nny/dj0nny.github.io/source/src/assets/logo.png" id="logo">
        </div>
        <div class="column is-8 social">
          <a href="#" target="_blank"><i class="fa fa-facebook"></i></a>
          <a href="#" target="_blank"><i class="fa fa-twitter"></i></a>
          <a href="#" target="_blank"><i class="fa fa-instagram"></i></a>
          <a href="#" target="_blank"><i class="fa fa-github"></i></a>
        </div>
      </div>
    </div>
  </div>
</template>



<style lang="scss" scoped>

.container.is-fluid {
  margin-left: 0 !important;
  margin-right: 0 !important;
}

.navbar-custom {
	background-color: #fff;
	box-shadow: 1px 1px 1px 1px rgba(0, 0, 0, 0.4);
	padding: 8px;
	position: fixed;
	top: 0;
	width: 100%;
  z-index: 100;
  text-align: center;
  
	img#logo {
    width: 55%;
	}

	.social {
		margin-top: 15px;

		i {
			margin-right: 20px;
			color: #284b63;
			font-size: 30px;
		}
	}
}
</style>
