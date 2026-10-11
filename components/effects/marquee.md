# Marquee

Бегущая строка, вдохновлённая cult-ui Marquee.

## Использование

```html
<div class="marquee">
  <div class="marquee-track">
    <span>Элемент</span>
  </div>
  <div class="marquee-track" aria-hidden="true">
    <span>Элемент</span>  <!-- дубль для бесшовности -->
  </div>
</div>
```

## Варианты

- `marquee-fast` — 12s
- `marquee-slow` — 60s
- `marquee-reverse` — обратное направление
- `marquee-vertical` — вертикальная

## Принципы

- **Обязательно два трека** — второй `aria-hidden`, для бесшовного цикла
- Пауза при наведении
- Только CSS, без JS
- `prefers-reduced-motion` отключает анимацию
