<template>
  <div class="about">
    <h1>Vue Todos</h1>
    <p>Vue Todos is a Crud Todo tracking application created for a Vue 3 Crash course by John Komarnicki.</p>
    <p>Track your daily task's using this todo tracker with abilities to save, complete, edit & delete todos.</p>
    <p>Feel free to addd on this application with functionalities such as the ability to drag and render todos, animate creation/deletion of todos or even create this into a full stack application with the ability to have different days of tracking todos!</p>
  </div>
</template>

<style>
.about {
  padding: 16px;
  text-align: justify;
  p {
    margin: 16px 0;
  }
}

@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
