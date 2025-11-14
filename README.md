### **🛒 Challenge Data Science – Análisis de Tiendas Alura Store LATAM**


**📘 Introducción**

El objetivo de este proyecto es analizar el rendimiento de cuatro tiendas de Alura Store LATAM utilizando datos reales de ventas, productos, calificaciones, costos de envío y ubicación geográfica.
A partir de este análisis, se busca responder la pregunta principal:

¿Qué tienda debería vender el Sr. Juan y cuál sería mejor cerrar?

Además, se desarrolla un desafío extra que incluye el análisis geográfico de las ventas mediante mapas y gráficos de dispersión utilizando latitud y longitud.



🎯 Objetivos del análisis

Calcular los ingresos totales por tienda.

Identificar las categorías más y menos vendidas.

Encontrar los productos más y menos vendidos.

Analizar la calificación promedio por tienda.

Evaluar el costo de envío promedio.

Analizar la distribución geográfica con datos de latitud y longitud.

Elaborar una recomendación final respaldada con datos y visualizaciones.



🧠 Desarrollo del Proyecto



🛍️ 1. Ingresos Totales por Tienda

Se sumaron los valores de la columna Precio para cada tienda.

Resultados:

Tienda 1: $1,150,880,400

Tienda 2: $1,116,343,500

Tienda 3: $1,098,019,600

Tienda 4: $1,038,375,700

➡️ La Tienda 1 es la que más ingresa.
➡️ La Tienda 4 es la que menos ingresa.



📦 2. Categorías más y menos vendidas

Se utilizó value_counts() por categoría en cada tienda.

En general:

Las categorías Tecnología y Accesorios son las más vendidas.

Las menos vendidas cambian según tienda, aunque suelen incluir categorías de menor rotación.



⭐ 3. Calificación promedio por tienda
Tienda	Calificación promedio
Tienda 1	3.97
Tienda 2	4.03
Tienda 3	4.04
Tienda 4	3.99

➡️ Tienda 3 tiene la mejor satisfacción de clientes.
➡️ Tienda 1 tiene la más baja.



📈 4. Productos más y menos vendidos

Esto permitió identificar los productos líderes y los de menor rotación.

Los costos se mantienen similares, aunque con variaciones pequeñas entre tiendas.




🌍 6. Desafío Extra – Análisis geográfico

Se utilizaron las columnas lat y lon para generar:

Gráficos de dispersión de ventas.

Mapas con puntos por tienda.

Heatmaps para ver la concentración de ventas.

El análisis geográfico ayuda a identificar zonas con alta demanda o donde una tienda tiene bajo rendimiento comparado con su región.



📝 Conclusión y Recomendación Final
 **¿Qué tienda debería vender el Sr. Juan?**

❌ ¿Qué tienda sería recomendable cerrar?

→ La Tienda 4
Porque:

Tiene los ingresos más bajos.

No destaca en ninguna categoría clave.

Su distribución geográfica tiene menor densidad.

Su rendimiento es consistentemente inferior comparado con las demás.


Proyecto realizado por Nayeli Vilchis.
Análisis completo, visualizaciones, conclusiones y aplicación del desafío extra.
