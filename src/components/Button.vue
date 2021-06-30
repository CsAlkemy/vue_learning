<template>
  <button
    class="bg-green-600 text-white p-2 px-2 hover:shadow-md font-semibold hover:bg-green-400 "
  >
    {{ label }}
  </button>
</template>

<script>
export default {
  name: "Button",
  props:{
    label:{
      type:String,
      default:"Click"

    }
  }
};
</script>

<style scoped></style>
