# Получение данных из Google Analytics по API.

---

## О тетрадке
В тетрадке собран алоритм экспорта данных по API Google Analtics при помощи модуля gaapi4py. 

## Структура
1. Установка и импорт необходимых модулей.
2. Подключение к Google Drive.
3. Авторизация в Google Analytics.
4. Экспорт данных:
    - Простой запрос;
    - Запрос с обходом семплирования.
5. Сохранение данных в CSV.

## Необходимые модули
- **gaapi4py** — для работы с API Google Analytics;
- **join** из **os.path** — присоединяет части адреса в операционной системы;
- **drive** из **google.colab** — чтение и запись данных на Google Drtive;
- **pandas** — работа с данными в таблицах;
- **date** из **datetime** — оставить дату из объекта с датой и временем;
- **timedelta** из **datetime** — "смещение" даты;
- **sleep** из **time** — таймауты между запросами.


## Полезные ссылки
- [Документация по модулю gaapi4py](https://pypi.org/project/gaapi4py/);
- [Dimensions & Metrics Explorer](https://ga-dev-tools.appspot.com/dimensions-metrics-explorer/);
- [Google API Console](https://console.developers.google.com/apis/dashboard);
- [Google Analytics](https://analytics.google.com/analytics/).
