# Hero Section

Первый экран сайта, вдохновлённый shadcnblocks Hero.

## Использование

```html
<section class="hero hero-gradient">
  <div class="hero-content">
    <span class="hero-eyebrow">Новинка</span>
    <h1>Заголовок</h1>
    <p class="hero-subtitle">Описание</p>
    <div class="hero-cta">
      <a href="#" class="hero-btn hero-btn-primary">Начать</a>
    </div>
  </div>
</section>
```

## Варианты фона

- `hero-gradient` — градиентный
- `hero-dark` — тёмный
- `hero-image` — фоновое изображение

## Варианты расположения

- По центру (по умолчанию)
- `hero-left` — слева
- `hero-split` — текст + изображение

## Принципы

- Адаптивный размер текста (`clamp`)
- Кнопки с hover-эффектами
- `prefers-reduced-motion` отключает анимации
