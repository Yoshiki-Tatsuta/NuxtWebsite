<template lang="pug">
v-container(fill-height)
 v-row
   v-col(class="text-center")
    h1 投稿記事一覧
    br
    a(href="/kijiList/kiji001")
      p python環境構築
</template>

<script lang="ts">
export default {
  name: 'PostListPage'
}
</script>
