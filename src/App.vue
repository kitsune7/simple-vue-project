<script setup>
import { FormBuilder } from '@formio/vue'
</script>

<template>
  <main>
    <FormBuilder v-bind:form="{ display: 'form' }" v-bind:options="{}"></FormBuilder>
  </main>
</template>
