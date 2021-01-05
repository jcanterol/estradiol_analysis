# TCD [PRA2] Estradiol

## Descripción

En este repositorio se presenta el proyecto asociado a la PRA2 de la asignatura _Tipología y Ciclo de Vida de los Datos_ del Máster en Ciencia de Datos de la Universitat Oberta de Cataluña.

Mediante técnicas de limpieza y análisis de datos implementados en R se prepara y extrae información de un conjunto de datos médico. En particular, se exploran las variables con una mayor influencia en los niveles de la hormona _serum estradiol_, uno de los principales factores de riesgo de cáncer de mama en mujeres premenopáusicas.

## Equipo

Esta práctica ha sido realizada de manera individual por **Javier Cantero Lorenzo** tras la autorización del profesor responsable de la asignatura el día 04 de Diciembre de 2020.

## Archivos

- **csv/estradiol_raw.csv:** Archivo original con el conjunto de los datos no procesados.
- **csv/estradiol_clean.csv:** Archivo con el conjunto de los datos preprocesados y listo para el análisis.

- **src/extract.Rmd:** Archivo encargado de convertir los datos originales de formato Rdata a csv.
- **src/preprocess.Rmd:** Archivo encargado de llevar a cabo las operaciones de limpieza de los datos.
- **src/analysis.Rmd:** Archivo encargado de llevar a cabo el análisis de los datos.

## Descripción del conjunto de datos

El dataset cuenta con 211 registros identificados por 11 descriptores. La semántica de los distintos atributos del conjunto de datos es la siguiente:

- **Id:** Identificador.
- **Estrad:** Niveles de serum estradiol (a partir de una analítica hormonal).
- **Ethnic:** Etnia (opciones: ‘Caucasian’, ‘African American’).
- **Entage:** Edad.
- **NumChild:** Número de hijos.
- **Agefbo:** Edad en la que la persona ha tenido su primer hijo.
- **Anykids:** ¿Tiene hijos? (Opciones: ‘0’ (no), ‘1’ (sí)).
- **Agemenar:** Edad de la menarquia (primera menstruación).
- **BMI:** Medida de la adiposidad general.
- **WHR:** Medida de la adiposidad abdominal.
- **Area:** Hábitat (Opciones: ‘0’ (urbana), ‘1’ (rural)).

## Licencia

Este proyecto cuenta con licencia **CC BY-NC-SA 4.0 License**.
