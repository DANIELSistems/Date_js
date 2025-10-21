🧠 1. Descripción del objeto Date

El objeto Date en JavaScript se usa para trabajar con fechas y tiempos.
Permite obtener, establecer y modificar la fecha y hora actual o cualquier otra fecha específica.

👉 Uso principal:
Manejar fechas y horas en una aplicación web, como mostrar la hora actual, calcular diferencias entre fechas, programar eventos, etc.

🧩 2. Principales propiedades del objeto Date

En realidad, Date no tiene muchas propiedades directas, pero sí varios métodos útiles para obtener o establecer partes de la fecha.

Propiedad / Método	Descripción
Date.length	Devuelve el número de argumentos que recibe el constructor (0).
Date.prototype	Permite añadir métodos personalizados a todos los objetos Date.
⚙️ 3. Principales métodos del objeto Date
🔹 Métodos para obtener información
Método	Descripción	Ejemplo
getFullYear()	Año completo (por ejemplo 2025)	fecha.getFullYear()
getMonth()	Mes (0-11) — Enero = 0	fecha.getMonth()
getDate()	Día del mes (1-31)	fecha.getDate()
getDay()	Día de la semana (0-6) — Domingo = 0	fecha.getDay()
getHours()	Hora (0-23)	fecha.getHours()
getMinutes()	Minutos (0-59)	fecha.getMinutes()
getSeconds()	Segundos (0-59)	fecha.getSeconds()
🔹 Métodos para establecer información
Método	Descripción
setFullYear(año)	Establece el año
setMonth(mes)	Establece el mes
setDate(día)	Establece el día
setHours(hora)	Establece la hora