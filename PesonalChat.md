# Создание персонального чата

**Акторы:** 
- Пользователь
- Приложение
- Бэкенд
- БД

**Цель:** Как пользователь, я хочу возможность создать персональный чат, чтобы писать сообщения определенным людям.  
**Предусловия:** Пользователь успешно октрыл приложение и вошел в свою учетную запись, у пользователя есть контакты-пользователи, в приложении открыт список контактов текущего пользователя.

**Сценарий:**

1. Пользователь нажимает на контакт, с которым он хочет создать персональный чат.
2. Приложение отображает карточку контакта.
3. Пользователь нажимает на кнопку "Отправить сообщение".
4. Приложение отправляет запрос на создание Персонального чата на бэкенд.
5. Приложение получает ответ об успешном создании Персонального чата от сервера.
6. Приложение переходит в окно чата.

**Результат:**
- В списке чатов появился новый Персональный чат

**Исключения:**  
5a. Сервер сообщил о внутренней ошибке.

![img](https://www.websequencediagrams.com/cgi-bin/cdraw?lz=dGl0bGUg0KHQvtC30LTQsNC90LjQtSDQv9C10YDRgdC-0L3QsNC70YzQvdC-0LPQviDRh9Cw0YLQsAoK0J_QvgAWBbfQvtCyABEFtdC70YwgLT4g0J_RgNC40LvQvtC20LUAUAY6INCd0LDQtgA7BQBhBb3QsCDQutC-0L3RgtCw0LrRggoAJRQgLQBNBQBYFjog0J7RgtC-0LHRgABZBQAtCNC60LDRgNGC0L7Rh9C60LgAWw_QsACBDTSaAIIDBb_QutCwICIAdAW_AHIFstC40YLRjCAAgi4FvtCx0YkAgW4IIgCBPBc-INCh0LXRgNCy0LXRgDog0JfQsABIBb7RgQCCFAYAgnoFAIJmMGFsdAphbHQKAFEMAII5BwCCfRWe0YIAfQWCINC-0LEg0YPRgQCDeAWIAINsBbwAdRC4AIQSCS4AhAAKZWxzZQBIKafQsNGCINGB0YPRidC10YHRgtCy0YPQtdGCLCDQsgCFAwWy0YAAIAVJRACEZAoAgg040L8AhSAFg9GHAIQPCrgAcQW-AIUdBbgg0LHQtdGB0LXQtNGLAIIEM9GBAEMOtdC5AEUOZW5kAIUkMiA6INCe0LrQvQCGZgwAgj4qADoF0YjQuNCxAIUmBQCESAgAhGcJ0LUAXjaS0YsAgyAFtACFWRHRjwCEPAbQvgBvCbUAgXcFCg&s=modern-blue)
