<template>
  <article class="card">
    <div class="card__title">
      <h1>This is the title</h1>
    </div>
    <div class="card__body">
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo eius officia ab cum reiciendis unde rem quis voluptatibus tempora adipisci!</p>
    </div>
    <div class="card__footer">
      <button class="card__button">Click Me!</button>
    </div>
  </article>
</template>

<style scoped>
.card {
  padding-top: 24px;
  min-width: 250px;
  height: fit-content;
  background: white;
  border-radius: 12px;
  border: 1px solid #ccc;
  display: grid;
  grid-template-rows: auto 1fr auto;
  gap: 16px;
  overflow: hidden;
}

.card__title {
  padding: 0 24px;
}

.card__title > h1 {
  margin: 0;
  padding: 0;
  font-size: 20px;
  font-weight: bold;
  color: gray;
}

.card__body {
  padding: 0 24px;
}

.card__body p {
  margin: 0;
  padding: 0;
  font-size: 16px;
  color: #333;
}

.card__footer {
  padding: 12px 24px;
  background: lightgrey;
}

.card__button {
  width: 100%;
  padding: 8px 12px;
  border-radius: 4px;
  background: orange;
  color: white;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
}

.card__button:hover {
  background: orangered;
}
</style>