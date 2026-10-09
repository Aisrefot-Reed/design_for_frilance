# Morphing Menu

Трансформирующееся меню, вдохновлённое cult-ui Morphing Menu.

## Использование

```html
<div class="morphing-menu">
  <button class="morphing-menu-toggle">
    <span></span><span></span><span></span>
  </button>
  <div class="morphing-menu-content">
    <a href="#">Главная</a>
  </div>
</div>
```

## Принципы

- Требует JS для переключения класса `active`
- Анимация через CSS transitions
- `prefers-reduced-motion` отключает анимацию
