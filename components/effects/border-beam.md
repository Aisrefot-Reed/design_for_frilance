# Border Beam

Бегущий луч по границе, вдохновлённый cult-ui Border Beam.

## Использование

```html
<div class="border-beam">
  <div class="card">Контент</div>
</div>
```

## Варианты

- `border-beam-fast` — быстрый луч (1.5s)
- `border-beam-slow` — медленный луч (6s)
- `border-beam-double` — двойной цвет

## Принципы

- Только CSS, без JS
- Использует `mask` для создания границы
- `prefers-reduced-motion` отключает анимацию
