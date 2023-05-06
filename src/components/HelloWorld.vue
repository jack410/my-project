<template>
  <div>
    <input v-model="name" placeholder="请输入你的名字">
    <p v-if="name">Hello, {{ name }}!</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: '',
    };
  },
};
</script>
