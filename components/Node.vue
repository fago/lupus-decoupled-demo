<template>
  <div class="node">
    <h2>{{ title }}</h2>
    <slot name="default" />
    <slot name="body" />
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true
    }
  }
}
</script>
