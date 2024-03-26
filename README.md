# 1) Отсутствие запроса фио официанта перед началом смены в стартовом меню
## Шаги:
1. Открыть бот
2. Нажать /start
## Ожидаемый результат:
Перед началом смены бот должен спросить фио официанта
## Фактический результат: 
Перед началом смены бот не спрашивает фио официанта
## Скриншот: 
https://disk.yandex.ru/i/Kb0BfyALzmOiSw

# 2) Отсутствие у позиций меню выбора количества в списке блюд 
## Предусловия: бот запущен
## Шаги:
1. Нажать «Начать смену»
2. Нажать «Список блюд»
## Ожидаемый результат:
У каждой позиции можно выбирать количество (граммы/штуки)
## Фактический результат: 
У позиций меню нет выбора количества
## Скриншот:
https://disk.yandex.ru/d/CCUwJrXHZ5M1kw

# 3) Нет возможности освободить стол, если клиент ничего не заказывал
## Предусловия: бот запущен
## Шаги:
1. Нажать «Начать смену»
2. Нажать «Все столы»
3. Нажать 5
4. Нажать «Занять стол»
5. Нажать «Освободить стол»
## Ожидаемый результат:
Бот выдает сообщение: «Стол свободен»
## Фактический результат: 
Бот выдает сообщение: «Заказ не оплачен»
## Скриншот:
https://disk.yandex.ru/d/ynAw_eZaDVx6Pg

