# FUAS 2016–2020 — Analítica de datos educacionales

Repositorio docente orientado al uso de información asociada al **Formulario Único de Acreditación Socioeconómica (FUAS)** y a datos públicos oficiales del **Ministerio de Educación de Chile (MINEDUC)** como base para actividades de **analítica de datos**.

Los notebooks fueron desarrollados como material de trabajo para estudiantes de distintos cursos, permitiendo aplicar técnicas de exploración, preparación y modelamiento sobre problemas vinculados con educación superior y beneficios estudiantiles.

## Propósito docente

El repositorio busca trabajar con problemas reales y datos del sistema educacional chileno, utilizando Python y notebooks Jupyter como entorno de análisis.

Entre los temas presentes en los notebooks se encuentran variables relacionadas con **gratuidad**, trayectoria en educación superior, características académicas y socioeconómicas, y cambio de institución de educación superior (IES).

## Contenido

### Análisis por período

- `FUAS-2016.ipynb`
- `FUAS-2017.ipynb`
- `FUAS-2018.ipynb`
- `FUAS-2019.ipynb`

Estos notebooks contienen ejercicios de exploración y análisis de variables asociadas a los datos trabajados en las actividades docentes.

### Modelamiento

- `1_FUAS-2016-202_Regresion-Logistica.ipynb`
- `1_FUAS-2016-202_Regresion-Logistica_GRATUIDAD.ipynb`
- `1_FUAS-2016-202_Regresion-Logistica_CAMBIO-IES.ipynb`

Estos materiales incorporan ejercicios de **regresión logística** aplicados, entre otros aspectos, a variables relacionadas con obtención de gratuidad y cambio de institución.

## Usos docentes

Los notebooks permiten abordar actividades como:

- análisis exploratorio de datos;
- identificación y selección de variables;
- preparación y transformación de información;
- análisis de variables académicas y socioeconómicas;
- construcción e interpretación de modelos de clasificación;
- regresión logística aplicada a problemas educacionales;
- discusión crítica de resultados y limitaciones del modelamiento.

## Datos y reproducibilidad

Los notebooks hacen referencia a archivos de trabajo como `FUAS-Clustering.csv`, `rutUnicos_final.csv` y `DatosGuardados.csv`. **Estos archivos no forman parte actualmente del repositorio**, por lo que algunos notebooks no pueden ejecutarse de principio a fin únicamente mediante un clon del proyecto.

El repositorio se conserva principalmente como **material docente e histórico** y como registro de los ejercicios analíticos desarrollados.

## Fuente de los datos

Los ejercicios fueron construidos a partir de información pública oficial del **Ministerio de Educación de Chile (MINEDUC)** utilizada en las actividades docentes.

- [Datos Abiertos MINEDUC](https://datosabiertos.mineduc.cl/)
- [Portal de Beneficios Estudiantiles](https://portal.beneficiosestudiantiles.cl/)

Para nuevos análisis o investigaciones se recomienda obtener los datos directamente desde las fuentes oficiales, verificar su documentación y utilizar las versiones correspondientes al período que se desea estudiar.

## Nota sobre vigencia

Los notebooks reflejan herramientas, bibliotecas y prácticas utilizadas al momento de desarrollar las actividades. Algunas dependencias o instrucciones pueden requerir ajustes para ejecutarse en entornos actuales de Python.

No se han modificado los notebooks originales para preservar su valor como material docente histórico.

## Uso responsable

El trabajo con información socioeconómica y educacional requiere interpretar los resultados dentro de su contexto y evitar inferencias que excedan lo que permiten los datos. En actividades de modelamiento, las asociaciones o predicciones obtenidas no deben interpretarse automáticamente como relaciones causales.

---

**Responsable del repositorio:** Dr. Julio López-Núñez  
**Uso principal:** docencia y formación en analítica de datos
