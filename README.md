# Project_3
необходимо исследовать влияние характеристик клиентов, которых страховая компания обслуживает, на размер страховых выплат

![DALL·E 2024-02-13](https://github.com/exelero565/Project_4/assets/97280394/d6d2a683-67ce-40b2-96b5-c539a322d1bd)

# Практика: Статистические Тесты в Контексте EDA (Исследовательский Анализ Данных)
## Постановка Задачи

Страховая компания обратилась за помощью к вам, опытному специалисту по данным, с задачей исследования влияния характеристик клиентов на размер годовых страховых выплат. Компания также хочет выявить другие взаимосвязи в данных.

Основные вопросы, на которые необходимо ответить:
- Больше ли страховые выплаты у мужчин по сравнению с женщинами?
- Меньше ли страховые выплаты у некурящих по сравнению с курящими?
- Влияет ли регион проживания на размер выплат?
- Существует ли взаимосвязь между курением и полом клиента?

Для ответов на эти вопросы будет использоваться уровень значимости $\alpha=0.05$.

Исследование основано на данных о годовых страховых выплатах с учетом характеристик клиентов.

## Загрузка Данных
Используемые библиотеки: pandas, numpy, scipy, statsmodels, matplotlib, seaborn.

Данные загружены с платформы Kaggle и доступны по [ссылке](https://www.kaggle.com/datasets/mirichoi0218/insurance/).

## Предварительная Обработка Данных
Выполнена очистка данных, обработка пропусков, создание новых признаков.

## Описательный Анализ Данных
Проведен анализ распределения страховых выплат в зависимости от различных характеристик клиентов: пола, курения, региона проживания. Выявлены основные тенденции и возможные аномалии.

## Статистический Анализ Данных
Применены различные статистические тесты для проверки гипотез о взаимосвязи характеристик клиентов со страховыми выплатами:
- Тест Шапиро-Уилка на нормальность распределения;
- U-критерий Манна-Уитни для сравнения двух независимых выборок;
- Критерий Краскела-Уоллиса для сравнения нескольких групп;
- Критерий хи-квадрат для анализа взаимосвязи между категориальными переменными.

## Выводы
- Не обнаружено статистически значимых различий в размере страховых выплат между мужчинами и женщинами.
- Выплаты для некурящих клиентов статистически меньше, чем для курящих.
- Регион проживания не влияет на размер страховых выплат.
- Найдена взаимосвязь между курением и полом клиентов.

Исследование показало важность учета курения при определении размера страховых выплат и выявило отсутствие дискриминации по полу и региону проживания в страховых выплатах.

## Автор
https://github.com/exelero565

## Лицензия
Проект распространяется под лицензией MIT. Вы можете свободно использовать и распространять этот код для личных и коммерческих целей с обязательной ссылкой на автора.
