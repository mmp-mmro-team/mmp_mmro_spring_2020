# Семинары по машинному обучению для бакалавров 3 курса кафедры ММП и магистров 1 курса кафедр ИИТ и МФ факультета ВМК МГУ, весенний семестр 2019/2020
В репозитории находятся материалы и домашние задания по семинарам "ММРО 2019/2020"

<p align="center">
  <b>!!!ВНИМАНИЕ! СЕМИНАРЫ С 17 МАРТА ПРОВОДЯТСЯ ОНЛАЙН!!!</b>
</p>

<p align="center">
<img src="http://funzoo.ru/uploads/posts/2009-11/1258648863_tn.jpg" height=200pt> <img src="https://github.com/mmp-mmro-team/mmp_mmro_spring_2020/blob/master/trash/kernel_trick.jpg" height=200pt>
</p>

**Курс сдается через систему [anytask](https://anytask.org/course/668)**

На семинары и работу ассистентов можно оставить отзыв: [[анонимно без регистрации и смс](https://docs.google.com/forms/d/e/1FAIpQLSf_wnrm52RfnHkqZPbsWOpjzd9Uelwq5Jk0elZYGH2p-vQyaw/viewform)]

**Полезные ссылки:**

* Материалы прошлых лет:
  - [Раз](https://github.com/esokolov/ml-course-msu)
  - [Два](https://github.com/esokolov/ml-course-hse)
* [Курс лекций по ММРО](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D1%80%D0%B0%D1%81%D0%BF%D0%BE%D0%B7%D0%BD%D0%B0%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F_%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%92.%D0%92.%D0%9A%D0%B8%D1%82%D0%BE%D0%B2%29)
* [Курс Практикума на ЭВМ, осень](https://github.com/mmp-practicum-team/mmp_practicum_fall_2019)
* [Курс ММРО 19/20, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2019)

## Правила выставления оценок

Общая оценка выставляется по следующей формуле:
![](https://github.com/mmp-mmro-team/mmp_mmro_spring_2020/blob/master/trash/formula.png)
, где 

* Check --- 5 * <сумма баллов за проверочные> / <суммарный макс балл за проверочные>
* Labs --- min(5, 5 * <сумма баллов за лабораторные + конкурсы> / <суммарный макс балл за лабораторные (без бонусов и конкурсов)>
* Exam --- оценка за экзамен, до 5 баллов

Причем
* Для общей оценки 5 необходимо сдать **все** лабораторные работы на оценку >= 3 **и** получить за эказамен не меньше 4
* Для общей оценки 4 необходимо сдать **не менее 3-х** лабораторных работ на оценку >= 3 **и** получить за экзамен не меньше 3
* Для общей оценки 3 необходимо получить за экзамен не меньше 3

Обратите внимание, что округление общей оценки (и только ее) производится вверх.
## Занятия

| Дата | Номер | Тема | Материалы | ДЗ |
| :---: | :---: | --- | --- | --- |
| 13 февраля  | Семинар 1  | <ul><li>Имплементации градиентного бустинга</li><li>Блендинг</li><li>Важность признаков: OOB и FSTR</li><li>Интерпретация алгоритмов: LIME</li></ul> | [Ноутбук с кодом семинара (прошлогодний, с опечатками)](https://github.com/esokolov/ml-course-hse/blob/master/2019-fall/seminars/sem10-gbm.ipynb) | ¯\\\_(ツ)\_/¯ |
| 20 февраля  | Семинар 2  | <ul><li>Байесовские методы машинного обучения</li><li>Оптимальные байесовские правила:<ol><li>Для классификации</li><li>Для регрессии</li></ol></li><li>Наивный байесовский классификатор</li></ul> | <ul><li>[PDF с семинаром (все, кроме оптимального байесовского правила для регресси)](https://github.com/mmp-mmro-team/mmp_mmro_spring_2020/blob/master/seminars/sem2-bayes.pdf)</li><li>[PDF с оптимальным байесовским правилом для регресси (§2.1)](https://github.com/mmp-mmro-team/mmp_mmro_spring_2020/blob/master/seminars/sem2.5-ensembles.pdf) </li></ul> | ¯\\\_(ツ)\_/¯ |
| 27 февраля  | Семинар 3  | <ul><li>Метод главных компонент, обсуждение методов отбора признаков</li></ul> | <ul><li>[Ноутбук с кодом семинара 1](https://colab.research.google.com/drive/1N5jvNGNibBSgLBrCPRV6NbXxvCAYsQI7)</li><li>[Ноутбук 2](https://github.com/esokolov/ml-course-hse/blob/master/2019-fall/seminars/sem11_clustering%2Bpca.ipynb)</li></ul> | ¯\\\_(ツ)\_/¯ |
| 5 марта  | Семинар 4  | <ul><li>Вывод линейного дискриминанта Фишера</li><li>Ядровой метод главных компонент</li></ul> | <ul><li>[Лекция раз](https://github.com/esokolov/ml-course-hse/blob/master/2017-spring/seminars/sem15-fld.pdf)</li><li>[Лекция два](https://github.com/esokolov/ml-course-hse/blob/master/2017-spring/lecture-notes/lecture16-kernels.pdf)</li></ul>| ¯\\\_(ツ)\_/¯ |
| 12 марта  | Семинар 5  | <ul><li>Аппроксимация ядер</li><li>Ядра для строк</li></ul> | [Лекция, секции 1-2](https://github.com/esokolov/ml-course-hse/blob/master/2018-spring/lecture-notes/lecture14-kernels.pdf)| [ДЗ 1](homework-practice/homework-practice-01.ipynb)|
| 19 марта  | Семинар 6  | <ul><li>EM алгоритм</li><li>Разделение смеси нормальных распределений</li></ul> | <ul><li>[Материалы семинара](https://github.com/mmp-mmro-team/mmp_mmro_spring_2020/blob/master/seminars/sem6-em.pdf)</li><li>[Матричное дифференцирование](https://github.com/mmp-mmro-team/mmp_mmro_spring_2020/blob/master/seminars/sem6.5-matrix_differentiation.pdf)</li></ul>| ¯\\\_(ツ)\_/¯ |
