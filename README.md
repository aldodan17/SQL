# SQL
Este proyecto combina SQL y Python para analizar datos reales de viajes en Chicago. El objetivo es identificar patrones en las compañías de taxis, los barrios donde más finalizan los viajes y evaluar si el clima influye en la duración de ciertos trayectos.
Se trabajó con consultas SQL para extraer datos, visualizaciones en Python y una prueba de hipótesis estadística.

🛠️ Tecnologías utilizadas

SQL (PostgreSQL)
Python
pandas
matplotlib / seaborn
Estadística inferencial
Pruebas de hipótesis

📌 Metodología del proyecto
1️⃣ Importación y validación de datos (SQL → Python)
Carga de los datasets provenientes de consultas SQL.
Revisión y corrección de tipos de datos.
Exploración inicial y detección de valores inconsistentes.

2️⃣ Análisis de viajes y compañías de taxi

Ranking de compañías por volumen de viajes (15–16 noviembre 2017).
Identificación de los 10 barrios con más viajes finalizados en noviembre.
Gráficos comparativos para entender tendencias y participación de cada empresa.

3️⃣ Visualizaciones

✔ Gráfico de compañías de taxi vs número de viajes.
✔ Top 10 barrios con más viajes finalizados.
✔ Distribución de duración de viajes por clima.

4️⃣ Prueba de hipótesis
Se evaluó la afirmación:
“La duración promedio de los viajes desde el Loop hasta O’Hare cambia los sábados lluviosos.”

Incluye:

Formulación de H₀ (no hay diferencia) y H₁ (sí hay diferencia).
Selección del test estadístico adecuado (Mann-Whitney U o t-test según distribución).
Definición del nivel de significancia (α).
Interpretación técnica del p-value.

📈 Resultados principales

Identificación de las empresas con mayor actividad en días específicos.
Determinación de los barrios más concurridos por destino.
Análisis que confirma o rechaza si el clima (lluvia) afecta la duración de un viaje clave en la ciudad.

🧪 Conclusiones

Este proyecto muestra habilidades en:
Recuperación y análisis de datos con SQL.
Limpieza y transformación de datos.

Visualización profesional.

Pruebas de hipótesis orientadas a decisiones reales.
