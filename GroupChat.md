# Создание общего чата

**Акторы:** 

- Пользователь 
- Приложение
- Бэкенд
- БД

**Цель:** Как пользователь, я хочу иметь возможность создать общий чат, чтобы что-то обсуждать в группе по интересам.

**Предусловия:** Пользователь успешно октрыл приложение и вошел в свою учетную запись, у пользователя есть контакты (>0), в приложении открыта главная страница.

**Сценарий:**

1. Пользователь нажимает на кнопку "Создать общий чат"
2. Приложение отображает диалоговое окно с опциями создания Общего чата.
3. Пользователь заполняет поля: "Название", "Описание".
4. Пользователь нажимает на кнопку "Добавить участников".
5. Приложение отображает список контактов с чекбоксами.  
6. Пользователь выбирает нужные контакы, ставя напротив них флажки в чекбоксах.
7. Пользователь подтверждает свой выбор, нажимая на кнопку "ОК".
8. Приложение возвращается к основонму диалоговому окну создания Общего чата.
9. Пользователь нажимает на кнопку "Создать".
10. Приложение отправляет запрос на создание Общего чата.
11. Приложение получает ответ об успешном создание Общего чата.
12. Приложение переходит в окно группового чата.

**Результат:**
- В списке чатов пользователя появляется новый Общий чат.
- В БД успешно сохраняется новый Общий чат

**Исключения:**  
7а1. Пользователь не выбрал ни одного контакта.  
7а2. Пользователь не заполнил "Название" Общего чата.  
11а1. Сервер сообщил овнутренней ошибке.

![img](https://www.websequencediagrams.com/cgi-bin/cdraw?lz=dGl0bGUg0KHQvtC30LTQsNC90LjQtSDQs9GA0YPQv9C_0L7QstC-0LPQviDRh9Cw0YLQsAoK0J_QvtC70YzQtwAaBbDRgtC10LvRjCAtPiDQn9GA0LjQu9C-0LbQtQBKBjog0JrQvdC-0L_QutCwICIAZgrRgtGMAFwSuQBlByIgCgA7FC0tPgBqGDog0J7RgtCx0YDQsAB2CiDQlNCeINGBINC-0L_RhtC40Y_QvNC4INCe0LHRidC1AIFSDSAAgUYZLT4AgUYXl9CwAIIlBbvQvQBpCgALBrXQuSAi0J3QsNC30LIAglgIIiwgItCe0L_QuNGBAAsJAEUzAIJHDpTQvtCx0LDQstC4AIJSBdGDAIMtBYHRggCDUQW60L7QsiIAgjwVIC0AgzQFAII2Hb4AgkQR0YEAgTsHutCwIABaBb3RgtCw0LoAKQWyINGBINGH0LXQutCx0L7QugCBZgW80LgAhAo0ktGL0LHQvtGAINC90YPQttC90YvRhQBiEywAgnIGtNGC0LLQtdGA0LbQtACDfAqyAD0KugCFBwm-0Lkg0J7QmgCBZTWSAIY0BbLRgNCw0YIg0Log0L7RgQCFZgWyAIVsBbzRgwCEeAUAhWRPIgphbHQAgywGAIFVFtGBAIdGDNGPAIc0HgCFQDMAYBuDAIhEBbsAh3cG0Y8Ahy0WPkJhY2tlbmQAhjYI0YDQvtGBINC90LAAgS4PAIhuIWFsdAoARwcAiBUFAIhtE9CjAIUoBbXRiACJAgUAghAQ0LUKZWxzZQAlIZ7RiNC40LEAhWsGAIEjB7XRgACEZAe1AIQMNtGLAIpdBbQAgy4GvgCJCwcAgy8HvtCxINC-AG4JtQoKZW5kAIEoBQCJYwa60LDQtyDQvtGCAIMpSgCJThme0YLQvACLTwWwAINUEmVuZACKejOhAIl-B77QuiDQsgCCSgWFAIxhCL7QsgoK&s=modern-blue)