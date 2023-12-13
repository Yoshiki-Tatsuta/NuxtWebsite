<template lang="pug">
v-container(fill-height)
  v-row(justify="center")
    v-col(cols="8")
      h1 pythonの環境構築
      br
      .pre-code
        pre
          code.code-text
            | print('hello world')
            |  hello world
    v-col(cols="2")
      h2 広告
      p 表示
</template>

<script lang="ts">
export default {
  name: 'Kiji001Page'
}
</script>

<style>
.pre-code {
  display: block;
  background-color: black;
  color: azure;
}
/* .border-style {
    border:1px solid #D3D3D3;
} */
</style>