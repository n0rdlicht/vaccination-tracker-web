<template>
  <div class="construction">
    <h1>{{ msg }}</h1>
    <p>
      🏗️ A work in progress.<br /><br />&gt;
      <a href="https://github.com/n0rdlicht/rki-vaccination-scraper" target="_blank" rel="noopener">Initial Data and Experimental Visualisation</a>
    </p>
  </div>
</template>

<script>
export default {
  name: 'Construction',
  props: {
    msg: String
  }
}
</script>
