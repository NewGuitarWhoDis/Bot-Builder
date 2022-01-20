<template>
    <div id="main-content" class="main">
        <Event name="When bot is ready" />
        <Event name="When user sends message" />
        <Event name="Command" />
    </div>
</template>

<script>
import Event from './event'

export default {
    components: {
        Event,
  },
}
</script>

<style>
    .main {
        position: absolute;
        left: 450px;
        top: 40px;
        right: 0px;
        bottom: 0px;
        background-color: transparent;
    }
</style>