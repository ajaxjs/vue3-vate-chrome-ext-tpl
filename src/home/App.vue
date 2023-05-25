<template>
    <div id="popup">
        <h1>New Tab</h1>
    </div>
</template>

<script setup>
  import {ref} from 'vue'

  const count = ref(0)
</script>

<style>
#popup {
    font-size: 32px;
    color: red;
    padding: 15px;
}
</style>
