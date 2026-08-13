<p align="center">
  <img src="assets/img/logo.jpg" width="150"
style="border-radius: 50%;">
</p>

# Sebastián Oropeza — Data Analyst

Data Analyst con formación en TripleTen y proyectos aplicados en machine 
learning, marketing analytics y A/B testing. Trabajo con Python, SQL y 
Tableau para limpiar, estructurar y visualizar datos que respalden 
decisiones de negocio.

He desarrollado un modelo predictivo de churn con 90% de accuracy sobre 
4,000 clientes, identificado una ineficiencia de $141,321 en campañas de 
marketing y auditado pruebas A/B detectando problemas de ejecución que 
invalidaban sus conclusiones.

**Inglés C1 (EFSET)** — disponible para roles remotos, híbridos y presenciales.

---

### Habilidades técnicas
**Lenguajes:** Python (Pandas, NumPy, Scipy, Seaborn, Matplotlib) | SQL

**Visualización:** Tableau | Excel | Google Sheets

**Análisis:** Estadística inferencial | Análisis de cohortes | A/B Testing | Machine Learning básico

**Otros:** Pipelines de datos | Web Scraping (BeautifulSoup) | Git & GitHub

---

### Contacto
[LinkedIn](https://www.linkedin.com/in/sebastian-oropeza-ramirez) | 
[GitHub](https://github.com/sgcuervo) | 
[Portafolio](https://sgcuervo.github.io/) | 
sebastianor2099@gmail.com

***

# Proyectos seleccionados

## Predicción de Churn en Gimnasios — Model Fitness
Model Fitness pierde clientes silenciosamente: se van sin cancelar, 
simplemente dejan de asistir. El gimnasio necesita identificar quién 
está en riesgo antes de que desaparezca, y diseñar intervenciones 
específicas para cada perfil de cliente.

### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/MATPLOTLIB-blue?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/SEABORN-blue?style=for-the-badge)
![Limpieza de Datos](https://img.shields.io/badge/LIMPIEZA_DE_DATOS-blue?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/MACHINE_LEARNING-blue?style=for-the-badge)
![Clustering](https://img.shields.io/badge/CLUSTERING-blue?style=for-the-badge)
![Análisis de Datos](https://img.shields.io/badge/AN%C3%81LISIS_DE_DATOS-blue?style=for-the-badge)
![Visualización de Datos](https://img.shields.io/badge/VISUALIZACI%C3%93N_DE_DATOS-blue?style=for-the-badge)

## Preguntas clave:
1. ¿Qué variables predicen mejor la cancelación de una membresía?
2. ¿Cuándo ocurre la deserción y qué la desencadena?
3. ¿Qué perfiles de cliente existen y cuál es su nivel de riesgo?
4. ¿Qué estrategias concretas pueden reducir el churn por segmento?

## Metodología
- **Análisis exploratorio:** Identificación de variables con mayor poder 
  predictivo y detección de multicolinealidad crítica entre pares de 
  variables (correlaciones de 0.95 y 0.97).
- **Modelado predictivo:** Entrenamiento y comparación de Regresión 
  Logística y Random Forest sobre dataset de 4,000 clientes. Selección 
  del modelo final basada en Recall como métrica prioritaria.
- **Segmentación:** Clustering con K-Means validado con dendrograma 
  jerárquico para determinar número óptimo de clústeres (5).
- **Recomendaciones:** Traducción de hallazgos en estrategias de retención 
  diferenciadas por segmento.

## Insights clave:
1. **El primer mes es la ventana crítica.** El tiempo de vida promedio 
de un cliente que cancela es de 0.99 meses — se van en su primera 
experiencia. Quienes superan el tercer mes muestran lealtad prolongada.

2. **La asistencia semanal es la señal de alerta más temprana.** Los 
usuarios en riesgo reducen su frecuencia a 1 visita o menos por semana 
en el mes de cancelación. Una asistencia de 3 o más veces por semana 
reduce la probabilidad de abandono a casi cero.

3. **Los contratos cortos son volátiles por naturaleza.** Los clientes 
que cancelan promedian contratos de 1.7 meses; los leales, 5.7 meses.

4. **Los vínculos sociales y corporativos retienen más que cualquier 
descuento.** Solo el 18.3% de los clientes que se van llegó referido 
por un amigo, contra el 35.3% de los leales.

5. **La Regresión Logística superó al Random Forest como modelo final.**

   | Métrica | Regresión Logística | Random Forest |
   |---|---|---|
   | Accuracy | 90.0% | 89.6% |
   | Recall | 81.8% | 75.2% |
   | Precisión | 78.6% | 81.4% |

6. **Cinco segmentos identificados con tasas de churn desde 0% hasta 58.2%.**

   | Clúster | Perfil | Churn |
   |---|---|---|
   | 0 — Golondrina | Contratos cortos, sin vínculos, perfil joven | 58.2% |
   | 3 — Foráneos | Viven lejos del gimnasio | 40.8% |
   | 2 — Red Social | 100% referidos o convenio corporativo | 12.9% |
   | 1 — Premium | Contratos largos, alto consumo adicional | 3.2% |
   | 4 — VIP | Clientes históricos, hábito consolidado | 0.0% |

## Recomendaciones:
1. **Programa de onboarding para primeros 60 días** — sesión gratuita 
con entrenador en la primera semana y alerta automática si la asistencia 
cae por debajo de 2 visitas en la primera quincena.
2. **Campaña de conversión a contratos largos** — descuento para usuarios 
mensuales que completen su primer mes, incentivando el salto a membresías 
semestrales o anuales.
3. **Club de recompensas por asistencia** — puntos canjeables en cafetería 
y tienda para premiar consistencia y usar servicios adicionales como ancla 
de hábito diario.
4. **Expansión del canal corporativo y social** — nuevos convenios con 
empresas del vecindario y optimización del programa "Trae a un amigo".

### Visualizaciones destacadas

1. **Mapa de calor de correlaciones entre variables**
![Mapa de calor](assets/img/p01_correlation_heatmap.png)
El análisis del mapa de calor revela que la gran mayoría de las características no presentan correlaciones significativas entre sí. Sin embargo, se detectan dos casos críticos de multicolinealidad fuerte (valores superiores a **0.90**):

`contract_period` y `month_to_end_contract` (**0.97**): Relación lineal casi perfecta debido a la naturaleza del vencimiento de las membresías.
`avg_class_frequency_total` y `avg_class_frequency_current_month` (**0.95**): Alta dependencia entre el comportamiento histórico de asistencia y el del mes en curso.
Para evitar distorsiones en los coeficientes del modelo de Regresión Logística, se recomienda eliminar una variable de cada par (`month_to_end_contract` y `avg_class_frequency_total`) antes de proceder con el entrenamiento de los modelos predictivos.

2. **Dendrograma jerárquico**
![Dendrograma](assets/img/p01_dendrogram.png)
El gráfico jerárquico muestra una estructura de agrupamiento clara:

- **Grupos Principales**: Se identifican inicialmente 4 grandes bloques de color en la base (naranja, verde, rojo y morado).

- **Justificación de los 5 Clústeres**: Al analizar la rama morada de la derecha, se observa una división sumamente marcada en dos sub-ramas principales alrededor de la altura 60. Separar este bloque masivo en dos subgrupos independientes nos permite obtener una segmentación más precisa y detallada. Por lo tanto, se justifica matemáticamente fijar el algoritmo en **5 clústeres** para el análisis posterior con K-Means.

3. **Tasa de churn por clúster**
![Churn por clúster](assets/img/p01_churn_rate.png)
Al ejecutar el aislamiento de la tasa de deserción por grupo, se obtienen las siguientes respuestas clave para el negocio:

1. **¿Difieren en términos de tasa de cancelación?** Sí, difieren de manera drástica y polarizada. La base de clientes de Model Fitness se divide en dos extremos muy claros: grupos con una retención casi perfecta y grupos con una fuga masiva de usuarios.

2. **¿Qué grupos son propensos a irse?**
- **Clúster 0 (Riesgo Crítico):** Presenta la tasa de cancelación más alta del gimnasio con un **58.2%**. Es el grupo prioritario a intervenir.
- **Clúster 3 (Riesgo Moderado-Alto):** Registra una tasa de deserción del **40.8%**, impulsada principalmente por la barrera geográfica (usuarios lejanos).

3. **¿Cuáles son leales?**
- **Clúster 4 (Lealtad Absoluta):** Muestra una tasa de cancelación del **0.0%**. Son los clientes históricos más consolidados del club.
- **Clúster 1 (Alta Lealtad):** Registra apenas un **3.2%** de deserción, caracterizado por su alto consumo en servicios adicionales y contratos de largo plazo.
- **Clúster 2 (Alta Lealtad Social):** Presenta un **12.9%** de bajas, respaldado por la efectividad de las membresías corporativas y el programa de referidos.

**Visita el [repositorio completo](https://github.com/sgcuervo/model-fitness-machine-learning) para más detalles.**
