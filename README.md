# Progect
Этот проект направлен на проведение комплексного анализа числовых данных с использованием различных методов статистики. Он включает в себя загрузку данных, разведывательный анализ, анализ пропусков и выбросов, а также различные методы проверки и подгонки распределений. Основной целью является извлечение полезной информации из набора данных и подготовка его для дальнейшего анализа и моделирования.
## Содержание
1. **Загрузка DataFrame**
   - Загрузка данных из файлов CSV и Excel.
2. **Разведывательный анализ (EDA)**
   - Визуализация и исследование основных характеристик данных.
   - Анализ графиков для выявления аномалий.
3. **Анализ пропусков данных**
   - Выявление и обработка пропусков в данных.
   - Различные стратегии для заполнения или удаления пропущенных значений.
   - Сохранение изменений в новый файл
4. **Анализ выбросов**
   - Выбор ряда данных для анализа.
   - Идентификация выбросов с помощью межквартильного размаха.
   - Визуализация результатов анализа.
   - Сохранение изменений в новый файл
5. **Проверка нормальности**
   - Выбор ряда данных для анализа.
   - Проведение теста Шапиро-Уилка  на соответствие распределения ряда нормальному.
   - Визуализация распределения данных с помощью гистограмм и QQ-графика.
6. **Подгонка данных под распределение**
   - Выбор рядя данных для анализа.
   - Подбор параметров для различных статистических распределений.
   - Визуализация распределения данных.
7. **Линейные корреляционный анализ и регрессия**
   - Описание процесса корреляционного анализа
   - Выбор рядов данных для анализа.
   - Вычисление коэффициентов корреляции и детерминации.
   - Получение уравнения регрессии.
   - Построение диаграммы рассеяния.
   - Вывод результатов анализа в отдельный файл.
8. **Определение корреляционного отношения**
   - Описание процесса определения корреляционного отношения между рядами данных
   - Выбор рядов данных для анализа
   - Анализ взаимосвязей между переменными.
   - Использование различных методов для оценки корреляции.
   - Вывод результатов анализа в отдельный файл.
9. **Дисперсионный анализ**
   - Описание процесса дисперсионного анализа
   - Проведение ANOVA для сравнения средних значений между группами.
   - Интерпретация результатов и визуализация.
10. **Планирование эксперимента**
    - Описание процесса DOE.
    - Проведение DOE.
    - Интерпретация результатов и визуализация.

## Установка зависимостей
Для запуска проекта необходимо установить следующие библиотеки:
- tkinter,
- pandas,
- scipy.stats,
- math,
- numpy,
- matplotlib,
- itertools,
- statsmodels,
- sweetviz,
- seaborn,
- os.

## Запуск проекта
Для начала работы запустите модуль main.
Внимание: для реализации пунктов 4 - 8 содержания, модуль main необходимо запускать из терминала: python main.py

## Лицензия
Этот проект лицензирован под MIT License.
