<template>
  <div>
  <nav class="navbar navbar-default">
        <ul class="nav nav-pills">
          <li role="presentation"><a href="#">Home</a></li>
          <li role="presentation"><a href="#">About</a></li>
          <li role="presentation"><a href="#">Contact</a></li>
        </ul>
    </nav>
    <header></header>
    
  </div>
    
</template>

<script>
    import Header from './Header.vue'
    export default {
      components: {
        header: Header
      },
      mounted() {
          console.log('Component mounted.')
      }
    }
</script>
