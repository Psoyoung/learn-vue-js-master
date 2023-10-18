<template>
  <div>
    {{ str }}
    <app-header v-bind=""></app-header>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';

export default{
  data: function() {
    return {
      str : 'Header'
    }
  },
  components: {
    'app-header': AppHeader
  }
}
</script>
