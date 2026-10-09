# Floating Navbar

Плавающая навигация, вдохновлённая cult-ui Floating Navbar.

## Использование

```html
<nav class="floating-nav">
  <a href="#" class="active">Главная</a>
  <a href="#">О нас</a>
</nav>
```

## Варианты

- `floating-nav-dark` — тёмная тема

## Принципы

- `position: fixed` + `transform: translateX(-50%)`
- `backdrop-filter: blur()` для эффекта стекла
- `prefers-reduced-motion` отключает анимацию
