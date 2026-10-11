# Device Mockup

Мокап устройства, вдохновлённый cult-ui Device Mockups.

## Использование

```html
<div class="device device-laptop">
  <div class="device-screen">
    <img src="screenshot.jpg" alt="">
  </div>
</div>
```

## Варианты

- `device-laptop` — ноутбук с подставкой
- `device-phone` — телефон с вырезом
- `device-tablet` — планшет
- `device-browser` — окно браузера с точками

## Принципы

- Только CSS, без JS
- `aspect-ratio` держит пропорции
- Внутрь `.device-screen` — `img` или любой контент
