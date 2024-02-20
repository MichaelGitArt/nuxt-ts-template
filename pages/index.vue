<script setup lang="ts">
import type { ISection } from '~/types'

const { data } = await useFetch<any>('/api/get-data')
</script>

<template>
  <div class="bg-gray-100 p-5">
    {{ data }}
  </div>
</template>
