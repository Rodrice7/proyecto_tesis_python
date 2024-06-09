# proyecto_tesis_python
Investigación de Tesis: Eficiencia del financiamiento del mercado de capitales en Venezuela, un análisis para el período 2000-2015

CAPITULO IV
Introducción

El presente capítulo se centra en presentar los análisis exploratorios de las variables, tanto univariado como bivariado.  Luego se deriva en un análisis econométrico para evaluar la eficiencia del financiamiento del mercado de capitales en Venezuela durante el período 2000-2020. 
Este análisis es fundamental para comprender si el mercado de capitales ha servido como una fuente eficiente de financiamiento para las empresas en un contexto de limitado acceso al crédito bancario. A través de un enfoque metodológico riguroso y una selección cuidadosa de modelos econométricos, este capítulo busca arrojar luz sobre la dinámica del mercado de capitales venezolano y su impacto en la rentabilidad empresarial.
4.2 Metodología
La metodología empleada para el análisis econométrico involucra varios pasos críticos:
1.	Selección y Preparación de Datos: Se utilizaron datos secundarios, obtenidos de fuentes confiables como la Bolsa de Valores de Caracas y el Banco Central de Venezuela. Estos datos incluyen información clave como el PIB trimestral, la Formación Bruta de Capital Fijo (FBC), el Índice de Precios al Consumidor (IPC), montos negociados, número de operaciones y número de acciones, entre otros. Las empresas fueron clasificadas en dos sectores: financieras y no financieras.
2.	Transformación de Datos: Dada la naturaleza de los datos, se realizaron transformaciones para estandarizarlos a precios constantes de 1997, lo cual fue esencial para garantizar comparaciones coherentes a lo largo del tiempo. Para los indicadores de rentabilidad como ROE y ROA, se recopilaron datos semestrales y se realizó una interpolación lineal para desagregarlos a un formato trimestral, permitiendo un análisis más detallado y preciso.
3.	Construcción de Modelos Econométricos: Se emplearon dos tipos de modelos econométricos:
•	Modelos de Rezagos Distribuidos: Estos modelos se centraron en estudiar la relación directa entre las variables seleccionadas, como el PIB, montos negociados, IPC y FBC, con los indicadores de rentabilidad ROE y ROA.
•	Modelo de Corrección de Errores: Este modelo se consideró para evaluar la relación a largo plazo entre las variables no estacionarias y cointegradas.
El análisis econométrico buscó responder a la pregunta central de si el aumento de los montos negociados se correlaciona con aumentos en los indicadores de rentabilidad ROE y ROA, lo cual es indicativo de la eficiencia del mercado de valores.
4.5 Discusión de Limitaciones
El análisis enfrentó varias limitaciones que son importantes destacar:
Desafíos en la Recopilación de Datos: La obtención de datos completos y consistentes fue un desafío, especialmente en el contexto económico venezolano, donde la inflación excesiva y las conversiones monetarias pueden afectar la calidad y coherencia de los datos financieros. Se presentaron casos de datas incompletas o no estandarizadas en sus metodologías estadísticas de presentación. 
El levantamiento de la data referente a montos negociados tiene especial atención. Se recolecto de la publicación de boletines mensuales de la bolsa de valores de caracas, limitación que conlleva un aumento del sesgo de un “posible error humano”, pues aun usando software para automatizar la tarea, hay implícito una transformación y limpieza de datos. 
Limitaciones Metodológicas: La aplicación de la interpolación lineal y la diferenciación para tratar los datos de rentabilidad implica ciertas suposiciones y puede introducir estimaciones aproximadas. Además, la selección de modelos econométricos, aunque fundamentada, lleva inherente una serie de supuestos y restricciones analíticas.
Contexto Económico y Político: Los cambios políticos y económicos en Venezuela durante el período de estudio influyen significativamente en la interpretación de los resultados. La eficiencia del mercado de capitales puede verse afectada por factores externos que no se capturan completamente en el modelo.
Estas limitaciones son cruciales para comprender el alcance y las implicaciones de los hallazgos del análisis econométrico.


Documentación del Proceso Estadístico y Decisiones Tomadas:

1. Preparación y Revisión Inicial de los Datos
•	Carga de Datos: Importación de los datos relevantes para el análisis.
•	Exploración Inicial: Revisión de las variables clave, incluyendo PIB, FBC, ROE, ROA, y montos negociados.
2. Pruebas de Estacionariedad
•	Aplicación de Pruebas de Dickey-Fuller: Evaluación de la estacionariedad de las series temporales para determinar si era necesario realizar diferenciaciones.
•	Decisión de Diferenciar: Basándonos en los resultados, se decidió aplicar diferenciaciones a las series para lograr la estacionariedad.
3. Construcción del Modelo de Rezagos Distribuidos
•	Selección de Variables y Rezagos: Decisión de incluir rezagos diferenciados del PIB, FBC y montos negociados para capturar la dinámica temporal.
•	Modelado y Ajuste: Uso de regresión OLS para estimar la relación entre estas variables y los cambios en el ROE.
4. Evaluación de Multicolinealidad y Ajuste del Modelo
•	Análisis de Multicolinealidad: Uso del Factor de Inflación de la Varianza (VIF) para identificar problemas de multicolinealidad.
•	Eliminación de Variables: Basándonos en los VIF y la significancia estadística, se eliminaron algunas variables para reducir la multicolinealidad.
5. Interpretación de Resultados
•	Análisis de Coeficientes: Interpretación de los coeficientes del modelo ajustado para entender cómo los cambios en PIB, FBC y montos negociados afectan el cambio en el ROE.
•	Consideraciones Económicas: Reflexión sobre las implicaciones económicas de los resultados, en el contexto de la eficiencia del mercado de valores en Venezuela.
6. Modelo de Corrección de Errores (Complementario)
•	Razón para Incluir ECM: Decisión de incluir un ECM para explorar las relaciones a largo plazo y la corrección hacia el equilibrio.
•	Interpretación del ECM: Aunque el término de corrección de error no fue significativo, su inclusión proporcionó una perspectiva valiosa sobre la dinámica a largo plazo y posibles sugerencias para aquellos interesados en profundizar el análisis de largo plazo.

