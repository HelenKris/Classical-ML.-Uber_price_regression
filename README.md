ПЕРЕД ЗАПУСКОМ Uber_price_regression.ipynb

1. Убедитесь, что читаете датасет из правильной директории
2. В ноутбуке используются библиотеки:
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- sklearn
  
Убедитесь, что они установлены в вашей среде выполнения

Uber_price_regression представляет собой задачу предсказания ценника для поездки в аггрегаторе такси Uber и Lyft.
В данной работе были проанализированы более 693000 наблюдений с целью создания модели, предсказывающей стоимость поездки. В результате анализа и обработки данных фактически значимыми оказались лишь 8 признаков из 55.
При работе наиболее информативной показала себя модель Extra Trees Regressor, ключевой параметр оценки R2 равен более 0,95, что свидетельствует о хорошей работе данной модели.
Работа была создана при помощи лаборатории Colab Google.
В репозитории находится ссылка на блокнот в лаборатории, а также отдельный файл ipynb c кодом данной работы.
