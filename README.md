# Restaurantes-y-pedidos
Análisis y visualización de una base de datos de pedidos en restaurantes. Hecho con SQL y Python.

Este conjunto de datos se obtiene de la base de datos de SQL Server, por lo que los archivos (tablas) están relacionados entre sí. El conjunto de datos incluye la categoría, información del restaurante, información de los miembros, información del pedido, fecha, hora, ubicación, información financiera y más...

**Preguntas:**
***¿En qué ciudad y en qué período del día los miembros hacen más pedidos?***
***¿Cuál es la proporción de tipos de comidas en los restaurantes de cada ciudad?***
***¿Cuál es la proporción de pedidos en las ciudades con más restaurantes italianos?***
***¿Qué ciudades tienen más comidas veganas?***
***¿Cuál es la diferencia en el rango de precios de las comidas frías o calientes?***
***¿Cuál es la correlación entre el sexo de los miembros y el tipo de servicio?***
***¿Quiénes son los clientes que más pagan cada mes y sus ciudades?***
***¿Cuál es el total de pedidos mensuales y el total acumulado de cada restaurante a lo largo del año?***
***¿Cuál es la diferencia de pedidos mensuales para cada dos meses consecutivos en cada restaurante?***
***¿Cuáles son los meses en los que las ventas totales de cada restaurante son mayores que las ventas totales mensuales promedio del restaurante?***

#Desarrollo
**1. Contexto del conjunto de datos**
-Incluye información sobre ciudades, tipos de comida, miembros, detalles de pedidos, restaurantes y tipos de servicios.
-Permite responder preguntas relacionadas con hábitos de consumo, desempeño de restaurantes y preferencias de comida.
**2. Actividades realizadas**
*Preparación de datos:*
Se cargaron múltiples tablas en una base de datos SQLite.
Exploración inicial de las tablas para verificar columnas, filas vacías, y estructura de datos.
*Exploración de datos:*
Se identificaron patrones como los períodos del día en que los miembros hacen más pedidos, las ciudades con más restaurantes italianos o veganos, y las proporciones de tipos de comida.
*Análisis detallado:*
-Pedidos por ciudad y período del día: Se encontró que la mayoría de los pedidos ocurren en horarios de almuerzo y cena.
-Proporciones de tipos de comida por ciudad: Se analizó la relación entre los tipos de comida y la ubicación.
-Restaurantes italianos y pedidos: Se identificaron ciudades con más restaurantes italianos y su impacto en los pedidos.
-Comidas veganas: Se determinó que Ramat Hasharon, Tel Aviv y Herzelia tienen más comidas veganas.
-Precios de comida fría y caliente: No se encontraron diferencias significativas en los precios.
-Correlación entre sexo y tipo de servicio: Se observó una distribución igual entre hombres y mujeres en tipos de servicio.
*Análisis financiero y tendencias:*
-Se analizaron los miembros que más gastan por ciudad y mes.
-Se calcularon totales y acumulados de pedidos mensuales por restaurante.
-Se identificaron diferencias en ventas entre meses consecutivos y meses con ventas superiores al promedio.
*Visualizaciones:*
Se generaron gráficos para comprender patrones y proporciones de pedidos, tipos de comida, y ventas.
**3. Conclusiones principales**
*Pedidos y preferencias:*
-Los horarios de almuerzo (11:00-13:00) y cena (19:00-21:00) son los más activos.
-Ramat Hasharon tiene una mayor proporción de pedidos en restaurantes italianos, mientras que Tel Aviv y Ramat Hasharon destacan en comidas veganas.
*Eficiencia de costos y precios:*
-Los precios de comidas frías y calientes no muestran diferencias significativas.
-Los principales clientes de Givatayim gastan en promedio $50 al mes y consumen al menos dos comidas por pedido.
*Tendencias mensuales:*
Las ventas totales de los restaurantes son generalmente más altas en los primeros seis meses del año, y las variaciones mensuales reflejan la actividad comercial.
*Áreas de mejora:*
Análisis más granular puede ayudar a optimizar estrategias de precios y promociones.
**4. Métodos utilizados**
- Consultas SQL complejas (joins, CTEs, y funciones agregadas).
- Estadísticas descriptivas y visualización de datos.
- Generación de indicadores clave como proporciones, acumulados y diferencias entre períodos.


***En resumen, este archivo proporciona una visión detallada de los patrones de consumo y desempeño de restaurantes, permitiendo identificar áreas clave para mejorar la gestión operativa y financiera.***
