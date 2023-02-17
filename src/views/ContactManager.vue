<template>
   <div class="container mt-3">
    <div class="row">
        <div class="col">
            <p class="h3 text-success fw-bold">Administrador de Contatos
                <router-link to="/contacts/add" class="btn btn-success btn-sm"><i class="fa fa-plus-circle"></i> Adicionar Contato</router-link>
            </p>
            <form>
            <div class="row">
                <div class="col-md-6">
                    <div class="row">
                        <div class="col">
                            <input type="text" class="form-control" placeholder="Procurar Contato">
                        </div>
                        <div class="col">
                            <input type="submit" class="btn btn-outline-dark">
                        </div>
                    </div>
                </div>
            </div>
            </form>
        </div>
    </div>
   </div>
   
   <!-- card de contato -->
   <div class="container mt-3">
    <div class="row">
        <div class="col-md-6">
            <div class="card my-2 list-group-item-success shadow">
                <div class="car-body">
                    <div class="row align-items-center">
                        <div class="col-sm-4">
                            <img src="https://cdn-icons-png.flaticon.com/512/219/219986.png" alt="" class="contact-img" style="margin-left: 10px;">
                        </div>
                        <div class="col-md-6">
                            <ul class="list-group">
                                <li class="list-group-item">Nome : <span class="fw-bold"> Nome </span></li>
                                <li class="list-group-item">Email : <span class="fw-bold"> Email </span></li>
                                <li class="list-group-item">Contato : <span class="fw-bold"> Contato </span></li>
                            </ul>

                        </div>
                        <div class="col-sm-1 d-flex flex-column justify-content-center align-items-center">

                            <router-link to="/contacts/view/:contactId" class="btn btn-warning my-1">
                                <i class="fa fa-eye"></i>
                            </router-link>
                            <router-link to="/contacts/Edit/:contactId" class="btn btn-primary my-1">
                                <i class="fa fa-pen"></i>
                            </router-link>
                            <button class="btn btn-danger my-1">
                                <i class="fa fa-trash"></i>
                            </button>

                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
   </div>
   
</template>

<script>
export default{
name: "ContactManager"
}
</script>