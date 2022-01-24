<template>
  <div class="container">
    <h1 class="title">{{ $t('message') }}</h1>
    ********************************
    <!-- some code -->
    <SelectComponent />
  </div>
</template>

<script lang="ts">
import SelectComponent from '../components/LanguageInput.vue'

export default {
  name: 'IndexPage',
  components: {
    SelectComponent,
  },
}
</script>
