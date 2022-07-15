<!-- <template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
  </div>
</template> -->

<script>
export default {
  name: 'Home',
  data() {
    return {
      num: 0,
    };
  },
  methods: {
    clickHandler() {
      console.log(123123);
    },
  },
  render(h) {
    return h('div', {
      class: 'bgc',
      style: {
        color: '#fff',
      },
      on: {
        click: this.clickHandler,
      },
    }, 'click me');
  },
};
</script>

<style lang="scss">
.bgc {
  background-color: red;
}
</style>
