<template>
  <v-container class="fill-height">
    <v-responsive class="align-center text-center fill-height">
      <v-img
        class="mx-auto"
        height="300"
        lazy-src="@/assets/logo.svg"
        src="@/assets/logo.svg"
      >
        <template #placeholder>
          <div class="d-flex align-center justify-center fill-height">
            <v-progress-circular
              color="grey-lighten-4"
              indeterminate
            ></v-progress-circular>
          </div>
        </template>
      </v-img>

      <div class="text-body-2 font-weight-light mb-n1 mt-3">
        Bem-vindo à Plataforma
      </div>

      <h1 class="text-h2 font-weight-bold"><em class="mr-1">e-</em>Cattle</h1>
    </v-responsive>
  </v-container>
</template>

<script setup>
//
</script>
