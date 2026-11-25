# organizm-23-serpnia-dev

Статичний сайт спортклубу ORGANIZM (Харків, вул. 23 Серпня, 43).

## Сторінки

- `index.html` — головна (розклад, команда, режим роботи)
- `gallery.html` — простір клубу
- `prices.html` — абонементи (розкривні блоки)

## Стилі

Tailwind збирається в статичний `css/main.css` (CDN більше не використовується).
Після зміни класів у HTML або `css/style.css` перезберіть CSS:

```bash
npm install
npm run css:build   # або npm run css:watch під час роботи
```

`css/main.css` комітиться разом з HTML — на хостингу (Vercel) збірка не потрібна і не запускається.

## Зображення

- `img/hero`, `img/trainers`, `img/space` — WebP у двох розмірах (`-480` і `-800`).
- Іконки Lucide вбудовані в HTML як inline SVG.

## Порівняння фото К. Зарицької

`index.html` — перший варіант, `index.html?photo=2` — другий
(атрибути `data-alt-*` на картці, підміна в `js/main.js`).
