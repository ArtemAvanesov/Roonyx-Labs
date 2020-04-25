﻿# Лабораторные работы Roonyx
 
 Здесь представлены решения лабораторных задач:
 1) В качестве практического задания нужно на выбранном датасете:
   - Провести первичный анализ данных, пользуясь первой статьей серии в качестве руководства. Полученные инсайты пригодятся дальше в ходе выполнения;
   - Применить инструменты визуализации к данным, пользуясь второй статьей серии в качестве руководства (использовать разные типы графиков);
   - Провести feature engineering - из некоторых имеющихся признаков вывести один-два новых, которые можно будет использовать в дальнейшем при анализе или обучении (примеры есть в интернете);
   - Вывести одну-две гипотезы относительно целевой переменной - что и как на неё больше всего влияет и т.д. - можно текстом в джупитер ноутбуке (примеры также можно найти в интернете).

При выполнении практических заданий при написании текста используем исключительно английский язык. Статьи:[статьи](https://habr.com/ru/company/ods/blog/322626/ "Статьи на habr") 

 2) Разделить с помощью scikit-learn свои данные на тренировочную и тестовую выборки. Обучить и протестировать на своих датасетах следующие модели из библиотеки scikit-learn:
   - Дерево решений;
   - Логистическая регрессия;
   - Линейная регрессия;
   - KNN;
   - Случайный лес;
   - Градиентный бустинг.
  
Если данные предполагают решение задачи регрессии, то для того, чтобы обучить модели классификации нужно поделить свою переменную на 2 или более классов. И наоборот, если данные для классификации, можно сделать их подходящими для моделей регрессии. После обучения и тестирования нужно сравнить результаты моделей, отсортировав их по accuracy на тестовой выборке.
