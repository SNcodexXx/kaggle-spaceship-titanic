# Spaceship Titanic: Kaggle Competition

**Ссылка на соревнование:** [Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic)  
**Итоговый результат:** топ 15% (~273 место)

---

## Особенности проекта

Были добавлены следующие фичи:

- `total_spend`: сумма всех трат  
- `No_spending` / `Luxury_spend`: индикаторы нулевых трат (True/False) и объема ненулевых расходов  
- Заполнение части пропусков происходило исходя из групп пассажиров  

---

## Модели и подход

В итоговом стекинге использовались:

- RandomForest  
- CatBoost  

Добавление LightGBM, kNN и SVM не привело к существенному улучшению результата.

---

## Результаты

- Hold-out: **81.7%** accuracy, macro-F1 0.817
- Итоговый стекинг позволил достичь топ 15% среди участников  
- Результат на соревновании: 273 место

## Стек

`CatBoost` · `scikit-learn` · `pandas` · `NumPy`
