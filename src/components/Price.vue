<template>
  <div class="price">
    <div class="container">
      <div class="card">
        <div class="box">
          <div class="content">
            <h3>35 €</h3>
            <p>One time week</p>
          </div>
        </div>
      </div>

      <div class="card">
        <div class="box">
          <div class="content">
            <h3>45 €</h3>
            <p>Two time week</p>
          </div>
        </div>
      </div>

      <div class="card">
        <div class="box">
          <div class="content">
            <h3>55 €</h3>
            <p>Open house</p>
          </div>
        </div>
      </div>

      <div class="card">
        <div class="box">
          <div class="content">
            <h3>Payments</h3>
            <p>Transferencia</p>
            <p>Dinheiro</p>
            <p>Debito directo</p>
          </div>
        </div>
      </div>

      <div class="card2">
        <div class="box">
          <div class="content">
            <h3>Contacts:</h3>
            <p>Crossfitvaledoavetrofa@gmail.com</p>
            <br>
            <p>933818537</p>
            <br>
            <a href="https://www.facebook.com/CrossFitValedoAve"><img src="https://img.icons8.com/color/48/000000/facebook.png"/></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Parallax from 'vue-parallaxy'

export default {
  name: 'App',
  components: {
    Parallax
  }
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700;800&display=swap");

.table {
  margin: auto;
  width: 50%;
  padding: 100px;
}

.price {
  margin: auto;
  padding: 100px;
  color: red;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}

body {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  min-height: 100vh;
  background: #232427;
}

body .container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  max-width: 1200px;
  margin: 40px 0;
}

body .container .card {
  position: relative;
  min-width: 200px;
  height: 340px;
  box-shadow: inset 5px 5px 5px rgba(0, 0, 0, 0.2),
  inset -5px -5px 15px rgba(255, 255, 255, 0.1),
  5px 5px 15px rgba(0, 0, 0, 0.3), -5px -5px 15px rgba(255, 255, 255, 0.1);
  border-radius: 15px;
  margin: 30px;
  transition: 0.5s;
}

body .container .card .box {
  position: absolute;
  top: 20px;
  left: 20px;
  right: 20px;
  bottom: 20px;
  background: #2a2b2f;
  border-radius: 15px;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  transition: 0.5s;
}

body .container .card .box:hover {
  transform: translateY(-50px);
}

body .container .card .box:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 50%;
  height: 100%;
  background: rgba(255, 255, 255, 0.03);
}

body .container .card .box .content {
  padding: 20px;
  text-align: center;
}

body .container .card .box .content h2 {
  position: absolute;
  top: -10px;
  right: 30px;
  font-size: 8rem;
  color: rgba(255, 255, 255, 0.1);
}

body .container .card .box .content h3 {
  font-size: 1.8rem;
  color: #fff;
  z-index: 1;
  transition: 0.5s;
  margin-bottom: 15px;
}

body .container .card .box .content p {
  font-size: 1rem;
  font-weight: 300;
  color: rgba(255, 255, 255, 0.9);
  z-index: 1;
  transition: 0.5s;
}


body .container .card2 {
  position: relative;
  min-width: 320px;
  height: 440px;
  box-shadow: inset 5px 5px 5px rgba(0, 0, 0, 0.2),
  inset -5px -5px 15px rgba(255, 255, 255, 0.1),
  5px 5px 15px rgba(0, 0, 0, 0.3), -5px -5px 15px rgba(255, 255, 255, 0.1);
  border-radius: 15px;
  margin: 0px;
  transition: 0.5s;
}

body .container .card2 .box {
  position: absolute;
  top: 20px;
  left: 20px;
  right: 20px;
  bottom: 20px;
  background: #2a2b2f;
  border-radius: 15px;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  transition: 0.5s;
}

body .container .card2 .box:hover {
  transform: translateY(-50px);
}

body .container .card2 .box:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 50%;
  height: 100%;
  background: rgba(255, 255, 255, 0.03);
}

body .container .card2 .box .content {
  padding: 20px;
  text-align: center;
}

body .container .card2 .box .content h2 {
  position: absolute;
  top: -10px;
  right: 30px;
  font-size: 8rem;
  color: rgba(255, 255, 255, 0.1);
}

body .container .card2 .box .content h3 {
  font-size: 1.8rem;
  color: #fff;
  z-index: 1;
  transition: 0.5s;
  margin-bottom: 15px;
}

body .container .card2 .box .content p {
  font-size: 0.9rem;
  font-weight: 300;
  color: rgba(255, 255, 255, 0.9);
  z-index: 1;
  transition: 0.5s;
}

</style>
