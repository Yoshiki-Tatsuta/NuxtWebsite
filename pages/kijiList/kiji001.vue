<template lang="pug">
v-container(fill-height)
  v-row(justify="center")
    v-col.border-style(cols="6")
      h1 pythonの環境構築
      br
      .pre-code
        pre
          code.code-text
            | print('hello world')
            |  hello world
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
.border-style {
    border:1px solid #D3D3D3;
}
</style>