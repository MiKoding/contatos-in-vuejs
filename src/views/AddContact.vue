<template>
  <div class="container mt-3">
    <div class="row">
        <div class="col">
            <p class="h3 text-sucess fw-bold">Adicionar Contato</p>
        </div>
    </div>
  </div>

  <div class="container mt-3">
    <div class="row">
        <div class="col md-1">
            <form action="">
                <div class="mb-2">
                    <input type="text" class="form-control" placeholder="Foto">
                </div>
                
                <div class="mb-2">
                    <input type="text" class="form-control" placeholder="Nome">
                </div>

                <div class="mb-2">
                    <input type="text" class="form-control" placeholder="Número">
                </div>
                
                <div class="mb-2">
                    <input type="text" class="form-control" placeholder="Email">
                </div>
                <div class="mb-2">
                    <input type="submit" class="btn btn-success" value="Cadastrar">
                </div>
            </form>
        </div>
        <div class="col-md-4">
            <img src="https://cdn-icons-png.flaticon.com/512/219/219986.png" alt="" class="contact-img">
        </div>
    </div>
  </div>
</template>



<script>
export default{
name: "AddContact"
}
</script>