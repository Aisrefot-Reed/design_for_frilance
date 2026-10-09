# File Drop

Зона для загрузки файлов, вдохновлённая cult-ui File Drop.

## Использование

```html
<div class="file-drop">
  <div class="file-drop-icon">📁</div>
  <p class="file-drop-text">Перетащите файл сюда</p>
  <input type="file">
</div>
```

## Принципы

- Требует JS для класса `dragover`
- `prefers-reduced-motion` отключает анимацию
