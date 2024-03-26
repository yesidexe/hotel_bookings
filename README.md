# Hotel bookings
La idea de este "proyecto" práctico de **Machine learning** surgió en un bootcamp/curso de código facilito, el dataset a trabajar es uno que se encontró en kaggle, llamado [Hotel bookings](https://www.kaggle.com/datasets/mojtaba142/hotel-booking), es un problema de clasificación que vamos a resolver con Random Forest Classifier.

> 📢 Fue hecho con las mejores intenciones y esfuerzo, pero como tal no es un proyecto profesional, puede tener sus errores, y cositas a mejorar.

## **Contenido**
-  Data/...
    + `hotel_booking_clean.csv` dataset que genero en el notebook `hotel_bookings_EDA.ipynb`.
    + `hotel_booking_raw.csv` dataset crudo que se descarga en kaggle.
    + `hotel_booking_training.csv` dataset que proporciona **código facilito**, es un porcentaje del crudo.
    + `new_customers.csv` dataset que proporciona **código facilito** para probar el modelo, es el otro porcentaje del crudo.
- `df_profiling.html` es el reporte que generó **ydata_profiling** en el `hotel_bookings_EDA.ipynb`.
- `hotel_bookings_EDA.ipynb` es el notebook donde realizo algo de EDA con Feature engineering, y pruebo el modelo para dejarlo listo, y en el siguiente notebook solo usar pipelines y guardar el modelo.
- `hotel_bookings_pipeline.ipynb` notebook donde utilizó el dataset limpio `hotel_booking_clean.csv`, uso pipelines, guardo el modelo y lo pruebo.
- `modelo_pipeline.joblib` modelo que puede ser usado a producción. (aún no sé bien del tema, pero se supone que este modelo puede ser usado en producción)

## **Ambiente de desarrollo**
- [Python](https://www.python.org/)
- [VisualStudioCode](https://code.visualstudio.com/)

## **Librerias usadas**
- Pandas, Matplotlib, Seaborn, Numpy
- Scikit Learn
- joblib (Utilizada para guardar el modelo)
- [ydata_profiling](https://docs.profiling.ydata.ai/latest/) (Utilizada para el reporte de EDA)
- [optuna](https://optuna.org/#code_examples) (Utilizada para optimizar los parámetros del modelo)

## **Notas/Observaciones** 
#### *(Si están marcadas ya las resolví)*
- [ ] Que pasa si eliminaba `arrival_date_ear` en lugar de `reservation_status_date`??
- [ ] Entendí por qué en el bootcamp/curso `reservation_status` presentaba fuga de datos con el target, pero no por qué `reservation_status_date` lo presentaba.
- [ ] El one-hot-encoder sirve a las variables binarizadas??
- [ ] Que tal si uso cross validation?
- [ ] Cómo puedo crear un ColumnTransform con una funcion personalizada?



  
