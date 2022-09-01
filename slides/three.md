---
layout: two-cols
---
# Mau pasang Vue Component juga bisa!

```html
<!-- components/MyCard.vue -->

<template>
  <article class="card">
    <div class="card__title">
      <h1>This is the title</h1>
    </div>
    <div class="card__body">
      <p>Lorem ipsum dolor sit amet...</p>
    </div>
    <div class="card__footer">
      <button class="card__button">Click Me!</button>
    </div>
  </article>
</template>
```

::right::

<div class="three__right-container">
  <MyCard />
</div>

<style>
  .three__right-container {
    padding: 0 24px;
    height: 100%;
    display: flex;
    align-items: center;
  }
</style>