В программе определенна структура о следующими полями: имя, фамилия, день, месяц и год рождения.
Ввод:
 - Первая строка содержит одно целое число N от 0 до 10000 — число студентов.
 - Далее идут N строк, каждая из которых содержит две строки длиной от 1 до 15 символов — имя и фамилию очередного студента, и три целых числа от 0 до 1000000000 — день, месяц и год рождения.
 - Следующая строка содержит одно целое число M от 0 до 10000 — число запросов.
 - Следующие M строк содержат строку длиной от 1 до 15 символов — запрос, и целое число от 1 до 1000000000 — номер студента (нумерация начинается с 1).
Вывод:
 - Для запроса вида name K, где K от 1 до N, вывод через пробел имя и фамилию K-го студента.
 - Для запроса вида date K, где K от 1 до N, вывод через точку день, месяц и год рождения K-го студента.
 - Для остальных запросов вывод bad request.