# Проект «Определение успешности компьютерной игры»
## Описание 
Вы работаете в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Вам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.
## Цель
Необходимо выявить определяющие успешность игры закономерности, что позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.
## План
1. Изучение данных
2. Подготовка данных
3. Исследовательский анализ данных
4. Составление портрета пользователя каждого региона
5. Проверка гипотез
## Инструменты
- Pandas
- numpy
- scipy
- seaborn
- matplotlib
- EDA
- Feature engineering
## Итоговый вывод
<b>Шаг 1. Открытие файла с данными и изучение общей информации</b>
<br>
Данные были успешно загружены, никаких проблем не возникло. Дана предварительная оценка данных: в некоторых столбцах присутсвуют пропуски и столбцы неправильно названы.
<br><br>

<b>Шаг 2. Подготовка данных</b>
<br>
Переименовали названия столбцов в соответствии с правилами. Преобразовали данные в нужные типы. Обработали пропуски в некоторых столбцах. Добавили столбец с суммарными продажами во всех регионах.
<br><br>

<b>Шаг 3. Исследовательский анализ данных</b>
<br>
Данные не за все периоды важны для нашей цели. По продажам лидирует платформа PS4. Все платформы постепенно падают по продажам. Растущих платформ нет. PC - стабильная платформа. Потенциально прибыльные платформы - PS4, XOne, 3DS, PC. По графику "ящык с усами" можно сказать следующее: разницы между графиками по каждой платформе почти нет. Они демонстрируют похожие продажи. Средние же продажи очень сильно отличаются, поскольку почти в каждом графике присутсвуют выбросы (продажи очень популярных игр). Высокий рейтинг далеко не всегда означает большие продажи, а низкий рейтинг почти всегда обозначает низкий уровень продаж. Слабо отрицательная связь на графике с оценками пользователей и умеренно положительная связь на графике с оценками критиков. Самые высокие продажи у жанров Shooter, Sports и Platform. Самые низкие продажи у жанров Strategy, Puzzle, Adventure.
<br><br>

<b>Шаг 4. Портрет пользователя каждого региона</b>
<br>
- NA: самая популрная платформа - XOne, самый популярный жанр - Shooter.
- EU: самая популрная платформа - PS4, самый популярный жанр - Shooter.
- JP: самая популрная платформа - 3DS, самый популярный жанр - Role-Playing.
<br><br>

<b>Шаг 5. Проверка гипотез</b>
<br>
В ходе проверки обе гипотезы потдвердились:
1. Средние пользовательские рейтинги платформ Xbox One и PC одинаковые <br>
2. Средние пользовательские рейтинги жанров Action (англ. «действие», экшен-игры) и Sports (англ. «спортивные соревнования») разные
<br><br>


