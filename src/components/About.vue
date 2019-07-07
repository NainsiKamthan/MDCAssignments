<template>
  <div class="about">
    <h1>This is Nainsi Kamthan's Vue Project </h1>
    <h1>Hello {{ their_name }}, this is an about page</h1>
    <p> This is my first vue project which is used to add and remove skills.</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna ali...</p>
  </div>
</template>

<script>
export default {
  name: 'About',
  data() {
    return {
      their_name: this.$route.params.name
    }
  }
}
</script>