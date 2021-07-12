<template>
  <p>puta vida</p>
</template>

<script>
export default {
  data() {
    return {
      title: 'Jonaflix'
    }
  },
  head() {
    return {
      title: this.title,
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        {
          hid: 'description',
          name: 'description',
          content: 'Blog pessoal e opinativo sobre obras em geral da cultura pop.'
        }
      ]
    }
  }
}
</script>
