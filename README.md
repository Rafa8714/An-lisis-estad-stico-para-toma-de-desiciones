Análisis de Hipótesis y Pruebas A/B: Tienda Online 🛒📊

Este proyecto se divide en dos etapas críticas para la toma de decisiones de negocio: la priorización de hipótesis mediante frameworks de crecimiento y el análisis de resultados de un test A/B para optimizar los ingresos.

📝 Descripción del Proyecto
El objetivo es determinar qué cambios en la plataforma de e-commerce generan el mayor impacto con el menor esfuerzo posible, utilizando datos reales de navegación y transacciones.

🚀 Etapa 1: Priorización de Hipótesis
Se evaluaron 9 hipótesis de negocio utilizando dos metodologías:

1. ICE (Impact, Confidence, Ease): Enfocado en la rapidez y el impacto directo.

  * Ganador: Lanzar descuentos por cumpleaños. * Conclusión: Es ideal para resultados rápidos ("Quick Wins") debido a su alta confianza y bajo esfuerzo, aunque su alcance es limitado.

2. RICE (Reach, Impact, Confidence, Effort): Introduce el factor de Alcance (Reach).

  * Ganador: Agregar formularios de suscripción en todas las páginas.

Conclusión: Al medir cuántos usuarios verán el cambio, esta hipótesis escala al primer lugar. Afectar a toda la base de usuarios es más rentable a largo plazo que acciones segmentadas.

🧪 Etapa 2: Análisis del Test A/B

Tras la implementación de las pruebas, se realizó un proceso de limpieza y análisis descriptivo:

No se pudo rechazar la hipótesis nula: la distribución parece ser normal:

<img width="833" height="547" alt="image" src="https://github.com/user-attachments/assets/3faa08d7-7216-431b-8379-8eb8b4f3b179" />

Hipótesis nula rechazada: la distribución no es normal:

<img width="841" height="547" alt="image" src="https://github.com/user-attachments/assets/13537420-6eb2-4f0b-9ee3-5111d1740a47" />


🛠️ Calidad de los Datos
  * Limpieza de Usuarios: Se detectaron 58 usuarios "contaminados" (presentes en ambos grupos, A y B).

  * Acción: Se excluyeron del análisis para evitar sesgos, ya que su comportamiento no puede atribuirse a una sola variante, garantizando así la integridad estadística del test.

📈 Conclusiones Preliminares

  * Divergencia de Métricas: Se observó que mientras ICE prioriza la conversión individual, RICE prioriza la captura de leads masivos.

  * Estabilidad: Los ingresos acumulados muestran tendencias que permiten identificar qué grupo (A o B) está liderando la rentabilidad sin la influencia de valores atípicos (outliers).

💡 Conclusiones Generales

  * Elegir el Framework correcto: Si el objetivo es crecimiento masivo, RICE es superior por considerar el volumen de tráfico. Si el presupuesto es muy ajustado, ICE ayuda a identificar tareas sencillas.

  * La limpieza es clave: Un 5% de usuarios duplicados entre grupos puede invalidar meses de experimentación. La detección temprana de estos IDs evitó conclusiones erróneas sobre la conversión.

🛠️ Tecnologías Utilizadas

  * Python (Pandas, Numpy)

  * Visualización: Matplotlib & Seaborn

  * Análisis Estadístico
