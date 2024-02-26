<template>
  <div>{{ answer }}</div>
</template>

<script>
import axios from "axios";

export default {
  name: "App",
  data() {
    return {
      answer: {},
    };
  },
  methods: {
    async getAnswer() {
      const { data } = await axios.get("https://api.chucknorris.io/jokes/random");
      this.answer = data.value;
    },
  },
  beforeMount() {
    this.getAnswer();
  },
};
</script>