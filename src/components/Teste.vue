<script setup>
import '@mdi/font/css/materialdesignicons.css'
import 'vuetify/styles'

</script>


<template>
    <h1>vue component</h1>
    <v-btn color="orange-darken-2" variant="text" prepend-icon="mdi-check-circle" selected-class="btnhover">Botao</v-btn>
    <v-btn>
        <v-icon icon="$vuetify" color="orange-darken-2" selected-class="btnhover"></v-icon>
    </v-btn>

</template>

<style>
    .btnhover {
        background-color: transparent;
        border-style: none;
    }
</style>