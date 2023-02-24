<script setup>
import { name as webName } from '../package.json'

</script>
<template>
  <div flex justify-between>
    <h1 class="text-4xl font-semibold sm:text-5xl u-text-gray-900">{{ webName }}</h1>
    <div></div>
    <Links />
  </div>
</template>
