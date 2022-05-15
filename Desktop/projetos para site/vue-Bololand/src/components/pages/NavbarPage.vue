<template>
   <nav id="barra" class="navbar navbar-expand-lg">
          <div class="container-fluid">
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                  <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                      <li class="nav-item">
                          <a class="nav-link" aria-current="page" href="login.html">Perfil</a>
                      </li>
                      <li class="nav-item">
                          <a class="nav-link" aria-current="page" href="#">Vendas</a>
                      </li>
                      <li class="nav-item">
                          <a class="nav-link" aria-current="page" href="ofertas.html">Oferta do dia</a>
                      </li>
                      <li class="nav-item">
                          <a class="nav-link" aria-current="page" href="#">Historico</a>
                      </li>
  
                      <li class="nav-item">
                          <a class="nav-link" aria-current="page" href="#">Visitas</a>
                      </li>
  
                      <li class="nav-item">
                          <a class="nav-link" aria-current="page" href="#">Notificações</a>
                      </li>
  
                      <li class="nav-item">
                          <a class="nav-link" aria-current="page" href="carrinho.html">Carrinho</a>
                      </li>
                  </ul>
                  <div id="direita">
                      <input type="text" id="txtBusca" placeholder="Buscar..." />
                      <button id="btnBusca">Buscar</button>
                  </div>
              </div>
          </div>
      </nav>
  
  
      <div class="">
          <div class="container">
              <div class="row">
                  <div class="col-md-2 col-12 borda">
                      <table id="center">
  
                          <a class="nav-link" aria-current="page" href="../src/paginas/produtos.vue">Categorias</a>
  
                          <a class="nav-link" aria-current="page" href="../src/paginas/login.vue">Móveis</a>
  
                          <a class="nav-link" aria-current="page" href="login.html">Veículos</a>
  
                          <a class="nav-link" aria-current="page" href="login.html">Eletronicos</a>
  
                          <a class="nav-link" aria-current="page" href="login.html">Informática</a>
  
                          <a class="nav-link" aria-current="page" href="login.html">celulares</a>
  
                          <a class="nav-link" aria-current="page" href="login.html">Tv e Vídeo</a>
  
                      </table>
                  </div>
              </div>
          </div>
      </div>
      
</template>

<script>
export default {
  name: "NavbarPage",
};
</script>

<style scoped>
.navbar {
  padding: 0;
}

.nav-link a {
  color: #fff !important;
}

.nav-link a:hover {
  color: #0022cc !important;
  background-color: #ffffff;
  border-bottom: solid 5px #ecdd0b;
  font-weight: bold;
}
</style>