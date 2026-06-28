# Dead Land, Dead Skies map generator editor

Самодостаточный браузерный генератор гексовой карты для настольно-ролевой игры "Мёртвое небо, мёртвая земля".

Откройте `index.html` в браузере. Установка зависимостей не нужна.

## Что умеет

- Генерирует регион seed-ом по 6-мильным гексам.
- Использует броски 2d6 для ландшафта, d6 для окультуренных участков и d20 для достопримечательностей.
- Создаёт поселения с блоками, населением, властью, богатством, скрытым управлением и публичным заведением.
- Соединяет окультуренные гексы дорогами, крупные поселения железной дорогой, а речные участки в системы или озёра.
- Показывает подробности выбранного гекса по клику.
- Масштабирует карту колесом мыши к курсору и двигает viewport при зажатой правой кнопке мыши.
- Переключает чистый и атмосферный режимы отображения.
- В атмосферном режиме рисует карту как потрёпанный лист на тёмном столе, с дымом, грязью, ржавчиной, кровью и проволокой на местности.
- Рисует отдельные значки для всех достопримечательностей из таблицы d20.
- Экспортирует карту в PNG и данные генерации в JSON.

Гексовая карта и атмосферная подложка рисуются процедурно.

---

## English

Self-contained browser-based hex map generator for the tabletop role-playing game "Dead Sky, Dead Land".

Open `index.html` in a browser. No dependency installation required.

## Features

- Generates a region from a seed using 6-mile hexes.
- Uses 2d6 rolls for terrain, d6 for developed areas, and d20 for landmarks.
- Creates settlements with districts, population, authority, wealth, hidden control, and a public establishment.
- Connects developed hexes with roads, major settlements with railways, and river segments into river systems or lakes.
- Shows details for the selected hex on click.
- Zooms the map toward the cursor with the mouse wheel and moves the viewport while the right mouse button is held.
- Switches between clean and atmospheric display modes.
- In atmospheric mode, renders the map as a worn sheet on a dark table, with smoke, dirt, rust, blood, and wire across the terrain.
- Draws unique icons for every landmark from the d20 table.
- Exports the map as PNG and generation data as JSON.

The hex map and atmospheric backdrop are generated procedurally.

## License

MIT. See `LICENSE`.
