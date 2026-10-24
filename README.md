# Alzheimer-PowerBI-analysis
Reporte interactivo en Power BI que presenta los hallazgos clave del análisis de datos sobre el Alzheimer
![Vista previa del Dashboard de Alzheimer](https://github.com/camila-portilla/Alzheimer-PowerBI-analysis/blob/main/Analisis%20MID%20alzahimer.jpg)

📊 Conclusiones y Hallazgos Clave
1. Demografía y Volúmenes Cerebrales
Distribución por género: Se identifica una mayor cantidad de pacientes femeninas que masculinos en el conjunto de datos.

Evolución con la edad: El inicio de la severidad comienza a verse a partir de los 60 años (en rangos de 0.5 a 1). El volumen cerebral real en pacientes de hasta 50 años se mantiene estable entre 0.8 y 0.9.

Patrones en pacientes femeninas:
Comienza a identificarse atrofia cerebral después de los 50 años, registrando un volumen mínimo de 0.64 en una paciente de 92 años.
Existe una alta concentración de atrofia a partir de los 50 años con volúmenes entre 0.7 y 0.8, de forma transversal a la edad.

Patrones en pacientes masculinos: Se observa una marcada pendiente descendente en la disminución del volumen cerebral (con una caída pronunciada desde 0.79) a partir de los 69 años.

2. Reserva Cognitiva y Nivel Educativo
Rangos de alerta propuestos: Considerando cinco niveles de educación (Primaria, Secundaria, Técnico, Pregrado y Posgrado), se establecen umbrales de alerta para la reserva cognitiva de forma jerárquica: Posgrado (<27), segundo nivel (26), tercer nivel (25), cuarto nivel (24) y quinto nivel (21 – 22).

Comportamiento general: En pacientes femeninas, los promedios de reserva cognitiva se mantienen estables dentro de los rangos establecidos (entre 24.60 y 28.51).

Correlación: De forma global, no se observa una relación directa y determinante entre el volumen cerebral, el nivel educativo y la reserva cognitiva.

3. Análisis por Grados de Severidad
Severidad 0.5 (Atrofia Leve): Los pacientes cuentan con un volumen cerebral (en su gran mayoría hasta los 80 años) entre 0.8 y 0.70. A pesar de la atrofia leve, la reserva cognitiva se mantiene dentro de los límites preestablecidos en la mayoría de niveles educativos, a excepción del nivel de posgrado (promedio menor al esperado) y secundaria (promedio de 22.40, sujeto a un tamaño de muestra reducido).

Severidad 1: La atrofia se identifica desde los 60 años, con mayor incidencia entre las décadas de los 70 y 80 años, con volúmenes que van desde 0.76 hasta 0.66. Se observa una disminución general y alerta en la reserva cognitiva en todos los niveles educativos, con la única excepción del nivel Primaria (que mantiene un promedio de 22.67).

Severidad 2: La muestra cuenta únicamente con 2 pacientes (Femenina de 78 años con volumen de 0.7, y Masculino de 86 años con volumen de 0.67). Ambos presentan una reserva cognitiva de 15, aunque se destaca que no es posible generar conclusiones categóricas debido al tamaño reducido de la muestra.

4. Limitaciones del Estudio
Calidad de los datos: El conjunto de datos presenta variables con información incompleta para determinados pacientes, lo que limita ciertos cruces analíticos específicos.

⚠️ Aviso y Descargo de Responsabilidad (Disclaimer)
El conjunto de datos utilizado en este proyecto es exclusivamente para fines de demostración, práctica y portafolio profesional. Los datos no son de mi autoría ni de mi propiedad; su uso tiene un carácter estrictamente académico y demostrativo para ilustrar habilidades en análisis de datos, modelado y Business Intelligence.
Dimensiones externas: No se dispone de variables geográficas u otras dimensiones contextuales adicionales que permitan expandir el alcance del análisis predictivo.
