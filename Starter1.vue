/*
beforeCreate (you can run code before the Vue instance is created)
created (you can run code after the Vue instance is created )
beforeMount (you can run code before your element is mounted to the DOM)
mounted (you can run code when the element is mounted to the DOM)
beforeUpdate (you can run code before values are updated in the DOM)
updated (you can run code after values in the DOM have been updated)
beforeDestroy (you can run code before an instance is destroyed)
destroyed (you can run code when an instance is destroyed)
*/

<template>
  <section class="component-name">
    Component here
  </section>
</template>

<script>
export default {
  name: 'ComponentName',
  // *----------------------- P r o p s ----------------------------------------------------------
  props: {},
  // *----------------------- D a t a -----------------------------------------------------------
  data() {
    return {}
  },
  // *----------------------- C o m p u t e d ---------------------------------------------------
  computed: {},
  // *----------------------- L i f e   c i r c l e ---------------------------------------------
  // for any complex logic, you should use a computed property to take out complexity from template
  created() {},
  // *----------------------- M e t h o d s -----------------------------------------------------
  methods: {},
  // *----------------------- W a t c h ---------------------------------------------------------
  watch: {}
}
</script>
