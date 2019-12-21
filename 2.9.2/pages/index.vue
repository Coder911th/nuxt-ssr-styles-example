<template>
  <div>
    <div class="rect"></div>
    <style>
      .rect {
        background-color: {{ color }};
      }
    </style>
  </div>
</template>

<script>
export default {
  data() {
    return {
      color: 'red'
    }
  }
}
</script>

<style>
.rect {
  width: 200px;
  height: 100px;
  margin: 10px auto;
  border: 1px solid #000;
}
</style>

