<script lang="tsx">
export default defineComponent({
  setup() {
    const msg = ref(125888)
    return () => <div>{msg.value}</div>
  },
})
</script>
