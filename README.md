# Análisis del Conflicto Geopolítico entre Ucrania y Rusia (2018 - 2023)

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el conflicto geopolítico entre Ucrania y Rusia, un conflicto que culminó en una guerra a gran escala iniciada en 2022, la cual continúa hasta la fecha. El análisis abarca el período desde 2018 hasta 2023, con el objetivo de estudiar los eventos que llevaron a la escalada del conflicto, sus repercusiones y las implicaciones geopolíticas a nivel global.

El conjunto de datos contiene más de 96.000 registros y 31 columnas que cubren diferentes aspectos, como eventos militares, sanciones económicas, desplazamientos de población y reacciones diplomáticas. La riqueza y la complejidad de los datos permite realizar un análisis exhaustivo de la evolución del conflicto.

## Elección y Justificación del Conjunto de Datos

El conjunto de datos seleccionado es ideal para este proyecto debido a su tamaño y amplitud temporal. Los datos, que abarcan desde 2018 hasta 2023, permiten obtener una visión detallada del conflicto, con suficientes registros para realizar análisis robustos. Los datos incluyen información de múltiples tipos: temporal, geográfica, económica y militar, lo que exige un tratamiento cuidadoso mediante técnicas de limpieza y visualización.

### Características del Conjunto de Datos

- **Período**: 2018 - 2023
- **Registros**: 96.082
- **Columnas**: 31 variables
- **Tamaño**: 42 MB
- **Tipos de Variables**: Datos temporales, geográficos, económicos, militares, desplazamientos de población, entre otros.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

1. **notebooks/**: Carpeta que contiene notebooks Jupyter con el análisis interactivo de los datos.
   - `Irene_Talavera_Álvarez.ipynb`: Notebook principal que incluye el análisis, la limpieza de datos y la visualización de los eventos clave del conflicto.

2. **data/**: Carpeta donde se almacena el conjunto de datos en formato CSV.
   - `conflict_data_ukraine_russia_2018_2023.csv`: Datos crudos que contienen información del conflicto.

3. **scripts/**: Carpeta con scripts de Python que realizan tareas específicas dentro del proyecto.
   - `data_cleaning.py`: Script para la limpieza y el preprocesamiento de los datos.
   - `visualizations.py`: Script para la generación de gráficos y visualizaciones.

4. **output/**: Carpeta que contiene los resultados del análisis, como gráficos y archivos generados durante el proceso.

5. **README.md**: Este archivo, que proporciona una descripción general del proyecto, sus objetivos y cómo ejecutarlo.

## Bibliotecas Utilizadas

El proyecto requiere las siguientes bibliotecas de Python para su correcto funcionamiento:

- `pandas`
- `requests`
- `matplotlib`
- `seaborn`

## Requisitos

Para ejecutar el proyecto, necesitarás instalar las dependencias necesarias. Puedes instalarlas ejecutando el siguiente comando en tu terminal:

```bash
pip install pandas requests matplotlib seaborn
```

## Instrucciones de Ejecución

1. **Instalar las dependencias**:
   Asegúrate de tener instaladas todas las bibliotecas requeridas ejecutando el siguiente comando:
   ```bash
   pip install pandas requests matplotlib seaborn
   ```

2. **Abrir el notebook**:
   Utiliza Jupyter Notebook o cualquier otro entorno compatible para abrir el archivo `Irene_Talavera_Álvarez.ipynb`.

3. **Ejecutar el análisis**:
   Sigue las celdas paso a paso en el notebook para ejecutar el análisis. El notebook incluye la limpieza de datos, generación de visualizaciones y conclusiones basadas en los datos del conflicto.

4. **Explorar los resultados**:
   Los resultados del análisis incluyen gráficos y tendencias visuales que permiten comprender mejor la evolución del conflicto, tanto en términos de los eventos militares como de las sanciones económicas y los desplazamientos de población.

## Resultados Esperados

El proyecto incluye los siguientes tipos de resultados:

- **Gráficos y visualizaciones**: Se generan gráficos sobre la evolución temporal del conflicto, sanciones económicas impuestas, desplazamientos de población y eventos militares clave.
- **Análisis de tendencias**: A partir de los datos, se identifican tendencias sobre cómo ha evolucionado el conflicto y cuáles son las posibles direcciones futuras.
- **Predicciones basadas en datos**: Utilizando técnicas de análisis predictivo, el proyecto ofrece una visión sobre los posibles desarrollos del conflicto en función de los datos históricos.

## Contribuciones

Si deseas contribuir a este proyecto, puedes hacerlo siguiendo estos pasos:

1. Haz un **fork** de este repositorio.
2. Crea una nueva rama para tu funcionalidad (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz un **commit** (`git commit -m 'Añadir nueva funcionalidad'`).
4. Sube tus cambios a tu repositorio (`git push origin feature/nueva-funcionalidad`).
5. Abre un **pull request** para que se revisen tus cambios.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para obtener más detalles sobre los términos y condiciones.

## Contacto

Si tienes alguna pregunta o sugerencia sobre el proyecto, no dudes en ponerte en contacto conmigo:

- **Nombre**: [Irene Talavera Álvarez]
- **GitHub**: [https://github.com/irtajal](https://github.com/irtajal)
