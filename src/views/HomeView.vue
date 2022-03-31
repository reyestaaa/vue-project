<script setup>
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'
</script>

<template>
  <Navbar />

  <main>

    <div class="content-1 container text-center">
        <img src="../assets/img/ring.png" alt="ring" class="">
        <div class="card position-absolute bottom start-50 translate-middle  border-0" style="width: 50%;">
            <div class="card-body mukta">
              <h1 class="card-title mt-2 fw-bold">Luxury Love Rings</h1>
              <h5 class="card-subtitle mb-3">make with love</h5>
              <a class="btn btn-outline-dark btn-lg fw-bold">Shop Now</a>
            </div>
          </div>
    </div>

    <div class="content-2 text-center">
        <div class="title text-start">
            <h1 class="myeongjo fw-bold">Luxury Jewelry</h1>
            <p class="londrina fw-light">Bargets</p>
        </div>
        <div class="card-gallery">
            <div>
              <img src="../assets/img/5aas.png" alt="" class="img-fluid">
            </div>
            <div>
              <img src="../assets/img/2gelang.png" alt="" class="img-fluid">
            </div>
            <div>
              <img src="../assets/img/3gelang.png" alt="" class="img-fluid">
            </div>
            <div>
              <img src="../assets/img/4gelang.png" alt="" class="img-fluid">
            </div>
          </div>
          <a class="btn btn-outline-dark btn-lg mt-5 fw-bold">Shop Luxury Bracelet</a>
    </div>

    <div class="content-3">
      <div>
        <div class="img-3">
        </div>
        <div class="text-3">
          <div class="txt-2">
                  <h2 class="fw-bold">Luxury Jewelry</h2>
                  <p class="fw-light">Crown</p>
              </div>
            <div class="txt-2">
                  <a class="btn btn-outline-dark btn-lg border-0">Show Me <i class="bi bi-arrow-right"></i> </a>
            </div>
          </div>
      </div>
      <div>
        <div class="img-3">
        </div>
        <div class="text-3">
          <div class="txt-2">
                  <h2 class="fw-bold">Luxury Jewelry</h2>
                  <p class="fw-light">Crown</p>
              </div>
            <div class="txt-2">
                  <a class="btn btn-outline-dark btn-lg border-0">Show Me <i class="bi bi-arrow-right"></i> </a>
            </div>
          </div>
      </div>
    </div>

    <div class="content-4 p-4">
      <h2 class="ms-4 mb-4">Here’s new</h2>
      <div class="row">

        <div class="col-md-6">
            <div class="card ms-4 mb-1 border-0" style="max-width: 800px;">
                <div class="row">
                  <div class="col-md-5 ">
                    <img src="../assets/img/kalung.png" class="img-fluid rounded-start" alt="...">
                  </div>
                  <div class="col-md-7">
                    <div class="card-body mt-5">
                      <h2 class="card-title">Luxury Jewelrye</h2>
                      <p class="fw-light">Crown</p>
                      <a class="btn btn-outline-dark btn-lg border-0">Show Me <i class="bi bi-arrow-right"></i> </a>
                    </div>
                  </div>
                </div>
              </div>
        </div>
        <div class="col-md-6">
            <div class="card ms-4 mb-1 border-0" style="max-width: 800px;">
                <div class="row">
                  <div class="col-md-5">
                    <img src="../assets/img/ring2.png" class="img-fluid rounded-start" alt="...">
                  </div>
                  <div class="col-md-7">
                    <div class="card-body mt-5">
                      <h2 class="card-title">Luxury Jewelrye</h2>
                      <p class="fw-light">Crown</p>
                      <a class="btn btn-outline-dark btn-lg border-0 ">Show Me <i class="bi bi-arrow-right"></i></a>
                    </div>
                  </div>
                </div>
              </div>
        </div>
      </div>
    </div>

   <div class="content-5 p-4 text-white mt-3">
        <h3 class=" w-bold">about me</h3>
        <div class="p-4 text-center ">
            <h2 class="fw-bold">Lorperie veniam voluptatibus usantium dprehenderit quidem voluptatum impedit id, provident commodi sit ut nam cum cupiditate temporibus mollitia?</h2>
            <p class="fw-light fs-6">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ipsa ad ducimus quaerat odio incidunt quibusdam non modi, vero sapiente suscipit.</p>
        </div>
   </div>




  </main>

  <Footer/>

</template>

<style scoped>
.btn{
  transition: all .30s ease-in;
}

.btn-outline-dark{
  font-family: 'Mukta Mahee', sans-serif;
}

.content-1{
  margin-bottom:140px;
}

.bottom{
  top: 90%;
}

.content-2{
  padding: 40px;
  margin-bottom: 40px;
}

.card-gallery {
    margin-top: 30px;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-gap: 10px;
    justify-content: center;
}

.content-3 {
    padding: 50px;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-gap: 136px;
    margin-bottom: 50px;
}

.text-3{
  display: flex;
  padding: 10px;
  justify-content: space-between;
  margin-top: 40px;
}

.content-5{
  background-color: rgba(239, 157, 135, 1);
}

h2{
   font-family: 'Nanum Myeongjo', serif;
   font-weight: 900;
}

p{
   font-family: 'Londrina Solid', cursive;
}

.fw-light{
  font-weight: 250;
}

.rounded-start{
  border-bottom: 5px solid black;
  border-right: 5px solid black;

}

    .img-3{
        width: 100%;
        height: 600px;
        background-image: url(../assets/img/crown.png);
        background-size: 100% 100%;
        box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
        animation: img-3 10s linear infinite;
    }

    @keyframes img-3 {
        0%{
            background-image: url(../assets/img/crown2.png);
        }
        25%{
            background-image: url(../assets/img/crown3.png);
        }
        50%{
            background-image: url(../assets/img/crown4.png);
        }
        75%{
            background-image: url(../assets/img/crown5.png);
        }
        100%{
            background-image: url(../assets/img/crown6.png);
        }
    }

</style>