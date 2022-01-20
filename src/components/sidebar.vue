<template>
  <div class="sidebar">
    <div class="blocks">
      <Block @drop-block="$emit('drop-block', 'onready')" name="When bot is ready"/>
      <Block name="When user sends messsage" />
      <Block name="Command" />
    </div>
  </div>
</template>

<script>
import Block from './block'

export default {
  name: 'Sidebar', 
  components: {
    Block,
  },
}
</script>

<style scoped>

    .sidebar {
        background-color: #2F3136;
        position: absolute;
        top: 40px;
        bottom: 0px;
        left: 200px;
        width: 250px;
    }

</style>
