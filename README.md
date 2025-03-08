Hola a todos, este es mi primer proyecto de ML. En esta ocasión entreno un modelo de regresión lineal múltiple relacionado a las calificaciones de estudiantes.
El proyecto está totalmente en español, para que cualquier persona de la comunidad que esté interesada lo analize, estudie y recomiende cambios en el algoritmo con el fin de optimizar su precisión.

Una breve explicación de los módulos:

Limpieza_Estudiantes: Recibe como entrada el data set orginal descargado de: https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression/code y en base a análisis de datos, correlación, colinealidad y multicolinealidad entre estos, regresa los datos que se considere escenciales para entrenar al algoritmo.

Entrnamiento_Estudiantes: Recibe como entrada el data set de sálida del módulo Limpieza_Estudiantes, para poder entrenar al modelo de regresión lineal para posteriormente evaluarlo mediante métricas de error y diagramas de comparativa.
