<template>
  <div class="home">You see HOME!</div>
</template>

<script setup>
// @ is an alias to /src
import { onMounted } from "vue";
import { useRouter } from "vue-router";

const router = useRouter();

onMounted(() => {
  router.push("/about");
});
</script>
