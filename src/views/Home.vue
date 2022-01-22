<template>
  <div class="p-5">
   <h1 class="text-danger"> codebooth</h1>
   <the-button large to="/" primary >SignIn</the-button>
    <the-button to="/about" small info>Create an Accout</the-button>
  </div>
</template>

<script>
import TheButton from '../components/TheButton.vue'
// @ is an alias to /src


export default {
  name: 'Home',
  components: {
    TheButton
   
  }
}
</script>
