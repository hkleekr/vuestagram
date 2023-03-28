<template>
  <div>
    <Post :뷰스타데이터="뷰스타데이터[i]" v-for="(a,i) in 뷰스타데이터" :key="i" />
</div>
</template>

<script>
import Post from './Post.vue';

export default {
    name: 'container',
    props: {
        뷰스타데이터: Array,
    },
    components: {
        Post : Post
    }

}
</script>

<style>

</style>