<template>
  <div>
    <v-layout justify-center class="mb-4">
        <h1>Administración</h1>
      <v-flex align-self-center class="ml-4">
        <AgregarCursoBtn />
      </v-flex>
    </v-layout>

    <CursosTabla />

    <AlertSection />
  </div>
</template>

<script>
import CursosTabla from '../components/CursosTabla.vue'
import AgregarCursoBtn from '../components/AgregarCursoBtn.vue'
import AlertSection from '../components/AlertSection.vue'
export default {
  components: {
    CursosTabla,
    AgregarCursoBtn,
    AlertSection
  }
}
</script>

<style></style>
