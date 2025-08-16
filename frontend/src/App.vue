<template>
  <div class="welcome">
    <h1>👋 Добро пожаловать в Vue 2 + Vite</h1>
    <p>Вы успешно запустили проект!</p>

    <div class="card">
      <h2>Что дальше?</h2>
      <ul>
        <li>Откройте <code>App.vue</code> и начните редактировать</li>
        <li>Попробуйте добавить новые компоненты</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped>
.welcome {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  font-family: system-ui, sans-serif;
  background: linear-gradient(135deg, #42b983, #35495e);
  color: #fff;
  text-align: center;
  padding: 2rem;
}

h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.card {
  background: rgba(255, 255, 255, 0.15);
  padding: 1.5rem 2rem;
  border-radius: 12px;
  margin-top: 2rem;
  text-align: left;
}

.card h2 {
  margin-bottom: 0.5rem;
}

.card ul {
  list-style: none;
  padding: 0;
}

.card li {
  margin: 0.3rem 0;
}
</style>
