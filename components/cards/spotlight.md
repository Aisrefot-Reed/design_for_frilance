# Spotlight Card

Карточка с эффектом прожектора, вдохновлённая cult-ui Spotlight.

## Использование

```html
<div class="spotlight">
  <h3>Заголовок</h3>
  <p>Описание</p>
</div>
```

## Варианты

- `spotlight-dark` — тёмная
- `spotlight-accent` — акцентный прожектор

## Принципы

- Эффект следует за курсором (требует JS для `--x` и `--y`)
- Без JS — статичный градиент по центру
- `prefers-reduced-motion` отключает анимацию
