<script setup>
const handleClick = () => {
  alert("ボタンがクリックされました")
}
</script>

<template>
  <h1>Sample4</h1>
  <button @click="handleClick">click</button>
  <button @mouseover="handleClick">click</button>
</template>




