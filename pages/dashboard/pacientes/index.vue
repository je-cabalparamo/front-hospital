<template>
  <tablaPacientes />
</template>

<script>
import tablaPacientes from '~/components/pacientes/tabla-pacientes.vue'
export default {
  name: 'IndexPage',
  auth: true,
  components: {
    tablaPacientes
  },
  layout: 'main'
}
</script>
