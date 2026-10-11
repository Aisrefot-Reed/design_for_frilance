# Orbiting Circles

Орбитальные круги, вдохновлённые cult-ui Orbiting Circles.

## Использование

```html
<div class="orbit">
  <div class="orbit-center">Ядро</div>
  <div class="orbit-ring">
    <div class="orbit-item">1</div>
  </div>
</div>
```

## Варианты

- `orbit-ring-inner` — внутреннее кольцо (обратное вращение)

## CSS-переменные

- `--orbit-size` — размер (по умолчанию 320px)
- `--orbit-duration` — период вращения (24s)
- `--orbit-line` — цвет кольца

## Принципы

- Только CSS, без JS
- Элементы вращаются, но текст остаётся прямым (`orbit-counter`)
- До 4 элементов на кольцо
