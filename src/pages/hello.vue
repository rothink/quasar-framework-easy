<template>
  <q-page padding>
    <hello />
  </q-page>
</template>

<script>
import Hello from '../components/hello'
export default {
  // name: 'PageName',
    components: {
        'hello' : Hello
    },
    mounted() {
        console.info(this.$newPluginName);
    }
}
</script>

<style>
</style>
