<template>
  <div id="app">
    <div class="container">
      <h1>情人节快乐，周军一！</h1>
      <p>亲爱的军一，我们已经一起走过了6年的风风雨雨，每一天都因为有你而变得更加美好。</p>
      <p>你是我生命中最重要的人，我爱你胜过一切。</p>
      <p>愿我们的爱情像这颗心一样，永远跳动不息。</p>
      <div class="heart">❤️</div>
    </div>
  </div>
</template>

<style>
html,
body {
  margin: 0;
  padding: 0;
}
#app {
  width: 100%;
  height: 100%;
  overflow: hidden;
  /* background: url('./assets/image/image.jpg') no-repeat center center; */
  background-size: 100% 100%;
}
body {
  font-family: 'Arial', sans-serif;
  background-color: #ffebee;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
  overflow: hidden;
}
.container {
  text-align: center;
  color: #d32f2f;
}
h1 {
  font-size: 3rem;
  animation: fadeIn 2s ease-in-out;
}
p {
  font-size: 1.5rem;
  animation: slideIn 2s ease-in-out;
}
.heart {
  font-size: 5rem;
  animation: beat 1s infinite;
}
@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
@keyframes slideIn {
  0% {
    transform: translateY(-50px);
    opacity: 0;
  }
  100% {
    transform: translateY(0);
    opacity: 1;
  }
}
@keyframes beat {
  0%,
  100% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.2);
  }
}
</style>
