<template>
  <div class="w-2/4 mx-auto">
    <div class="grid grid-cols-3 grid-rows-1 shadow-md hover:shadow-lg">
      <div class="col-span-1">
        <img
          src="https://images.unsplash.com/photo-1564069114553-7215e1ff1890?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=640&q=80"
          alt="office space"
          class="w-auto h-44 object-cover rounded-lg"
        />
      </div>
      <div class="col-span-2 bg-white p-3">
        <h1 class="text-2xl text-black font-semibold pb-3">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Aut,
          necessitatibus
        </h1>
        <Button  label="Read Now"/>
      </div>
    </div>
  </div>
</template>

<script>
import Button from "@/components/Button";
export default {
  name: "HeroCard",
  components: { Button },
};
</script>

<style scoped></style>
