<template>
  <div class="main-page">
  <Menu/>
  <Container/>
  </div>
</template>

<script>
import Menu from '../components/Menu';
import Container from '../components/Container'
export default {
    name: "Main-Page",
    components: {Menu, Container}

}
</script>

