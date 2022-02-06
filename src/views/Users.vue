<template>
  <users />
</template>

<script>
export default {
  name: "Home",

  components: {
    Users: () => import("@/components/Users.vue"),
  },
};
</script>
