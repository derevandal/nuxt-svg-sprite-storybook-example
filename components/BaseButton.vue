<template>
  <button class="a">
    <slot />
  </button>
</template>

<script>
export default {
  data: () => ({
    size: '',
  }),
}
</script>
