<template>
  <div class="home">
    <tic-tac-toe />
  </div>
</template>

<script>
import TicTacToe from '@/components/TicTacToe.vue'

export default {
  name: 'Home',
  components: {
    TicTacToe
  }
}
</script>
