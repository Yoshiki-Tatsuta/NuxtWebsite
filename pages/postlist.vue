<template lang="pug">
v-container(fill-height)
  v-row
    v-col(class="text-center" cols="10")
      h1 投稿記事一覧
      br
      p 
        | ・
        NuxtLink(to="/kijiList/kiji001") python環境構築
    v-col(class="text-center" cols="2")
      h2 広告
</template>

<script lang="ts">
export default {
  name: 'PostListPage'
}
</script>
