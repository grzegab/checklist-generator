<script setup>
import { useFormStore } from '@/stores/form.js'

const formStore = useFormStore()
</script>

<template>
  <h2 class="title">Translate Filters Text (TFT)</h2>
  <h3 class="subtitle">It describe selected filters to point out all bad or good decisions</h3>
  <div class="field">
    <label class="label">Text generated by AI:</label>
    <div class="control">
      <textarea v-model="formStore.filterOutput" placeholder="Text to set filters to ..." class="textarea"></textarea>
    </div>
  </div>

  <div class="field is-grouped">
    <div class="control">
      <button class="button is-primary" @click="formStore.explainFilters">Submit</button>
    </div>
  </div>
</template>