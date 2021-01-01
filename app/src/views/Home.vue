<template>
  <div class="home middlecol">
    <span class="icon">💉</span>
    <h1>The COVID-19 🦠<br>Vaccination Tracker 📈</h1>
    <construction/>
  </div>
</template>

<script>
// @ is an alias to /src
import Construction from '@/components/Construction.vue'

export default {
  name: 'Home',
  components: {
    Construction
  }
}
</script>
<style lang="scss">
.icon {
  font-size: 120px;
}
</style>
