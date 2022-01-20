<template>
  <div v-on:click="DropBlock()" class="block" draggable="true">
      <h1>{{name}}</h1>
  </div>
</template>

<script>
export default {
    name: 'block',
    props: {
        name: String,
        eventId: String,
    },
    methods: {
        DropBlock() {
            this.$emit('drop-block');
        }
    }
};

</script>

<style scoped>
 .block {
     background: rgb(93, 93, 207);
     margin: 10px;
     margin-bottom: 15px;
     padding: 10px;
     border-radius: 5px;
     cursor: pointer;
     user-select: none;
     
 }
 h1 {
     font-size: 20px;
 }
</style>