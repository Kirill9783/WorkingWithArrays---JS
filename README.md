Задача 1
Цель задания
Научиться выполнять поиск элементов в массиве и показывать результат в списке DOM-элементов.

Что нужно сделать
Создайте папку проекта «Задача 1»с файлами:
index.html;
index.js;
style.css.
В файле index.html создайте базовую HTML-разметку, подключите файл скрипта и файл CSS-стилей.
Создайте веб-приложение «Домашняя библиотека»со следующим функционалом:
На странице должен выводиться список книг библиотеки из массива.
Предусмотрите возможность добавления новой книги в массив. Для этого создайте кнопку «Добавить книгу». Ввод названия книги осуществляется в окне prompt(), которое отображается при клике на кнопку добавления. Перед добавлением книги в массив обязательно сделайте проверку ввода. Если пользователь ничего не ввёл, покажите alert() с сообщением: «Название книги не введено!» 
Для поиска книги в списке создайте кнопку «Поиск», при клике на которую отображается окно ввода prompt() c вводом названия для поиска. Найденная книга в списке должна быть выделена цветом. Если книга не найдена, покажите alert() с сообщением: «Книга не найдена!»
Выполните минимальную CSS-стилизацию DOM-элементов.

Задача 2
Цель задания
Научиться выполнять фильтрацию чисел в массиве и показывать обновлённый результат в списке DOM-элементов.

Что нужно сделать
Создайте папку проекта «Задача 2»с файлами:
index.html;
index.js;
style.css.
В файле index.html создайте базовую HTML-разметку, подключите файл скрипта и файл CSS-стилей.
Создайте веб-приложение «Рост учеников»со следующим функционалом:
На странице из массива должен выводиться список чисел, которые определяют рост каждого ученика.
Предусмотрите возможность добавления нового числа (роста ученика) в массив. Для этого создайте кнопку «Добавить рост». Ввод числа осуществляется в окне prompt(), которое отображается при клике на кнопку добавления. Перед добавлением роста в массив обязательно сделайте проверку ввода. Если пользователь ничего не ввёл, покажите alert() с сообщением: «Рост не введён!»
Для фильтрации чисел в массиве по  минимальному значению создайте кнопку «Фильтровать», при клике на которую отображается окно ввода prompt() c вводом числа. Список роста должен быть перерисован в DOM-дереве. Если пользователь ничего не ввёл, покажите весь список без учёта фильтрации.
Выполните минимальную CSS-стилизацию DOM-элементов.

Задача 3
Цель задания
Научиться выполнять сортировку элементов в массиве и показывать результат в списке DOM-элементов.

Что нужно сделать
Создайте папку проекта «Задача 3»с файлами:
index.html;
index.js;
style.css.
В файле index.html создайте базовую HTML-разметку, подключите файл скрипта и файл CSS-стилей.
Создайте веб-приложение «Корзина покупателя»со следующим функционалом:
На странице из массива должен выводиться отсортированный по возрастанию список товаров.
Предусмотрите возможность добавления нового товара в массив. Для этого создайте кнопку «Добавить товар». Ввод названия осуществляется в окне prompt(), которое отображается при клике на кнопку добавления. Перед добавлением товара в массив обязательно сделайте проверку ввода. Если пользователь ничего не ввёл, покажите alert() с сообщением: «Название товара не введено!»
После добавления нового товара список должен обновиться в DOM-дереве в отсортированном виде по возрастанию.
Подсказка:в JavaScript доступна возможность сравнения строк. Это работает так же, как и с числами. Пример:
if ("Яблоко" > "Арбуз"){
 console.log("Яблоко больше Арбуз")
}
При сравнении строк происходит сравнение каждого отдельного символа. В этом примере символ «Я» больше символа «А», поэтому строка «Яблоко» больше, чем «Арбуз». Подробнее о сравнении строк рассказано в материале «Операторы сравнения».

Выполните минимальную CSS-стилизацию DOM-элементов.
