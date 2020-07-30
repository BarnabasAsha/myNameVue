<template>
  <div class="my-name">
    <h1>{{name}}</h1>
  </div>
</template>

<script>
export default {
    props: {
        name: String
    }
}
</script>

<style scoped>
    .my-name {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        height: 100vh;
        background: #f1f1f2;
        position: absolute;
        top: 0;
        left: 0;
    }

    .my-name h1 {
        font-size: 3rem;
        font-family: 'Lucida sans', sans-serif;
        color: #0f095e;
    }
</style>