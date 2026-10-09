# Aurora Background

Анимированный градиентный фон, вдохновлённый cult-ui Aurora Background.

## Использование

```html
<div class="aurora aurora-cool">
  <div class="content">Контент</div>
</div>
```

## Варианты цветов

- `aurora-warm` — тёплые тона (оранжевый, красный)
- `aurora-cool` — холодные тона (синий, фиолетовый)
- `aurora-nature` — природные тона (зелёный)
- `aurora-sunset` — закатные тона (розовый, оранжевый)

## CSS-переменные

- `--aurora-1`, `--aurora-2`, `--aurora-3` — цвета градиентов
- `--bg` — цвет фона

## Принципы

- Только CSS, без JS
- `prefers-reduced-motion` отключает анимацию
- Контент должен быть внутри `.aurora > *`
