<template>
    <div class="nachrichten">
      
      <NachrichtenComponent msg="Welcome to Your Vue.js App"/>
    </div>
  </template>

<script>
// @ is an alias to /src
import NachrichtenComponent from '@/components/NachrichtenComponent.vue'

export default {
  name: 'NachrichtenView',
  components: {
    NachrichtenComponent
  }
}
</script>