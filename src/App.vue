<script setup>
</script>
<template>
  <div id="app">
    <button>Cerrar</button>
    <br /><br />
    <div class="winOpen">
      <div class="content">
        <h1>ITGAM!</h1>
        <p>Desarrollo de Apps Para Dispositivos Móviles 📱</p>
      </div>
    </div>
  </div>
</template>

<style>
body {
  background-color: #000;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
}
/* Centered button */
button {
  background-color: #333; /* Dark button background color */
  color: #fff; /* Text color */
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.winOpen {
  position: absolute;
  left: 125px;
  width: 400px;
  transition: left 0.3s ease-in;
}
.winClose {
  position: absolute;
  left: -400px;
  width: 400px;
  background-color: #ff5733;
  transition: left 0.3s ease-in;
}
.content {
  background-color: #ff5733; /* Vibrant color for the foreground */
  color: white; /* Text color for the foreground */
  padding: 20px;
  border-radius: 5px;
  text-align: center;
}

.centered-div {
  display: flex;
  flex-direction: column;
  align-items: center;
  position: absolute;
  left: 125px;
  width: 400px;
  transition: left 0.3s ease-in;
}
</style>
