<template lang="pug">
v-container(fill-height)
  v-row
    v-col(class="text-center" cols="10")
      h1 トップページ
      br
      p これからいろんなプログラミングに関する記事をここに書いていく予定
    v-col(class="text-center" cols="2")
      h2 広告
      p ここに広告を表示
</template>

<script lang="ts">
export default {
  name: 'IndexPage'
}
</script>

<style>
.pre-code {
  display: block;
  background-color: black;
  color: azure;
}

.pre-code .code-text {
  display: inline-block;
  text-align: left;
  white-space: pre;
}
</style>

<!-- &ensp;は半角スペース（en space）を、&emsp;は全角スペース（em space） -->
