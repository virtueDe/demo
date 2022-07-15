<script>
import { h } from "vue";
export default {
  setup() {
    const submitForm = () => {
      console.log(12312);
    };
    return () =>
      h(
        "div",
        {
          class: "read-the-docs",
          style: {
            "background-color": "#000",
          },
          id: "hello",
          onClick: submitForm,
        },
        12321
      );
  },
};
</script>
<!-- 
<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test HMR
    </p>
  </div>

  <p>
    Check out
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite starter
  </p>
  <p>
    Install
    <a href="https://github.com/johnsoncodehk/volar" target="_blank">Volar</a>
    in your IDE for a better DX
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>
</template> -->

<style scoped>
.read-the-docs {
  color: red;
}
</style>
