<template>
  <div class="home">
    <h1>
      Hey ich bin Radu und das ist mein Bodycount:
    </h1>
    <h1>
      {{ fuckCounter }}
    </h1>
    <button @click="sendFuck()">
      Fick mich!
    </button>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data() {
    return {
      fuckCounter: 0,
    }
  },
  methods: {
    sendFuck() {
      this.fuckCounter += 1;
    }
  }
}
</script>

