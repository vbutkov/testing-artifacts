# testing-artifacts

### Домашнее задание

Составьте Матрицу соответствия требований для приложения “Калькулятор” — включите в неё минимум названия 4 требований и 4 названия тестовых сценария.

Сами требования (use cases) опишите коротко (1-2 параграфа) отдельно текстом.

```
| Требование   |  Тестовый сценарий 							   
|--------------|---------------------------------------------------------------------------|
| Сложение 1   | Ввести 2+2 и нажать кнопку "равно".  Ожидаемым результат 4. 		 
| Сложение 2   | Ввести 15+17 и нажать кнопку "равно".  Ожидаемым результат 32.    		   
| Сложение 3   | Ввести 0+0 и нажать кнопку "равно".  Ожидаемым результат 0.     		    
| Сложение 4   | Ввести -3+3 и нажать кнопку "равно". Ожидаемым результат 0.    		   
-------------------------------------------------------------------------------------------|
| Вычитание 1  | Ввести 8-5 и нажать кнопку "равно". Ожидаемым результат  3.                
| Вычитание 2  | Ввести 18-12 и нажать кнопку "равно". Ожидаемым результат 6.                
| Вычитание 3  | Ввести 0-0 и нажать кнопку "равно".  Ожидаемым результат  0.                
| Вычитание 4  | Ввести -5-3 и нажать кнопку "равно". Ожидаемым результат -8.                
-------------------------------------------------------------------------------------------|
| Умножение 1 | Ввести 3*4 и нажать кнопку "равно".  Ожидаемым результат  12.               
| Умножение 2 | Ввести 12*10 и нажать кнопку "равно".  Ожидаемым результат  120.
| Умножение 3 | Ввести 0*0 и нажать кнопку "равно". Ожидаемым результат  0.
| Умножение 4 | Ввести -5*10 и нажать кнопку "равно". Ожидаемым результат  -50.
-------------------------------------------------------------------------------------------|
| Деление 1   | Ввести 8/2 и нажать кнопку "равно". Ожидаемым результат 4.                 
| Деление 2   | Ввести 70/10 и нажать кнопку "равно". Ожидаемым результат 7.
| Деление 3   | Ввести 0/5 и нажать кнопку "равно". Ожидаемым результат 0.
| Деление 4   | Ввести -6/3 и нажать кнопку "равно". Ожидаемым результат -2.
-------------------------------------------------------------------------------------------|
```
```
| Требование | Описание требования 
Сложение 1. Тестовый сценарий сложения однозначных чисел.
Сложение 2. Тестовый сценарий сложения двузначных чисел.
Сложение 3. Тестовый сценарий сложения нулевых чисел.
Сложение 4. Тестовый сценарий сложения отрицательных чисел.

Вычитание 1. Тестовый сценарий вычитания однозначных чисел.
Вычитание 2. Тестовый сценарий вычитания двузначных чисел.
Вычитание 3. Тестовый сценарий вычитания нулевых чисел.
Вычитание 4. Тестовый сценарий вычитания отрицательных чисел.

Умножение 1. Тестовый сценарий умножения однозначных чисел.
Умножение 2. Тестовый сценарий умножения двузначных чисел.
Умножение 3. Тестовый сценарий умножения нулевых чисел.
Умножение 4. Тестовый сценарий умножения отрицательных чисел.

Деление 1. Тестовый сценарий деления однозначных чисел.
Деление 2. Тестовый сценарий деления двузначных чисел.
Деление 3. Тестовый сценарий деления нулевых чисел.
Деление 4. Тестовый сценарий деления отрицательных чисел.
```

Попробуйте составить небольшой текстовый документ с описанием требований для создания приложения “Калькулятор”, после чего проверьте данный документ на основе 5 критериев “Тестирования документации” — при необходимости внесите корректировки и уточнения в документ с требованиями.

## Требования для приложения "Калькулятор"

Требование 1: Базовые арифметические операции
Пользователь должен иметь возможность выполнить базовые арифметические операции, такие как сложение, вычитание, умножение и деление.

Требование 2: Ввод и вывод данных
Пользователь должен иметь возможность вводить числа и операторы с помощью интуитивного пользовательского интерфейса. Результат вычислений должен быть отображен на экране.

Требование 3: Обработка ошибок
Приложение должно обрабатывать ошибки ввода, такие как деление на ноль или некорректный формат числа, и сообщать пользователю о возникших ошибках.

Требование 4: Поддержка десятичных чисел
Пользователь должен иметь возможность вводить и получать результаты вычислений с десятичной точкой.

Требование 5: История вычислений
Приложение должно сохранять историю выполненных вычислений, чтобы пользователь мог просмотреть их позже или повторно выполнить

### Нефункциональные требования

1. Приложение должно быть разработано на платформе Android.
2. Приложение должно иметь привлекательный и интуитивно понятный пользовательский интерфейс.
3. Приложение должно быть стабильным и отзывчивым, не вызывать задержек или зависания.
4. Приложение должно быть легко масштабируемым и поддерживать добавление новых функций в будущем.
5. Приложение должно быть безопасным и защищенным от несанкционированного доступа или взлома.

Проверка требований на основе 5 критериев "Тестирование документации":

1. Четкость и ясность

Требование 2: Ввод и вывод данных
Пользователь должен иметь возможность вводить числа и операторы с помощью интуитивного пользовательского интерфейса. Результат вычислений должен быть отображен на экране.
Уточнение по требованию: 
Допустимые значения: от -999 999 999 999 999 до 999 999 999 999 999. 
Допустимые операторы: +, -, *, \.
Формат ввода чисел и операторов: вводится число, далее вводится оператор один из допустимых, далее вводится второе число.

Требование 5: История вычислений
Приложение должно сохранять историю выполненных вычислений, чтобы пользователь мог просмотреть их позже или повторно выполнить
Уточнения по требованию:
История не сохраняется после завершения работы приложения. В процессе работы приложения история ограничена. Максимальный размер истории 1МБ.

2. Актуальность
Документация актуальна.

3. Логика
Логика приложения проверена. Блок схема прилагается.

4.Возможные сценарии
Возможные сценарии описаны в матрице соответствия требований.
Неочевидные сценарии запрещены при использовании приложения. Разрешены только те варианты использования, которые описаны в функциональных требованиях.

5. Интеграции
Интеграция с другим сервисом\сервисами не предусмотрена.
