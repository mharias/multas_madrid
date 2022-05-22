# Multas publlicadas por el Ayuntamiento de Madrid, ejemplos de visualización de datos 
repositorio de código, datos y código de análisis de multas publicadas por Ayuntamiento Madrid

Esta es la estructura del proyecto : 

.  
├── code                  # Scripts en Python.    
├── img                   # ficheros con los gráficos generados.  
├── data                  # información descargada de la API del Ayuntamiento.  
└── README.md             # este fichero README.md

El directorio `data` no se guarda en este repo por el tamaño del fichero, superior al límite que marca github para subir ficheros.
De todas formas puede bajar los datos fácilmente con el código del apartado **"Bajamos los datos desde la API del Ayuntamiento"**

La información bajada se formatea en un dataframe [`panda`](https://pandas.pydata.org). Los gráficos se generan con las librerias de [`matplotlib`](https://matplotlib.org/stable/) y [`seaborn`](https://seaborn.pydata.org/#)

Durante la preparación de este trabajo he aprendido a utilizar el *chaining* en `pandas` por la claridad de lectura del código. Estoy intentando evitar en todo lo posible la replicación de pandas de gran tamaño que afecta mucho a la memoria del PC, con el resultado de progresiva lentitud en la ejecución del Notebook.
