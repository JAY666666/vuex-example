<template>
  <div class="item">
    <div class="meta">{{ 111 }}</div>
    <div class="content">
      <div class="header">{{ 111 || '新建笔记' }}</div>
      <div class="extra">
        <editor></editor>
        {{ 111 }} 字
        <i class="right floated trash outline icon"></i>
      </div>
    </div>
  </div>
</template>

<script>
import editor from "./Editor";

export default {
  name: "Note",
  components: {
    editor
  },
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
