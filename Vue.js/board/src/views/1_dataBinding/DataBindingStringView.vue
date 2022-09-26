<template>
<div>
    <h1>Hello {{ userName }}</h1>
    <p></p>
</div>
</template>
<script>
export default {
  data() {
    return {
      userName: 'Yerang Park',
      message: '',
      arr: [],
      obj: {}
    }
  }
}
</script>
