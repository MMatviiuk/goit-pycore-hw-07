# Проект: Асистент для роботи з контактами

## Функціонал

1. **Контакти**
   - `add [ім'я] [телефон]` - Додає новий контакт або додає телефон до існуючого контакту.
   - `change [ім'я] [старий телефон] [новий телефон]` - Змінює телефон для вказаного контакту.
   - `phone [ім'я]` - Показує телефони контакту.
   - `all` - Показує всі контакти.

2. **Дні народження**
   - `add-birthday [ім'я] [дата народження]` - Додає дату народження контакту (формат: DD.MM.YYYY).
   - `show-birthday [ім'я]` - Показує дату народження контакту.
   - `birthdays` - Показує дні народження контактів, які будуть протягом тижня.

3. **Команди для взаємодії**
   - `hello` - Вітання від бота.
   - `close` або `exit` - Закриття програми.

## Як запустити

1. Імпортуйте клас `AddressBook` для роботи з контактами.
2. Використовуйте функцію `main()` для запуску асистента.

   ## Оцінка виконання

1. Реалізуйте всі вказані команди.
2. Дані мають виводитися в зрозумілому форматі.
3. Обробка помилок (наприклад, неправильний ввід чи відсутність контакту).
4. Валідація даних:
   - Дата народження: формат DD.MM.YYYY.
   - Телефон: 10 цифр.
5. Коректне закриття програми після команд `close` або `exit`.
