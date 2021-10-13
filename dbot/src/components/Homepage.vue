<template>
  <div class="home">
    <div>
    <img  class="robot" src="../assets/robot-home.png" aria-hidden="true" alt="robot-home">
    </div>
    <div class="getting-started">
        <a href="">Getting started</a> building your first bot
    </div>
  </div>
</template>

<script>
export default {
  name: 'Homepage',
  props: {
    Msg: String,
  },
};
</script>
<style>
    .home {
        font-family: Verdana, Geneva, Tahoma, sans-serif;
    }
    .robot {
        height: 300px;
    }
</style>
