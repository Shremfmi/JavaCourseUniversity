## Лабораторна робота №3
 

### Мета

Основною метою цієї лабораторної роботи було зрозуміти принципи роботи з JUnit та Mockito та навчитися використовувати їх для написання розширених тестових випадків.

### Завдання

Створено базову систему електронної комерції з сутностями `Product`, `Cart` та `Order`. Система дозволяє користувачам додавати продукти до кошика, видаляти їх, робити замовлення та перевіряти статус замовлення.

### Вимоги до сутностей

#### `Product`:
- Атрибути: `id`, `name`, `price`.

#### `Cart`:
- Зберігає список продуктів.

#### `Order`:
- Атрибути: `orderId`, `products`, `status`.

### Функціональність

1. Додавання/видалення продуктів з кошика.
2. Розміщення замовлення з товарів у кошику.
3. Отримання статусу конкретного замовлення.

## [Тести до Лабораторної роботи №3]()


1. **Тестування додавання/видалення продуктів з кошика:**
   - Протестувати додавання продуктів до кошика.
   - Протестувати видалення продуктів з кошика.

2. **Тестування функціональності розміщення замовлення:**
   - Протестувати розміщення замовлення та перевірити, чи зберігається статус замовлення.

3. **Тестування функціональності отримання статусу замовлення:**
   - Протестувати правильність отримання статусу конкретного замовлення.

### Використання Mockito

Для тестування використовується Mockito для заміни залежностей та замокання поведінки методів.