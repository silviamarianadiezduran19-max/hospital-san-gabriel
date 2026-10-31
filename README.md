# hospital-san-gabriel
Presentación trabajo de informática con los datos de 20 pacientes en Excel
HOSPITAL SAN GABRIEL

Proyecto de organización y análisis de registros clínicos sin estructurar

Descripción del proyecto

El presente proyecto académico tiene como finalidad organizar, estructurar y analizar 20 registros clínicos ficticios del Hospital San Gabriel. Los registros fueron recibidos inicialmente en formatos de texto sin estructurar, con diferentes abreviaturas, formatos de fechas y formas de registrar la información. A partir de estos datos se desarrolló un proceso de transformación y limpieza para convertir la información en una base de datos organizada, facilitando su consulta, procesamiento e interpretación estadística.

Objetivo del proyecto

Estructurar y limpiar los registros clínicos mediante la identificación, clasificación y estandarización de las variables, organizando la información en una base de datos que permita realizar análisis estadísticos descriptivos. Asimismo, identificar posibles inconsistencias y datos faltantes, y reconocer las características generales de los pacientes y sus estados de atención.

Diccionario de datos

La base de datos está conformada por doce variables. ID_PACIENTE corresponde al código único de identificación de cada paciente. EDAD representa los años cumplidos de cada persona y se clasifica como cuantitativa discreta. SEXO identifica el sexo femenino o masculino y corresponde a una variable cualitativa nominal. FECHA_CONSULTA registra la fecha de atención médica, mientras que MOTIVO_CONSULTA describe la razón principal por la cual el paciente acudió al hospital.

TEMPERATURA_C registra la temperatura corporal en grados Celsius y corresponde a una variable cuantitativa continua. FC_lpm representa la frecuencia cardíaca expresada en latidos por minuto y se clasifica como cuantitativa discreta. SpO2_% corresponde a la saturación periférica de oxígeno expresada en porcentaje. Diagnostico contiene el diagnóstico simulado registrado para cada paciente. Estado_Atención identifica si la atención se encuentra Finalizada, En atención o Pendiente. Observaciones permite registrar información adicional o datos faltantes y Registro corresponde al número consecutivo asignado a cada registro clínico.

Proceso de limpieza y organización de los datos

Inicialmente se revisaron los 20 registros clínicos para identificar las variables presentes y reconocer las diferencias en su presentación. Posteriormente, se separó la información en columnas independientes, asignando una fila a cada paciente y evitando almacenar varios datos en una misma celda.

Durante el proceso de limpieza se estandarizaron las categorías de sexo utilizando F para femenino y M para masculino. Las fechas se organizaron en el formato DD/MM/AAAA y los estados de atención se unificaron en tres categorías: Finalizada, En atención y Pendiente. También se organizaron los valores numéricos de edad, temperatura, frecuencia cardíaca y saturación de oxígeno para facilitar los cálculos estadísticos.

Se identificó un dato faltante en la saturación de oxígeno del paciente P016, por lo que se conservó la celda vacía sin asignar valores estimados. Asimismo, se verificaron las observaciones y se corrigió la asociación del dato «Saturación no registrada», que corresponde al paciente P016. Finalmente, se revisó la información para garantizar que los cálculos se realizaran sobre los registros correctos.

Resultados generales

El análisis de los 20 registros permitió obtener una edad promedio de 43 años y una temperatura promedio de 37,145 °C. La distribución por sexo fue equitativa, con 10 pacientes femeninos y 10 masculinos. Respecto al estado de atención, 9 pacientes presentan atención finalizada, 7 se encuentran en atención y 4 permanecen pendientes. La saturación mínima registrada fue del 91 %, correspondiente al paciente P009. Además, se identificó un registro incompleto por ausencia de saturación de oxígeno del paciente P016.

Archivos entregados

Para el desarrollo del proyecto se utilizaron los archivos e instrucciones proporcionados por el docente, los cuales contienen los registros clínicos ficticios del Hospital San Gabriel y las indicaciones para realizar las diferentes fases de la actividad.
A partir de esta información se elaboraron los archivos correspondientes al proyecto: pacientes.csv, que contiene los 20 registros clínicos estructurados; analisis.md, que presenta la interpretación de los indicadores estadísticos y las inconsistencias identificadas; y README.md, que documenta el objetivo, el diccionario de datos y el proceso de limpieza y organización de la información.

Declaración sobre los datos ficticios

Se declara que los 20 pacientes y todos los datos clínicos utilizados en este proyecto son completamente ficticios y fueron creados exclusivamente con fines académicos. La información no corresponde a personas reales y no debe utilizarse para establecer diagnósticos, tratamientos o decisiones clínicas. Su utilización tiene como único propósito desarrollar actividades de organización, limpieza, documentación y análisis estadístico de datos.

Consideraciones sobre privacidad clínica

El manejo de información clínica requiere responsabilidad, confidencialidad y protección de los datos personales. Por esta razón, es importante evitar la divulgación de información sensible, limitar el acceso a los registros y garantizar que los datos utilizados en actividades académicas no permitan identificar a pacientes reales. La protección de la información constituye un elemento esencial para preservar la integridad de los registros y la confianza en las instituciones de salud.



Hospital San Gabriel – Proyecto académico de Bioestadística.

Octubre de 2026.

