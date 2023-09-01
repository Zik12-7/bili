<template>
    <div id="app">
      <router-view />
      <!-- <button style="position: absolute;bottom: 0;right: 0;" @click="clearStor">清除缓存</button> -->
    </div>
  </template>
  <script>

  </script>
  <style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  img {
    width: 100%;
    height: auto;
    display: block;
  }
  
  input {
    outline: none;
  }
  
  html,
  body,
  #app {
    width: 100%;
    height: 100%;
    overflow: auto;
  }
  
  .Wrap {
    width: 100%;
    height: 100%;
    overflow: auto;
  }
  
  .Main {
    width: 100%;
    height: 100%;
  }
  
  .Bg {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    overflow: hidden;
  }
  
  .Content {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
  }
  .floatBox {
    position: absolute !important;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    opacity: 0;
  }
  </style>
  
