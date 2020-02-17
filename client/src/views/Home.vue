<template>
  <div class="home">
    <TaskBar />
  </div>
</template>

<script>
// @ is an alias to /src
import Taskbar from '@/components/TaskBar.vue'

export default {
  name: 'Home',
  components: {
    Taskbar
  }
}
</script>
