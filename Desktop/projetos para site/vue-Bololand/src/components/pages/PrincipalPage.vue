<template>
  <main id="home">
      <section id="propaganda1" class="container-fluid">
          <div class="row">
              <div class="col-md-1 col-12"></div>
              <div class="col-md-2 col-12">
                  <img src="imagens do site/img/p1.jpg" class="img-fluid">
              </div>
  
              <div class="col-md-2 col-12">
                  <img src="imagens do site/img/p2.jpg" class="img-fluid">
              </div>
  
              <div class="col-md-2 col-12">
                  <img src="imagens do site/img/p3.jpg" class="img-fluid">
              </div>
  
              <div class="col-md-2 col-12">
                  <img src="imagens do site/img/produto01.jpg" class="img-fluid">
              </div>
  
              <div class="col-md-2 col-12">
                  <img src="imagens do site/img/produto02.jpg" class="img-fluid">
              </div>
              <div class="col-md-1 col-12"></div>
          </div>
      </section>
  
      <section id="demonstracao1 ">
          <div class="container">
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi eum veritatis accusamus aperiam tempora! Odio neque cum iure suscipit laborum nemo, aperiam sint, nobis possimus tempore dolor delectus laudantium quia. Lorem ipsum dolor sit,
                  amet consectetur adipisicing elit. Itaque aspernatur, eos facere ea modi consectetur sunt libero! Consectetur, molestiae ullam quas laborum nostrum quis impedit dolores! Assumenda voluptatum nobis tempore. Lorem ipsum dolor sit, amet consectetur
                  adipisicing elit. Incidunt repellendus corrupti ea quae tempore quod magnam doloremque rem. Cumque minus illum modi delectus velit obcaecati nobis maiores veritatis eveniet molestias
              </p>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi eum veritatis accusamus aperiam tempora! Odio neque cum iure suscipit laborum nemo, aperiam sint, nobis possimus tempore dolor delectus laudantium quia.</p>
          </div>
      </section>
  
      <section class="">
          <div class="container">
              <div class="row">
                  <div class="col-md-4 col-6 bg-white text-center py-4">
                      <img src="imagens do site/PRODUTOS/ALEXA.jpeg" class="img-fluid">
                  </div>
  
                  <div class="col-md-4 col-6 bg-white text-center py-4">
                      <img src="imagens do site/PRODUTOS/AMPLIFICADOR.jpeg" class="img-fluid">
                  </div>
  
                  <div class="col-md-4 col-6 bg-white text-center py-4">
                      <img src="imagens do site/PRODUTOS/CAMERA DE AÇÃO.jpeg" class="img-fluid">
                  </div>
              </div>
          </div>
      </section>
  
      <section id="eletronicos" class="">
          <div class="container">
              <div class="row">
                  <div class="col-md-12 col-12">
                      <h1>
                          Eletronicos
                      </h1>
                  </div>
                  <div class="col-md-3 col-6 bg-white text-center py-4">
                      <img src="imagens do site/PRODUTOS/IPHONE SE.jpeg" class="img-fluid">
                  </div>
  
                  <div class="col-md-3 col-6 bg-white text-center py-4">
                      <img src="imagens do site/PRODUTOS/IPOD FRENTE.jpeg" class="img-fluid">
                  </div>
  
                  <div class="col-md-3 col-6 bg-white text-center py-4">
                      <img src="imagens do site/PRODUTOS/OCULOS VR.jpeg" class="img-fluid">
                  </div>
  
                  <div class="col-md-3 col-6 bg-white text-center py-4">
                      <img src="imagens do site/PRODUTOS/NOTEBOOK.jpeg" class="img-fluid">
                  </div>
  
                  <div class="col-md-3 col-6 bg-white text-center py-4">
                      <img src="imagens do site/PRODUTOS/S9+.jpeg" class="img-fluid">
                  </div>
              </div>
          </div>
      </section>
  
      <section id="demonstracao2">
      </section>
  
      <section id="areaSocial">
          <div>
              <img src="imagens do site/redes socias/facebook.png" class="icone">
          </div>
      </section>
  
      <div id="center" class="col-12">
          Todos direitos reservados
      </div>
  
  </main>
</template>

<script>
import HeaderPage from "./HeaderPage.vue";
import NavbarPage from "./NavbarPage.vue";

export default {
  components: {
    HeaderPage,
    NavbarPage,
  },
};
</script>

<style scope>
/* 
Fonte: https://fonts.google.com/specimenTab?standard-styles#about
*/

@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");
#propaganda2,
#propaganda3,
#propaganda4 {
  padding: 0;
  background-image: url(../../assets/img/propaganda/p200x1000-01-2.jpg);
  width: 100%;
  height: 100%;
  min-height: 250px;
}

/* Corpo */

body {
  font-family: "Roboto", sans-serif;
  font-size: 1em;
  /*16px*/
  background-color: #a0affb;
}

/* Areas */

section {
  height: 100%;
  min-height: 250px;
  padding: 80px 0;
}

.slides {
  min-height: 500px;
  background-size: cover;
}

.logo {
  position: absolute;
  top: 20px;
  left: 20px;
  z-index: 1000;
}

.logo img {
  max-height: 200px;
}

.produtos {
  border-radius: 5px;
  border: solid 1px #bbb;
}

.produtos input,
.produtos button {
  border-radius: 5px;
  border: solid 1px #bbb;
  padding: 5px;
}

.demostracaoDetalhe {
  height: auto;
  min-height: 450px;
  background-image: url(../../assets/img/produtos/produto01.jpg);
  background-position: center;
  background-size: cover;
  font-size: 1.2222em;
}

.vertical {
  display: table-cell;
  vertical-align: middle;
}

.border-circle {
  border-radius: 25px;
}

.imgBG1,
.imgBG2,
.imgBG3 {
  background-size: cover;
  background-position: center;
  min-height: 500px;
}

.imgBG1 {
  background-image: url(../../assets/img/produtos/p1.jpg);
}

.imgBG2 {
  background-image: url(../../assets/img/produtos/produto02.jpg);
}

.imgBG3 {
  background-image: url(../../assets/img/produtos/p3.jpg);
}

.imgSocial {
  padding: 30px;
}

.conteudoCentro {
  height: 100%;
  min-height: 250px;
}

.respansive {
  width: 100%;
}

.listLink {
  text-decoration: none;
  list-style: none;
}

.btnVoltar {
  position: fixed;
  bottom: 20px;
  right: 20px;
  padding: 10px;
  font-size: 2em;
  /* border: solid 3px;
    border-radius: 50px; */
}

.btnVoltar a {
  text-decoration: none;
}

a {
  color: #555;
}

.nolink {
  text-decoration: none;
  color: inherit;
}

.icon {
  /*32px*/
  font-size: 2em;
}

.fontIcon {
  font-size: 1.2em;
}

.copyRight {
  font-size: 0.8em;
  text-align: right;
}

footer {
  font-size: 0.9em;
}

footer h4 {
  font-size: 0.9em;
  font-weight: bold;
}

/* Media */

@media screen and (max-width: 768px) {
  .retirarElemento {
    display: none;
  }
  .logo {
    width: 100%;
    text-align: center;
  }
  .imgSocial {
    padding: 20px;
  }
}

@media print {
  #propaganda2,
  #propaganda3,
  #propaganda4 {
    display: none;
  }
}
</style>
