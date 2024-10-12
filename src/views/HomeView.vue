<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <div id="app">
    <div class="page-wrapper">
      <div class="">
        <header>
          <img src="../../public/img/Supermercado-title-color.png" alt="" />
          <h1>Tu compra es <b>100% segura</b></h1>
          <img src="../../public/img/security.png" alt="" />
        </header>

        <main class="main">
          <img src="../../public/img/Ellipse.png" alt="" class="Ellipse" />
          <img src="../../public/img/shopping-cart.png" alt="" class="shopping-cart" />
          <h2>Tu carrito está vacío</h2>
          <div class="button">
            <a
              href="C:\Users\PC\Desktop\supermercado"
              class="hover:border-blue-500 hover:border-solid hover:bg-white hover:text-blue-500 group w-full flex flex-col items-center justify-center rounded-md border-2 border-dashed border-slate-300 text-sm leading-6 text-slate-900 font-medium py-3"
            >
              Sigue comprando
            </a>
          </div>
        </main>

        <!-- <hr class="separator-h" /> -->

        <footer>
          <div class="footer-container align-items-center">
            <img
              src="../../public/img/Logo_Supermercado.png"
              alt="logo-supermercado-xyz"
              class="logo-supermercado"
            />
            <p>Todo lo que necesitas en un solo lugar</p>
            <hr class="separator-v" />
            <div class="footer-right">
              <img src="../../public/img/map-color.png" alt="maps" class="maps" />
              <p class="maps">
                Av 13 #3-24 ***** - Cúcuta.<br />
                Norte de Santander, Colombia.
              </p>
              <img src="../../public/img/call-color.png" alt="call" class="call" />
              <p class="call">
                Celular: ##########<br />
                Telefono: ##########
              </p>
            </div>
          </div>
        </footer>
      </div>
    </div>
  </div>
</template>

<style>
header {
  width: 100%;
  height: 50px;
  background-color: #f96616;
  display: flex;
  justify-content: space-between;
  place-items: center;
  padding: 20px;
}

header img {
  /* width: 100%; */
  height: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #f96616;
}

header h1 {
  /* width: 100%; */
  height: 30px;
  color: white;
  font-size: 18px;
  margin-left: -80px;
}

header h1 b {
  /* width: 100%; */
  height: 30px;
  color: white;
  font-size: 17px;
  font-weight: bold;
}

.main {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  text-align: center;
  margin-top: -10px;
  margin-bottom: -150px;
}

.Ellipse {
  max-width: 1000px;
  width: 150px;
  height: 150px;
  margin-bottom: 1rem;
  margin-top: -100px;
}

.shopping-cart {
  max-width: 1000px;
  width: 130px;
  height: 130px;
  margin-bottom: 30px;
  margin-top: -150px;
}

.main h2 {
  font-size: 1.5rem;
  margin-bottom: 1.5rem;
  margin-left: 20px;
}

/* .button {
  text-align: left;
  float: left;
  margin-top: 10px;
  display: flex;
  justify-content: center;
} */

.button a {
  color: white;
  background-color: #f96616;
  border: 1px solid #f96616;
  margin-top: 20px;
  /* margin-right: 20px; */
  cursor: pointer;
  border-radius: 3px;
  height: 35px;
  width: 180px;
  text-align: center;
  text-decoration: none;
  font-size: 17px;
  padding: 6px;
}

.button a:hover {
  background-color: white;
  color: #f96616;
  border: 1px solid #f96616;
}

/* .separator-h {
  width: 100%;
  border: 1px solid #f96616;
} */

footer {
  width: 100%;
  height: 100%;
  justify-content: space-around;
  align-items: center;
  padding: 20px;
  border-radius: 0px 0px 10px 10px;
  border: 1px solid #f96616;
}

.footer-container {
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding-bottom: 10px;
  margin-left: -70px;
}

.footer-right {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.footer-right div {
  display: flex;
  align-items: center;
}

.footer-right p {
  display: flex;
  justify-content: space-around;
  align-items: center;
  /* padding: 20px; */
  justify-content: space-around;
}

.footer-right img {
  display: flex;
  justify-content: space-around;
  align-items: center;
  /* padding: 20px; */
  justify-content: space-around;
  margin-left: -130px;
}

.separator-v {
  border-left: 1px solid #f96616;
  height: 170px;
  display: inline-block;
  margin-right: 20px;
}

footer p {
  /* width: 100%; */
  height: 100%;
  left: 20px;
  color: #f96616;
  font-family: Georgia, 'Times New Roman', Times, serif;
  display: flex;
  margin-left: -90px;
  font-size: 17px;
}

footer img {
  width: 230px;
  height: 150px;
  /* background-color: #f96616; */
  margin-left: 20px;
  margin-top: 20px;
}

footer .maps {
  width: 35px;
  height: 35px;
}

p.maps {
  width: 300px;
  margin-right: -50px;
  margin-top: -50px;
  text-align: center;
}

footer .call {
  width: 30px;
  height: 30px;
}

p.call {
  width: 300px;
  margin-right: -250px;
  margin-top: -48px;
  text-align: center;
}
</style>
