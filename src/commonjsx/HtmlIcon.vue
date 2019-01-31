<style scoped>
.icon {
  display: block;
}
</style>

<script>
export default {
  name: "HtmlIcon",

  props: {
    src: {
      type: String
    }
  },

  methods: {},

  render(h) {
    return h(
      "div",

      {
        class: "icon",
        domProps: {
          innerHTML: "<strong>喷出dom结构</strong>"
        }
      }
    );
  }
};
</script>
