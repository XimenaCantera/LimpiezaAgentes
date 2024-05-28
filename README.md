# LimpiezaAgentes

Instrucciones 
Para este problema, deberás entregar, de manera individual, un informe en PDF que estudie las estadísticas de un robot de limpieza reactivo, así como el enlace al repositorio en Github del código desarrollado para esta actividad. El código debe ajustarse al estilo solicita en el siguiente documento.

Dado:

Habitación de 20x20 espacios, no toroidal.
Número de agentes (1, 5, 10).
Porcentaje de celdas inicialmente sucias (80%).
Tiempo máximo de ejecución.
Realiza la siguiente simulación:

Inicializa las celdas sucias (ubicaciones aleatorias).
Todos los agentes empiezan en localidades aleatorios.
En cada paso de tiempo:
Si la celda está sucia, entonces aspira.
Si la celda está limpia, el agente elije una dirección aleatoria para moverse (unas de las 8 celdas vecinas) y elije la acción de movimiento (si no puede moverse allí, permanecerá en la misma celda).
Se ejecuta el tiempo máximo establecido.
Deberás recopilar la siguiente información durante la ejecución:

Tiempo necesario hasta que todas las celdas estén limpias (o se haya llegado al tiempo máximo).
Porcentaje de celdas limpias después de 500, 1000 y 1500 pasos de simulación.
¿Cuál es la cantidad mínima de agentes para lograr que el espacio esté limpio en menos de 1000 pasos?
Analiza cómo la cantidad de agentes impacta el tiempo dedicado, así como la cantidad de movimientos realizados. Desarrollar un informe con lo observado.
