# Отчет о тестировании "Введение дополнительного бонуса новым клиентам"

## *Краткое описание*

Написан код приложения с дополнительным бонусом для привлечения новых клиентов банка, который должен суммироваться с регулярным бонусом.
При реализации Debugging в строке 6 отображается сумма, округленная в меньшее значение, чем ожидает новый клиент.

## *Описание теста*

На компонентном уровне было проведено функциональное тестирование. Был скопирован код, запущен и проведен Debugging

## *Результаты тестирования*
- Код запускается
- Сумма бонуса считается с округлением
- Ссылка на [Issues](https://github.com/Tageko/HW_J-2.2/issues/1#issue-806765328)

## *Общие рекоммендации* 
Проверить плавующую точку в исходных значениях регулярного бонуса и бонусы для новых клиентов, чтобы при суммировании результат был равен 0,9.
