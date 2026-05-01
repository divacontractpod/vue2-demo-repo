<template>
  <div id="app" style="text-align:center; margin-top:40px;">
    <h1>{{ $t('title') }}</h1>
    <p>{{ $t('description') }}</p>

    <button @click="$i18n.locale = 'en'">EN</button>
    <button @click="$i18n.locale = 'fr'">FR</button>
  </div>
</template>

<script>
export default {
  name: 'App'
};
</script>

<style>
button {
  margin: 5px;
  padding: 8px 12px;
  cursor: pointer;
}
</style>
