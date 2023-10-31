# Задание
Создайте программу на Python или Java, которая принимает два списка чисел и выполняет следующие действия:
a. Рассчитывает среднее значение каждого списка.
b. Сравнивает эти средние значения и выводит соответствующее сообщение:
- ""Первый список имеет большее среднее значение"", если среднее значение первого списка больше.
- ""Второй список имеет большее среднее значение"", если среднее значение второго списка больше.
- ""Средние значения равны"", если средние значения списков равны.

Важно:
Приложение должно быть написано в соответствии с принципами объектно-ориентированного программирования.
Используйте Pytest (для Python) или JUnit (для Java) для написания тестов, которые проверяют правильность работы программы. Тесты должны учитывать различные сценарии использования вашего приложения.
Используйте pylint (для Python) или Checkstyle (для Java) для проверки качества кода.
Сгенерируйте отчет о покрытии кода тестами. Ваша цель - достичь минимум 90% покрытия.

*Формат и требования к сдаче: *
Отчет о выполнении этого задания должен включать в себя следующие элементы:
- Код программы
- Код тестов
- Отчет pylint/Checkstyle
- Отчет о покрытии тестами
- Объяснение того, какие сценарии покрыты тестами и почему вы выбрали именно эти сценарии.

## Отчет pylint
![](/pylint.png)

## Отчет о покрытии тестами
![](/total.png)

## Пояснения к выбору покрытия

В этой программе я выбрал следующие сценарии для тестирования:

1. `test_calculate_average_with_non_empty_list`: проверяет, что метод `calculate_average` правильно рассчитывает среднее значение для непустого списка.
2. `test_calculate_average_with_empty_list`: проверяет, что метод `calculate_average` возвращает `None`, если список пуст.
3. `test_compare_lists_with_higher_average_in_first_list`: проверяет, что метод `compare_lists` корректно сравнивает средние значения и выводит сообщение, что первый список имеет большее среднее значение.
4. `test_compare_lists_with_higher_average_in_second_list`: проверяет, что метод `compare_lists` корректно сравнивает средние значения и выводит сообщение, что второй список имеет большее среднее значение.
5. `test_compare_lists_with_equal_averages`: проверяет, что метод `compare_lists` корректно сравнивает средние значения и выводит сообщение, что средние значения списков равны.