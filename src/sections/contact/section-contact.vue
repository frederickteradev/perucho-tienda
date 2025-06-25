<script setup></script>

<template>
  <section class="imagen pt-1" id="contactos">
    <div class="container-fluid pt-5 mb-2">
      <div class="row px-2">
        <div class="col-md-6 p-5">
          <h1 class="mb-4 text-danger display-4 montserrat-500">Contáctanos</h1>
          <p class="mb-4 text-white montserrat-500 lead">
            ¿Tienes dudas, o ¿necesitas alguno de nuestros productos? Estamos
            para ti. Comunicate con nosotros y recibe la atencion cercana y
            personalizada que mereces.
          </p>
        </div>
        <div class="col-md-6 px-5 pt-4">
          <div class="card bg-dark">
            
          </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
.imagen {
  background-image: url("../../assets/heros-contact.jpg");

  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  height: 135vh;
  position: relative;
}

.imagen::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.5);
  z-index: 0;
}

.imagen .container-fluid {
  position: relative;
  z-index: 1;
}
</style>
