<template>

<header>
    <div class=" top">
        <h5>About Me</h5>
        <h1 class="text-center me-4">Luxury Jewelry</h1>
        <div class="icon">
        <img src="../assets/img/clarity_user-line.png" alt="" class="img-fluid logo-img">
            <a href="">
            <img src="../assets/img/fe_location.png" alt="" class="img-fluid logo-img">
            store</a>
        </div>
    </div>
    
    <nav class="navbar navbar-expand-lg navbar-light p-3">
      <div class="container">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-center" id="navbarNavAltMarkup">
          <div class="navbar-nav fs-5">
            <a class="nav-link active " href="#">Ring</a>
            <a class="nav-link " href="#">Bracelet</a>
            <a class="nav-link " href="#">Necklace</a>
            <a class="nav-link " href="#">Crown</a>
            <a class="nav-link " href="#">What’s new?</a>
          </div>
        </div>
      </div>
    </nav>
</header>

</template>

<style scoped>
nav{
  background-color: white;
}
h1{
  font-family: 'Nanum Myeongjo', serif;
  font-weight: bold;
}
.top{
  display: flex;
  padding: 20px;
  justify-content: space-between;
}

.nav-link{
  margin-right: 50px;
  font-family: 'Londrina Solid', cursive
} 

h5{
  font-family: 'Mukta Mahee', sans-serif;
}

.logo-img{
  width: 30px;
height: 30px;
object-fit: cover;
}

.icon a{
text-decoration: none;
color: black;
}



</style>


