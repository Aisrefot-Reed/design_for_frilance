# Design for Freelance — библиотека компонентов

Собственная библиотека HTML/CSS компонентов для генератора сайтов-визиток.

Вдохновлена: shadcn/ui, cult-ui, shadcnblocks.

## Структура

```
components/
├── backgrounds/      — фоновые эффекты (4)
│   ├── aurora.css       — анимированный градиентный фон
│   ├── particles.css    — частицы на фоне
│   ├── meteors.css      — падающие метеоры
│   └── grid.css         — анимированная сетка
├── text-effects/     — текстовые эффекты (4)
│   ├── typewriter.css   — эффект печатной машинки
│   ├── shimmer.css      — переливающийся текст
│   ├── flip-words.css   — переворачивающиеся слова
│   └── number-ticker.css — бегущие числа
├── cards/            — карточки и layout (4)
│   ├── bento.css        — адаптивная сетка bento
│   ├── spotlight.css    — карточка с эффектом прожектора
│   ├── tilt.css         — карточка с наклоном
│   └── glare.css        — карточка с бликом
├── navigation/       — навигация (2)
│   ├── floating-nav.css — плавающая навигация
│   └── morphing-menu.css — трансформирующееся меню
├── effects/          — визуальные эффекты (7)
│   ├── border-beam.css  — бегущий луч по границе
│   ├── blur-fade.css    — появление с размытием
│   ├── parallax.css     — параллакс
│   ├── marquee.css      — бегущая строка
│   ├── orbiting-circles.css — орбитальные круги
│   ├── sticky-scroll.css — липкий скролл
│   └── device-mockup.css — мокап устройства
├── forms/            — формы (3)
│   ├── input.css        — поля ввода
│   ├── file-drop.css    — загрузка файлов
│   └── stepper.css      — пошаговый ввод
├── sections/         — готовые секции (5)
│   ├── hero.css         — первый экран
│   ├── pricing.css      — цены
│   ├── testimonial.css  — отзывы
│   ├── contact.css      — контакты
│   └── logo-cloud.css   — облако логотипов
└── utils/            — утилиты (3)
    ├── animations.css   — базовые анимации
    ├── responsive.css   — адаптивные утилиты
    └── accessibility.css — доступность
```

**Итого: 32 компонента.**

## Использование

```html
<link rel="stylesheet" href="index.css">
<link rel="stylesheet" href="components/backgrounds/aurora.css">
<link rel="stylesheet" href="components/cards/bento.css">
```

## Принципы

1. **Без JS** — только HTML/CSS, никаких зависимостей
2. **Адаптивность** — mobile-first, брейкпоинты 700px и 1000px
3. **Доступность** — `prefers-reduced-motion`, ARIA, контраст
4. **Композируемость** — компоненты независимы, комбинируются
5. **Производительность** — CSS-only анимации, transform/opacity

## Интеграция с генератором

Библиотека подключена к пайплайну генерации сайтов:

- агент выбирает компоненты по характеру бизнеса
- CSS выбранных компонентов встраивается инлайном
- сайт остаётся самодостаточным (один HTML + фото)

Модуль интеграции: `libcomponents.py` в репозитории пайплайна.

## Лицензия

MIT
