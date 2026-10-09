# Design for Freelance — библиотека компонентов

Собственная библиотека HTML/CSS компонентов для генератора сайтов-визиток.

Вдохновлена: shadcn/ui, cult-ui, shadcnblocks.

## Структура

```
components/
├── backgrounds/      — фоновые эффекты (4 компонента)
│   ├── aurora.css       — анимированный градиентный фон
│   ├── particles.css    — частицы на фоне
│   ├── meteors.css      — падающие метеоры
│   └── grid.css         — анимированная сетка
├── text-effects/     — текстовые эффекты (4 компонента)
│   ├── typewriter.css   — эффект печатной машинки
│   ├── shimmer.css      — переливающийся текст
│   ├── flip-words.css   — переворачивающиеся слова
│   └── number-ticker.css — бегущие числа
├── cards/            — карточки и layout (4 компонента)
│   ├── bento.css        — адаптивная сетка bento
│   ├── spotlight.css    — карточка с эффектом прожектора
│   ├── tilt.css         — карточка с наклоном при наведении
│   └── glare.css        — карточка с бликом
├── navigation/       — навигация (2 компонента)
│   ├── floating-nav.css — плавающая навигация
│   └── morphing-menu.css — трансформирующееся меню
├── effects/          — визуальные эффекты (3 компонента)
│   ├── border-beam.css  — бегущий луч по границе
│   ├── blur-fade.css    — появление с размытием
│   └── parallax.css     — параллакс эффект
├── forms/            — формы (3 компонента)
│   ├── input.css        — стилизованные поля ввода
│   ├── file-drop.css    — зона для загрузки файлов
│   └── stepper.css      — пошаговый ввод
├── sections/         — готовые секции (4 компонента)
│   ├── hero.css         — первый экран
│   ├── pricing.css      — секция цен
│   ├── testimonial.css  — отзывы
│   └── contact.css      — контакты
└── utils/            — утилиты (3 компонента)
    ├── animations.css   — базовые анимации
    ├── responsive.css   — адаптивные утилиты
    └── accessibility.css — утилиты доступности
```

## Использование

### Вариант 1: Подключить всё

```html
<link rel="stylesheet" href="index.css">
```

### Вариант 2: Подключить только нужное

```html
<link rel="stylesheet" href="index.css">
<link rel="stylesheet" href="components/backgrounds/aurora.css">
<link rel="stylesheet" href="components/sections/hero.css">
```

### Вариант 3: Исппользовать отдельные компоненты

```html
<link rel="stylesheet" href="components/utils/animations.css">
<link rel="stylesheet" href="components/cards/bento.css">
```

## Принципы

1. **Без JS** — только HTML/CSS, никаких зависимостей
2. **Адаптивность** — mobile-first, брейкпоинты 700px и 1000px
3. **Доступность** — `prefers-reduced-motion`, ARIA-атрибуты, контраст
4. **Композируемость** — компоненты независимы, можно комбинировать
5. **Производительность** — CSS-only анимации, transform/opacity

## Лицензия

MIT
