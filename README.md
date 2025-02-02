# Проект: Задача предсказания статуса кредита

## Описание
Этот проект направлен на разработку модели, которая предсказывает вероятность дефолта клиента на основе данных о его личных характеристиках, финансовом положении и параметрах кредита. Основная цель — использовать предоставленные данные для создания точной и интерпретируемой модели.

---

## Структура проекта

- **`credit_risk.ipynb`**: Основной Jupyter Notebook с кодом, реализующим анализ данных, построение и оценку моделей.
- **`credit_risk_dataset.csv`**: Данные о клиентах.  
- **`README.md`**: Документация проекта.
- **`requirements.txt`**: Зависимости для запуска проекта.

---

## Установка и запуск

### Предварительные требования
- Python 3.9+
- Среда выполнения: Jupyter Notebook или аналогичная

### Установка зависимостей
1. Установите Python и виртуальную среду (рекомендуется).
2. Установите зависимости из `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```
---

## Основные шаги

1. **Импорт библиотек и подготовка данных:**
   - Используются библиотеки `pandas`, `matplotlib`, `seaborn` и `scikit-learn`.
   - Данные загружаются, предобрабатываются и исследуются для дальнейшего использования в моделях.

2. **Анализ данных:**
   - Исследовательский анализ данных (EDA), включая визуализацию распределений, проверку корреляций и обработку пропущенных значений.

3. **Построение моделей:**
   - Реализованы и протестированы следующие модели:
     - **Logistic Regression**
     - **KNeighborsClassifier**

4. **Оценка моделей:**
   - Основная метрика — **F1-score**, используемая для оценки качества классификации.
   - Результаты моделей сравниваются на основе их точности и метрик качества.

5. **Визуализация результатов:**
   - Используются `matplotlib` и `seaborn` для построения графиков и анализа предсказаний моделей.

---

## Зависимости

Основные библиотеки, используемые в проекте:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Все зависимости перечислены в `requirements.txt`.

---

## Автор
Максим Балашов

---

## Примечания
- Для достижения оптимальных результатов рекомендуется проводить дополнительный анализ данных и тестирование моделей.
- Среда выполнения — Jupyter Notebook, но код может быть легко адаптирован для других платформ (например, Google Colab или Kaggle).

