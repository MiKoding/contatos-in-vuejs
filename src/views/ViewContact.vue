<template>
     <div class="container mt-3">
    <div class="row">
        <div class="col">
            <p class="h3 text-sucess fw-bold">Detalhes do Contato</p>
        </div>
    </div>
  </div>

  <div class="container">
    <div class="row align-items-center">
        <div class="col-md-4">
            <img src="https://cdn-icons-png.flaticon.com/512/219/219986.png" alt="" class="contact-img-big">
        </div>
        <div class="col-md-6">
            <ul class="list-group">
                <li class="list-group-item">Nome : <span class="fw-bold"> Nome </span></li>
                <li class="list-group-item">Email : <span class="fw-bold"> Email </span></li>
                <li class="list-group-item">Contato : <span class="fw-bold"> Contato </span></li>
            </ul>
        </div>
    </div>
    <div class="row mt-3">
    <div class="col">
        <router-link to="/" class="btn btn-success"><i class="fa fa-arrow-alt-circle-left"></i>Voltar</router-link>
    </div>
  </div>
  </div>
  
</template>

<script>
export default{
    name: "ViewContact"
}
</script>