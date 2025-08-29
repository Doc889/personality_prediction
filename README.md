<h1>Прогноз типа личности человека</h1>

<h3>Цель:</h3>
Применение алгоритмов машинного обучения с целью прогнозирования, является ли человек интровертом или экстравертом.
<br>
<br>
Датасет был взят с сайта Kaggle.<br>
URL: https://www.kaggle.com/competitions/playground-series-s5e7

<h3>Признаки</h3>

В качестве признаков выступают:
- Время, проведенное в одиночестве
- Страх перед выступлением
- Посещение социальных мероприятий
- Выход на улицу
- Показатель истощения после общения
- Круг друзей
- Частота создания постов в социальных сетях

<h3>Гистограммы предикторов и зависимой переменной</h3>
<img width="627" height="613" alt="image" src="https://github.com/user-attachments/assets/75989a78-9e07-4d65-b008-ce2d7a1129bb" />


<h3>Примененные алгоритмы</h3>  

Примененные алгоритмы машинного обучения с их показателями оценки эффективности:
- Random Forest Classifier:
<img width="481" height="144" alt="image" src="https://github.com/user-attachments/assets/f4825e8c-67a0-4cb4-82d1-17247d7f8c23" />

- Logistic Regression
<img width="477" height="147" alt="image" src="https://github.com/user-attachments/assets/068f0a28-f91b-4da0-bd06-ff0ac152e9da" />

- XGBClassifier
<img width="459" height="149" alt="image" src="https://github.com/user-attachments/assets/a62a5fb7-c93f-439b-beb0-9322db40c5cc" />

<h3>Вывод:</h3>
Примененные алгоритмы машинного обучения показывают приблизительно одинаковые результаты. Однако алгоритмы Random Forest Classifier и XGBClassifier показали результат лучше по метрике recall по сравнению с Logistic Regression.

