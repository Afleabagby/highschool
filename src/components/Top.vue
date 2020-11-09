<template lang="pug">
//- Vue 的 img src 用 v-bind 時 ./ 代表 public 資料夾
//- 沒有用 v-bind 的話會找 src
#top
    img(:src="'./images/logo.png'")
</template>

<script>
export default {
  name: 'Top'
}
</script>
