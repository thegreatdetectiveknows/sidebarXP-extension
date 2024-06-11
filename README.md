# sidebarXP - Полезная боковая панель Firefox 

## Описание
Расширение "sidebarXP" предназначено для открытия веб-страницы в боковой панели браузера Firefox.

## Тестирование расширения
1. Откройте страницу "about:debugging" в браузере Firefox.
2. Нажмите кнопку "загрузить временное дополнение" и выберите файл manifest.json.
3. Откройте веб-страницу в боковой панели с помощью контекстного меню.

## Функциональность
- Открытие любой веб-страницы в боковой панели.
- Возможность включения режима мобильной версии для веб-страниц в боковой панели
- Возможность удобного просмотра содержимого сайта без переключения между вкладками.
- Не собирает и не передаёт никакие данные, обеспечивая конфиденциальность пользователя.
- Отсутствие соединений, гарантирующее безопасность использования расширения.

## Разрешения
Разрешения необходимы для отображения мобильной версии веб-страницы в боковой панели.
- `webRequest`: Для перехвата и изменения заголовков запросов.
- `webRequestBlocking`: Для блокировки запросов, пока не будет изменен заголовок User-Agent.
- `<all_urls>`: Для перехвата запросов на всех веб-страницах.

## To Do
- Открытие любой веб-страницы в боковой панели.
- Пункт в контекстном меню.
- Задание страницы по умолчанию.
- Переключатель мобильной версии.
- Иконки.
- ... дальше больше.
