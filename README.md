# Проект: Исследование банковских данных для предсказания депозита клиентов

## Описание проекта
Данный проект основан на исследовании данных банка с целью предсказания того, откроют ли клиенты депозит. Исследование включает в себя анализ различных характеристик клиентов и информации о предыдущих маркетинговых кампаниях.

```bash
git clone https://github.com/AlexanderGithubProfile/SCORING.git
```
## Структура репозитория
1. **01_preprocessing**: В этой части производится предобработка данных, включая анализ пропусков, выбросов, баланса выборки, а также обработка категориальных признаков и корреляционный анализ.
2. **02_model**: В этой части проекта выполняется построение и обучение различных моделей машинного обучения для предсказания депозита клиентов. Включает в себя разделение выборки на тренировочную и тестовую, обучение моделей, сравнение метрик и поиск оптимальных параметров.
3. **data**: В этой папке хранится файл с данными и экспорт файлами `banking.csv`.
3. **README.md**: Этот файл содержит общее описание проекта и инструкции по его запуску.

## Используемые библиотеки
- [**pandas**](https://pandas.pydata.org/): Библиотека для работы с данными, предоставляющая удобные инструменты для обработки и анализа табличных данных.
- [**numpy**](https://numpy.org/): Библиотека для работы с многомерными массивами данных и математическими операциями над ними.
- [**sklearn**](https://scikit-learn.org/stable/): Библиотека машинного обучения, предоставляющая реализации множества алгоритмов обучения с учителем и без учителя, а также инструменты для предобработки данных и оценки моделей.
- [**matplotlib**](https://matplotlib.org/): Библиотека для создания различных типов графиков и визуализации данных в Python.
- [**seaborn**](https://seaborn.pydata.org/): Библиотека для визуализации данных на основе matplotlib, предоставляющая более высокоуровневый интерфейс для создания статистических графиков.
- [**xgboost**](https://xgboost.readthedocs.io/en/latest/): Библиотека для градиентного бустинга, оптимизированная для скорости и производительности, использующаяся в задачах классификации и регрессии.
- [**lightgbm**](https://lightgbm.readthedocs.io/en/latest/): Библиотека для градиентного бустинга, также оптимизированная для скорости и производительности, часто используемая в задачах классификации и регрессии.


## Рассмотренные гипотезы:
1. Комбинация длительности последнего звонка и количества звонков в течение маркетинговой кампании.
2. Комбинация банковской ставки и индекса потребительских цен.
3. Гипотеза о сегментации возраста клиента.
4. Гипотеза о влиянии образования клиента.
5. Комбинации возраста и образования.
6. Влияние выгодных ставок и низкой безработицы на интерес к открытию вкладов.
7. Гипотеза о влиянии образования и наличия жилищного кредита на решение о депозите.

## Сделанные модели:
В разделе 02_model выполнены следующие шаги:
- Обучение моделей: логистическая регрессия, случайный лес, XGBoost, градиентный бустинг, LightGBM, нейронная сеть, линейный дискриминантный анализ, метод опорных векторов, наивный байесовский классификатор, метод ближайших соседей.
- Сравнение метрик моделей.
- Поиск оптимальных параметров моделей.
- Анализ важности признаков.

## Запуск проекта
Чтобы запустить проект, выполните следующие шаги:
1. Склонируйте репозиторий на свой компьютер.
2. Установите необходимые библиотеки, указанные в файле `requirements.txt`.
3. Откройте Jupyter Notebook из папки `notebooks`.
4. Запустите файлы Jupyter Notebook с кодом исследования.


