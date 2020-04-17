<template>
  <div>
    <p class="slj-title"><slot></slot></p>
    <slot name="line">
       <hr class="my-4" />
    </slot>
  </div>
</template>

<script>
export default {
  name: 'Title'
}
</script>

<style>
.slj-title {
  font-size: 2rem;
  line-height: 5rem;
}
</style>
