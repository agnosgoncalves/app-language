<template>
  <div class="fixed-center text-center">
    <p>
      <img
        src="~assets/sad.svg"
        style="width:30vw;max-width:150px;"
      >
    </p>
    <p class="text-faded">Desculpe, não encontramos nada here...<strong>(404)</strong></p>
     <router-link to="/welcome">
      <q-btn
        color="secondary"
        style="width:200px;"
      >Voltar</q-btn>
     </router-link>
  </div>
</template>

<script>
export default {
  name: 'Error404'
}
</script>
