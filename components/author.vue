<template>
  <div>
    <a href="https://twitter.com/yagi_suke" target="_blank">
      <img src="/yagisuke.jpg" alt="yagisuke" class="author">
    </a>
  </div>
</template>

<style>
.author {
  width: 300px;
  height: 300px;
  border-radius: 50%;
  animation: fuwafuwa 3s infinite linear alternate;
}

@keyframes fuwafuwa {
  0% {
    transform:translate(0, 0) rotate(-5deg);
  }
  50% {
    transform:translate(0, -5px) rotate(0deg);
  }
  100% {
    transform:translate(0, 0)rotate(5deg);
  }
}
</style>
