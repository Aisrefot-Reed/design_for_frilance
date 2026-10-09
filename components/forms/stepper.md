# Stepper

Пошаговый ввод, вдохновлённый cult-ui Stepper.

## Использование

```html
<div class="stepper">
  <div class="stepper-step completed">
    <div class="stepper-circle">✓</div>
    <span class="stepper-label">Шаг 1</span>
  </div>
  <div class="stepper-line completed"></div>
  <div class="stepper-step active">
    <div class="stepper-circle">2</div>
    <span class="stepper-label">Шаг 2</span>
  </div>
</div>
```

## Состояния

- `stepper-step.active` — текущий шаг
- `stepper-step.completed` — завершённый шаг
- `stepper-line.completed` — завершённая линия
