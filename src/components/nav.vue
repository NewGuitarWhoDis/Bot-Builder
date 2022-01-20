<template>
  <div class="nav">
    <h1>Bot Builder</h1>
    <div class="right">
      <input type="text" placeholder="Bot Token" class="botToken" />
      <button>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          version="1.1"
          id="Capa_1"
          x="0px"
          y="0px"
          viewBox="0 0 210 210"
          style="enable-background: new 0 0 210 210"
          xml:space="preserve"
        >
          <path d="M179.07,105L30.93,210V0L179.07,105z" />
          <g></g>
          <g></g>
          <g></g>
          <g></g>
          <g></g>
          <g></g>
          <g></g>
          <g></g>
          <g></g>
          <g></g>
          <g></g>
          <g></g>
          <g></g>
          <g></g>
          <g></g>
        </svg>
      </button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.nav {
  background-color: #202225;
  margin: 0px;
  height: 40px;
  padding-left: 10px;
  padding-right: 10px;
}

h1 {
  vertical-align: center;
  float: left;
  font-size: 20px;
}

.right {
  margin-top: 7px;
  float: right;
  display: flex;
  justify-content: center;
}

input {
  width: 500px;
  height: 24px;
  margin-right: 10px;
  padding-left: 10px;
  background: #40444b;
  border: none;
  color: white;
}

button {
  width: 28px;
  height: 26px;
  background: #40444b;
  border: none;
  cursor: pointer;
}
button:hover {
  background: #34373C;
}
svg {
  fill: rgb(89, 238, 109);
  margin-top: 2px;  
  width: 13px;
}
</style>
