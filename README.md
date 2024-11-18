# Анализ метрики Churn rate/ Выявление взаимосвязи
## Цели проекта:
+ Провести анализ предоставленных данных
+ Ответить на следующие вопросы:
1. Проверить, может ли быть связана исследуемая метрика с операционной системой, с которой работают водители
2. Проверить, есть ли различия в размерах оттока клиентов в разных городах
3. Проверить, есть ли разница в активности в первые 30 дней с момента регистрации между водителями из разных городов?
4. Проверить может ли отток быть связан с активностью в первые 30 дней после регистрации?

## В работе использован следующий стек:  
  <a href="https://jupiter.org/" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/640px-Jupyter_logo.svg.png" width="36" height="36" alt="jupiter-notebook" /></a>
  <a href="https://pandas.org/" target="_blank" rel="noreferrer"><img src="https://i.pinimg.com/originals/ce/6e/14/ce6e14ee46d262be29c3efef8cd2e86d.png" width="80" height="36" alt="pandas" /></a>
  <a href="https://seaborn.org/" target="_blank" rel="noreferrer"><img src="https://habrastorage.org/getpro/habr/upload_files/6c6/887/78d/6c688778d9df0ab8413b0fe1f65b33bb.png" width="80" height="36" alt="seaborn" /></a>
  <a href="https://scipy.org/" target="_blank" rel="noreferrer"><img src="https://kinsta.com/wp-content/uploads/2023/04/scipy-1024x445.jpg" width="80" height="36" alt="scipy" /></a>
  <a href="https://pingouin-stats.org/build/html/index.html" target="_blank" rel="noreferrer"><img src="https://pingouin-stats.org/build/html/_images/logo_pingouin.png" width="90" height="33" alt="pingouin" /></a>
  <a href="https://plotly.com/python/" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/8/8a/Plotly-logo.png" width="100" height="36" alt="plotly" /></a>


## Применялись следующие подходы:
+ Критерий Левена
+ Критерий Мана-Уитни
+ Критерий Геймса-Хоувелла
+ Критерий Хи-квадрат

## В ходе проекта мной было сделано:
+ Произведена проверка качества данных (пропущенные значения, количество строк, формат данных)
+ Предобработка данных в датафрейме (очистка от дубликатов и лишних значений)
+ Построена таблица сопряженности
+ Проверена и выявлена зависимость исследуемой метрики  с операционной системой, с которой работают водители 
+ Проверена и выявлена зависимость исследуемой метрики  от города
+ Проверена и выявлена зависимость исследуемой метрики  с активностью в первые 30 дней после регистрации 

#### Результат работы: получены ответы на все интересующие заказчика вопросы

Ознакомиться с файлом решения [тут](https://github.com/ncherniy/Prj-3_A-B_test_TaxiService/blob/main/churn_rate_taxi.ipynb)

--------------------
