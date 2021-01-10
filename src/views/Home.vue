<template>
  <div class="home">
    <Addtodo/>
    <Todos/>
  </div>
</template>

<script>
// @ is an alias to /src
import Addtodo from '../components/Addtodo'
import Todos from '../components/Todos'
 
export default {
  name: 'Home',
  components: {
    Addtodo,
    Todos
  }
}
</script>
