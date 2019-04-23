<template >
<div class="alert alert-secondary">
  <h3>Are you ready?</h3>
  <button class="btn btn-success"
  @click="$emit('onStart')">Yes start</button>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
.alert {
  text-align: center;
}

h3,
.btn {
  margin: 30px 0;
}
</style>
