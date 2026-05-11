# Montenegro Route Map

Интерактивная карта маршрута по Черногории для размещения на GitHub Pages.

## Как опубликовать на GitHub Pages

1. Создайте новый репозиторий на GitHub.
2. Загрузите в корень репозитория файл `index.html`.
3. В настройках репозитория откройте **Settings → Pages**.
4. В разделе **Build and deployment** выберите:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Нажмите **Save**.
6. Через 1–2 минуты сайт будет доступен по ссылке GitHub Pages.

## Важно

Карта использует:
- Leaflet через CDN;
- CARTO / OpenStreetMap tiles;
- OSRM routing service для построения автомобильных маршрутов;
- Google Maps links для открытия выбранного дня в Google Maps.

Google API key не нужен.
