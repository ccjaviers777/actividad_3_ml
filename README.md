Proyecto de Análisis de Obesidad

Este proyecto en python se centra en el análisis del conjunto de datos ObesityDataSet_raw_and_data_sinthetic.csv, el cual contiene información sintética sobre factores relacionados con la obesidad en individuos. La aplicación permite realizar operaciones de análisis básico y visualización de datos.

Descripción del conjunto de datos
El archivo ObesityDataSet_raw_and_data_sinthetic.csv incluye columnas que representan diferentes variables relacionadas con la obesidad, tales como:
- **Gender**: Género de la persona (`Male`, `Female`).
- **Age**: Edad de la persona en años.
- **Height**: Altura en metros.
- **Weight**: Peso en kilogramos.
- **family_history_with_overweight**: Indica si la persona tiene antecedentes familiares de sobrepeso (`yes`, `no`).
- **FAVC**: Indica si la persona consume alimentos con alto contenido calórico con frecuencia (`yes`, `no`).
- **FCVC**: Frecuencia de consumo de vegetales (escala de 0 a 3).
- **NCP**: Número de comidas principales que consume la persona en un día.
- **CAEC**: Frecuencia de consumo de comida entre comidas (`no`, `Sometimes`, `Frequently`, `Always`).
- **SMOKE**: Indica si la persona fuma (`yes`, `no`).
- **CH2O**: Cantidad de vasos de agua que consume la persona diariamente.
- **SCC**: Indica si la persona monitoriza sus calorías (`yes`, `no`).
- **FAF**: Frecuencia de actividad física semanal en horas.
- **TUE**: Tiempo de uso de dispositivos electrónicos en horas diarias.
- **CALC**: Frecuencia de consumo de alcohol (`no`, `Sometimes`, `Frequently`, `Always`).
- **MTRANS**: Medio de transporte principal (`Automobile`, `Motorbike`, `Bike`, `Walking`, `Public_Transportation`).
- **NObeyesdad**: Nivel de obesidad del individuo (clase objetivo: `Insufficient_Weight`, `Normal_Weight`, `Overweight_Level_I`, `Overweight_Level_II`, `Obesity_Type_I`,Obesity_Type_II`, `Obesity_Type_III`).

Este conjunto de datos es útil para construir modelos predictivos de obesidad y explorar patrones de hábitos que impactan la salud.

Funcionalidades del Proyecto
El proyecto permite realizar las siguientes tareas:
Carga de Datos: Cargar y leer los datos del archivo CSV en el entorno de Python para manipulación.
Análisis Estadístico: Calcular estadísticas descriptivas, tales como media, mediana y desviación estándar, para variables seleccionadas.
Visualización de Datos: Generar gráficos básicos que permiten observar patrones en los datos, como:
Distribución del IMC
Comparación de hábitos de actividad física vs. obesidad
- **Clasificación**: Predicción del nivel de obesidad basado en los factores proporcionados.
- **Clustering**: Segmentación de personas en grupos basados en sus hábitos y características.
- **Análisis Exploratorio de Datos (EDA)**: Estudio de patrones en los hábitos de alimentación y actividad física.

Configuración del Entorno.
Instalación
Clonar el repositorio:
Abrir el proyecto en Visual Studio code: Navega hasta la carpeta del cauderno y abre el archivo evaluacion_datos_sobre_obesidad.ipynb en Python.
Agregar el archivo CSV: Coloca el archivo ObesityDataSet_raw_and_data_sinthetic.csv en la carpeta de datos del proyecto o en la misma ubicación del código fuente.
Configurar las rutas de los archivos: Asegúrate de que la ruta en el código coincida con la ubicación real del archivo CSV. Modifica el código si es necesario.
Estructura del Proyecto
Cuadernos: Contiene módulos para cargar y procesar datos.
Datos: Carpeta donde se almacena el archivo ObesityDataSet_raw_and_data_sinthetic.csv.

Uso
Ejecuta el proyecto en Visual Studio code.
bashCopy codegit clone https://github.com/ccjaviers777/actividad_3_ml/