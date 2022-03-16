# 2022_Molnet_Hackathon

English:

Our case: Database programming
Task: Develop a mechanism that will map multiple database tables to fields of a single Java POJO and
will build a where-clause of the SQL query based on the values and data types of the fields.
Solution: People who knew how to program in Java immediately dropped out of the project, so we had to solve the task in Python (which everyone knew). Of course, 
we didn't win anything with this solution, but I'm happy that we did present the solution and the rest of the team did a good job. The Patient db toy database 
is based on real, published genetic data.

*****

The Patient db management program is designed to simplify work with patient genomic data.
It is assumed that there is a database that contains genomic rearrangements of the following format: Xq28(123455-123456), along with patient age and sex, 
and dates of sample collection and and analysis being ready.

How to use:

Enter the value of the chromosome of interest (1 -- 22, X, Y) and the patient's age. If only one value is entered (chromosome or age), the second value will be searched without restrictions. To perform a search, click the "Find" button.

As a result, you will get a list that displays the following values from the table:

Patient number in the journal;
Age (years);
The value of the chromosomal rearrangement (chromosome, location, coordinates, copy number) and the type of rearrangement.

For the results obtained, one can check out how long it took for the analysis to be prepared.

Then one can either perform a new search or exit the program.

Russian:

Наш кейс: Программирование базы данных
Задание: Разработать механизм, который сопоставит множество таблиц баз данных полям единственного Java POJO и 
построит where-clause SQL-запроса на основании значений и типов данных полей.
Решение: Люди, которые умели программировать на Java, у нас сразу выпали из проекта, поэтому пришлось решать все на Python (который все знали). Конечно, с таким решением мы ничего не выиграли, но я довольна тем, что мы все-таки представили решение и у оставшейся команды вышло неплохо поработать. В основе игрушечной базы данных Patient db лежат реальные, опубликованные генетические данные.

*****

Программа Patient db management предназначена для упрощения работы с геномными данными пациентов. 
Предполагается наличие базы данных, в которой содержатся геномные перестройки формата Xq28(123455-123456), возраст и пол пациента и даты забора и готовности образцов.

Как пользоваться:

Введите в программное окно значение интересующей хромосомы (1 -- 22, X, Y) и возраст пациента. В случае ввода только одного значения (хромосомы или возраста), для второго значения поиск будет производиться без ограничений. Для выполнения поиска нажмите кнопку "Найти".

В результате вы получите список, который отображает следующие значения из таблицы:

Номер пациента в журнале;
Возраст (лет);
Значение хромосомной перестройки формата (хромосома, участок в хромосоме, координаты в ДНК по нуклеотидам, количество копий участка) и тип перестройки.

Для полученных результатов можно узнать, сколько по времени готовился анализ.

Далее можно либо выполнить новый поиск, либо завершить программу.

Спасибо за использование программы Patient db management команды Mental!
