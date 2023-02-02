<template>
    <div class="resume">
      
      <ResumeComponent msg="Welcome to Your Vue.js App"/>
    </div>
  </template>

<script>
// @ is an alias to /src
import ResumeComponent from '@/components/ResumeComponent.vue'

export default {
  name: 'ResumeView',
  components: {
    ResumeComponent
  }
}
</script>