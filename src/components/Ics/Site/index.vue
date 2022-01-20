<template>
  <div>
    <svg-icon icon-class="link" @click="goto"/>
  </div>
</template>

<script>
export default {
  name: 'IcsSite',
  data() {
    return {
      url: 'http://ics.vip'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
