<template>
  <div class = "lispost" v-for = "(post, index) in listPost" :key = "index">
    <PostComp
      :date = "post.date"
      :title = "post.title"
      :type = "post.type"
    />
  </div>
</template>

<script>
import PostComp from './Post.vue'
export default {
    name: "ListPost",
    props: {
      listPost: Array,
    },
    data() {
        return {};
    },
    components: { PostComp }
}
</script>

<style>
.listpost{
  margin: 20% 20%;
}
</style>