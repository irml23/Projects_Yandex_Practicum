# Проект «Выбор локации для скважины»
## Описание 
Допустим, вы работаете в добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину. 
Шаги для выбора локации обычно такие:
- В избранном регионе собирают характеристики для скважин: качество нефти и объём её запасов;
- Строят модель для предсказания объёма запасов в новых скважинах;
- Выбирают скважины с самыми высокими оценками значений;
- Определяют регион с максимальной суммарной прибылью отобранных скважин.

Вам предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Постройте модель для определения региона, где добыча принесёт наибольшую прибыль. Проанализируйте возможную прибыль и риски техникой Bootstrap.
## Цель
Построить модель для определения региона, где добыча принесёт наибольшую прибыль; проанализировать возможную прибыль и риски техникой Bootstrap.
## Инструменты
- pandas
- numpy
- matplotlib
- sklearn
## Итоговый вывод
Первый и третий регионы обладают достаточно высоким процентом риска и имеют отрицательное значение прибыли на левой границе доверительного интервала, следовательно они не подходят под условия нашей задачи. **Второй регион** обладает процентом риска всего 1%, что подходит под условия нашей задачи; также обладает положительной левой границей и самым высоким средним доходом из трех регионов. Следовательно для разработки нового месторождения лучшим регионом из трех будет второй регион.
