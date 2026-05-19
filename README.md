# MATLAB: Herramienta de Tecnología para la Solución de Problemas

Repositorio académico del curso **MATLAB: Herramienta de Tecnología para la Solución de Problemas** de la Pontificia Universidad Javeriana.

El curso introduce MATLAB como herramienta de programación, análisis de datos, visualización científica y prototipado computacional. La versión 2026 incorpora de forma explícita el uso responsable de herramientas de inteligencia artificial generativa, especialmente **MATLAB Copilot**, para apoyar el desarrollo de código, la depuración, la documentación y la solución de problemas.

---

## Información general del curso

| Campo | Información |
|---|---|
| Curso | MATLAB: Herramienta de Tecnología para la Solución de Problemas |
| ID | 008275 |
| Créditos | 2 |
| Intensidad | 2 horas semanales |
| Duración | 16 semanas + entrega de proyectos |
| Nivel | Pregrado |
| Prerrequisito | Matemáticas básicas |
| Modalidad | Presencial, con componente práctico intensivo |
| Actualización | Enero de 2026 |

---

## Propósito del repositorio

Este repositorio reúne materiales, ejemplos, scripts, Live Scripts, ejercicios y proyectos asociados al curso. Está pensado como un espacio de trabajo progresivo para que los estudiantes puedan:

- Aprender los fundamentos de MATLAB desde cero.
- Resolver problemas numéricos, estadísticos y de visualización.
- Construir scripts, funciones y programas modulares.
- Importar, procesar y visualizar datos reales.
- Utilizar MATLAB Copilot y herramientas de IA generativa de manera crítica y responsable.
- Desarrollar un proyecto final aplicado a un problema de interés profesional.

---

## Resultados de aprendizaje esperados

Al finalizar el curso, el estudiante estará en capacidad de:

1. Escribir programas en MATLAB para resolver problemas numéricos, estadísticos y de visualización.
2. Usar prompts efectivos para generar código con apoyo de herramientas de IA.
3. Evaluar críticamente la calidad, pertinencia y corrección del código generado por IA.
4. Importar, procesar y exportar datos desde archivos de texto, hojas de cálculo, CSV, JSON y otras fuentes.
5. Crear gráficos 2D, gráficos 3D, animaciones, dashboards y reportes técnicos.
6. Implementar condicionales, bucles, funciones personalizadas y scripts modulares.
7. Depurar código usando herramientas tradicionales de MATLAB y asistencia de IA.
8. Documentar resultados mediante Live Scripts y reportes reproducibles.
9. Aplicar toolboxes especializados según el área de interés del proyecto final.

---

## Estructura sugerida del repositorio

```text
.
├── README.md
├── syllabus/
│   └── Syllabus_MATLAB_2026.pdf
├── modulo_01_fundamentos/
│   ├── clase_02_tipos_vectores_matrices/
│   ├── clase_03_operaciones_matrices/
│   ├── clase_04_graficos_2d/
│   └── clase_05_scripts_live_scripts_copilot/
├── modulo_02_programacion/
│   ├── clase_06_condicionales/
│   ├── clase_07_bucles/
│   ├── clase_08_vectorizacion/
│   └── clase_09_funciones_debugging/
├── modulo_03_datos_visualizacion/
│   ├── clase_10_importacion_tables/
│   ├── clase_11_graficos_3d_animaciones/
│   └── clase_12_dashboards_reportes/
├── modulo_04_aplicaciones/
│   ├── clase_13_imagenes/
│   └── clase_14_machine_learning/
├── proyectos/
│   ├── micro_proyecto_01/
│   ├── micro_proyecto_02/
│   └── proyecto_final/
├── datasets/
├── ejemplos/
└── recursos/
```

> La estructura puede ajustarse durante el semestre según las necesidades del curso y los proyectos desarrollados por los estudiantes.

---

## Contenido del curso

### Módulo 1 — Fundamentos de MATLAB y programación asistida por IA

**Semanas:** 1 a 5  
**Entregable:** Micro-Proyecto 1

Temas principales:

- Entorno de MATLAB y MATLAB Online.
- Variables, tipos de datos y operadores.
- Vectores, matrices e indexación.
- Operaciones elemento a elemento y operaciones matriciales.
- Estadística descriptiva básica.
- Gráficos 2D: `plot`, `scatter`, `bar`, `histogram`.
- Scripts, secciones ejecutables y buenas prácticas de documentación.
- Live Scripts como herramienta de reporte técnico.
- Introducción a MATLAB Copilot.
- Evaluación crítica de código generado por IA.

Funciones y conceptos destacados:

```matlab
zeros, ones, rand, randn, linspace
size, length, numel
sum, mean, std, var, min, max, range
plot, scatter, bar, histogram
xlabel, ylabel, title, legend, subplot
```

---

### Módulo 2 — Programación y estructuras de control

**Semanas:** 6 a 9  
**Entregable:** Micro-Proyecto 2

Temas principales:

- Operadores relacionales y lógicos.
- Condicionales: `if`, `elseif`, `else`.
- Selección múltiple con `switch-case`.
- Bucles `for` y `while`.
- Control de flujo con `break` y `continue`.
- Vectorización y eficiencia computacional.
- Creación de funciones con entradas y salidas.
- Validación de argumentos.
- Scope de variables.
- Debugging con breakpoints, step, watch y diagnóstico asistido por IA.
- Buenas prácticas de estilo, modularidad y testing.

Funciones y estructuras destacadas:

```matlab
if, elseif, else, switch, case, otherwise
for, while, break, continue
function, arguments, return
tic, toc
```

---

### Módulo 3 — Datos y visualización avanzada

**Semanas:** 10 a 12  
**Entregable:** ejercicios semanales que alimentan el proyecto final

Temas principales:

- Importación de datos desde CSV, Excel, texto y JSON.
- Exportación de resultados.
- Uso de `table` como estructura central para datos tabulares.
- Filtrado, ordenamiento y transformación de datos.
- Agrupamiento y resumen con `groupsummary`.
- Gráficos 3D con `plot3`, `scatter3` y `bar3`.
- Superficies con `mesh`, `surf` y `contour`.
- Animaciones con `drawnow`, `getframe` e `imwrite`.
- Dashboards con `tiledlayout` y `nexttile`.
- Exportación profesional de figuras y reportes.

Funciones destacadas:

```matlab
readtable, readmatrix, readcell
writetable, writematrix
jsonencode, jsondecode
table, array2table, sortrows, groupsummary
height, width, summary
plot3, scatter3, bar3
mesh, surf, contour, meshgrid
tiledlayout, nexttile, exportgraphics
```

---

### Módulo 4 — Aplicaciones: imágenes y machine learning

**Semanas:** 13 a 14  
**Entregable:** ejercicios de clase e insumos para el proyecto final

Temas principales:

- Lectura, visualización y escritura de imágenes.
- Representación matricial de imágenes.
- Canales RGB y escala de grises.
- Redimensionamiento y recorte.
- Filtros clásicos, realce y detección de bordes.
- Introducción a machine learning en MATLAB.
- Uso de datasets clásicos como `fisheriris` y `carbig`.
- Classification Learner.
- Regression Learner.
- Entrenamiento y comparación de modelos sin escribir modelos desde cero.
- Exportación de modelos para uso posterior en scripts.
- Uso de MATLAB Copilot para construir pipelines de análisis.

Toolboxes recomendados:

- Image Processing Toolbox.
- Statistics and Machine Learning Toolbox.

Funciones destacadas:

```matlab
imread, imwrite, imshow
rgb2gray, im2double, imresize, imcrop
fspecial, imfilter, imgaussfilt, medfilt2
edge, imadjust, histeq, adapthisteq, imsharpen
fitctree, fitlm, predict, confusionchart
```

---

## Cronograma resumido

| Semana | Tema | Actividad práctica |
|---:|---|---|
| 1 | Introducción a MATLAB y entorno de desarrollo | Operaciones básicas y cálculos matriciales |
| 2 | Variables, tipos de datos y MATLAB Copilot | Primeros prompts y evaluación de código generado |
| 3 | Vectores y matrices | Manipulación de datos numéricos |
| 4 | Gráficos 2D básicos | Visualización de datos climáticos |
| 5 | Scripts y Live Scripts | Micro-Proyecto 1 |
| 6 | Condicionales | Clasificador de datos |
| 7 | Bucles `for` y `while` | Procesamiento iterativo |
| 8 | Vectorización y eficiencia | Optimización de algoritmos |
| 9 | Funciones y debugging | Micro-Proyecto 2 |
| 10 | Importación y exportación de datos | Pipeline desde Excel y CSV |
| 11 | Tables y estructuras de datos | Análisis de dataset real |
| 12 | Gráficos 3D y animaciones | Visualización científica avanzada |
| 13 | Toolboxes especializados | Exploración por área de interés |
| 14 | Simulink básico / Machine Learning intro | Aplicación por área de interés |
| 15 | Trabajo en proyecto final | Asesoría individual |
| 16 | Presentación de proyectos finales | Entrega y presentación |

---

## Sistema de evaluación

| Componente | Tipo | Porcentaje | Semana |
|---|---|---:|---|
| Primera evaluación parcial | Micro-Proyecto 1 | 25 % | Semana 5 |
| Segunda evaluación parcial | Micro-Proyecto 2 | 25 % | Semana 9 |
| Evaluación final | Proyecto final | 30 % | Semana 16 |
| Trabajos asignados | Tareas y quices | 20 % | Continuo |

---

## Proyectos del curso

### Micro-Proyecto 1 — Análisis y visualización de datos

El estudiante desarrolla un Live Script en el que debe:

- Crear o importar un conjunto de datos relevante.
- Calcular estadísticas descriptivas.
- Realizar operaciones matriciales o vectoriales.
- Crear visualizaciones profesionales.
- Documentar el proceso de uso de MATLAB Copilot.
- Reflexionar sobre la utilidad, limitaciones y ajustes hechos al código generado por IA.

Entrega esperada:

```text
Apellido_Nombre_MicroProyecto1.mlx
```

---

### Micro-Proyecto 2 — Programa modular con funciones

El estudiante construye un programa modular que integre:

- Script principal.
- Mínimo tres funciones en archivos separados.
- Datos generados o importados.
- Condicionales, bucles y vectorización.
- Casos de prueba.
- Documentación con ayuda (`help`) en cada función.

Tema sugerido en el módulo:

```text
Simulador de gestión de inventario
```

Entrega esperada:

```text
Apellido_Nombre_MicroProyecto2.zip
```

---

### Proyecto final

El proyecto final debe resolver un problema real del área de interés del estudiante. Debe integrar:

- Importación de datos.
- Limpieza, procesamiento y análisis.
- Visualización 2D o 3D.
- Uso pertinente de scripts, funciones o Live Scripts.
- Documentación técnica.
- Presentación oral.
- Uso responsable y documentado de herramientas de IA.

---

## Uso responsable de inteligencia artificial

En este curso se permite y se promueve el uso de herramientas de IA generativa como apoyo al aprendizaje y al desarrollo de código. Sin embargo, cada estudiante debe demostrar comprensión real de sus soluciones.

Buenas prácticas esperadas:

- Documentar los prompts usados.
- Explicar qué partes del código fueron generadas con IA.
- Verificar que el código funcione correctamente.
- Corregir errores, adaptar el código y justificar cambios.
- No entregar código que no se entienda.
- Citar o declarar el apoyo de IA cuando sea solicitado por el docente.

Ejemplo de prompt recomendado:

```text
Tengo un archivo CSV llamado ventas_2025.csv con columnas Fecha, Producto,
Cantidad y Precio. Importa los datos, calcula el ingreso total por producto,
genera un gráfico de barras y comenta cada bloque del código para que pueda
explicarlo en un Live Script.
```

---

## Requisitos de software

Recomendado:

- MATLAB R2024b o superior.
- MATLAB Online.
- MATLAB Copilot, si está disponible para la licencia institucional.
- Image Processing Toolbox.
- Statistics and Machine Learning Toolbox.
- Signal Processing Toolbox, según el proyecto final.
- Simulink, para las sesiones introductorias o proyectos que lo requieran.

---

## Recomendaciones para estudiantes

1. Trabaja siempre en carpetas organizadas por clase o módulo.
2. Usa nombres descriptivos para variables y archivos.
3. Incluye comentarios que expliquen el propósito del código.
4. Prefiere vectorización cuando sea posible.
5. Prueba tus funciones con casos simples antes de usarlas en proyectos grandes.
6. Exporta tus resultados en formatos reproducibles: `.mlx`, `.m`, `.csv`, `.png`, `.pdf`.
7. Mantén un registro de prompts y respuestas relevantes de MATLAB Copilot.
8. Revisa errores comunes antes de pedir ayuda: dimensiones, índices, nombres de variables y rutas de archivos.

---

## Recursos recomendados

- MATLAB Onramp: <https://matlabacademy.mathworks.com>
- Documentación oficial de MATLAB: <https://www.mathworks.com/help/matlab>
- MATLAB Examples: <https://www.mathworks.com/help/matlab/examples.html>
- MATLAB Central: <https://www.mathworks.com/matlabcentral>
- MATLAB Copilot: <https://www.mathworks.com/products/matlab-copilot>

---

## Autor y contexto académico

Curso preparado para la Pontificia Universidad Javeriana, Bogotá, Colombia.

**Profesor:** Francisco Carlos Calderón  
**Año:** 2026

---

## Licencia

Material académico en desarrollo. La licencia de uso y redistribución del repositorio está pendiente de definición.
