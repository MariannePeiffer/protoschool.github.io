<template>
  <Lesson :text="text" />
</template>

<script>
import Lesson from '../../components/Lesson'
import text from './04.md'

export default {
  components: {
    Lesson
  },
  data: () => {
    return { text }
  }
}
</script>
