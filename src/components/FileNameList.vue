<template>
    <p>여기는 파일이름리스트</p>

    <v-file-input webkitdirectory></v-file-input>

</template>

<script>
export default {
  name: 'App',
  data() {
    return {
        folder: null
    }
  }
}
  </script>