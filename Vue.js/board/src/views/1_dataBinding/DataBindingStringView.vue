<template>
<div>
    <h1>Hello {{ userName }}</h1>
    <p>{{message}}</p>
</div>
</template>
<script>
export default {
  data() {
    return {
      userName: 'Yerang Park',
      message: 'Welcome to 뷰의 세계',
      arr: [],
      obj: {}
    }
  }
}
</script>
