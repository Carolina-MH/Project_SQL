# CINEFLIX RENTALS [SQL]

![encabezado](https://github.com/Carolina-MH/Project_SQL/raw/main/img/encabezado.png)


# Historia de negocio


En un mundo donde el streaming ha tomado el centro del escenario en la industria del entretenimiento, "Cineflix Rentals" se erige como un santuario para los amantes del cine que anhelan una experiencia más auténtica y selecta.

En "Cineflix Rentals," la pasión por las películas y el cine clásico se fusiona con la comodidad moderna. Esta tienda es un refugio cinematográfico donde los clientes pueden explorar una colección de películas en DVD, disfrutar de una experiencia de alquiler personalizada y recibir recomendaciones de películas de nuestro atento personal.

Sabemos que cada película tiene su propio encanto y que cada cliente tiene gustos únicos. Es por eso que he creado una base de datos excepcional y elegante que combina lo mejor de ambos mundos: la vasta colección de películas en DVD y la comodidad del alquiler en línea.


# Objetivos

La necesidad para introducir y utilizar una base de datos en "Cineflix Rentals" radica en:

🍿 `Gestión Eficiente de Películas y Clientes`

🍿 `Análisis y Toma de Decisiones`

🍿 `Seguimiento de Transacciones`

🍿 `Gestión de Personal`


# Exploración y limpieza de datos


La exploración y limpieza de datos son etapas fundamentales en la preparación de la base de datos para su uso eficiente. Por lo que, realizado varias consultas y operaciones para mejorar la calidad de los datos, incluyendo:

📊 `Estandarización de Datos`: Nombres de actores y categorías de películas para garantizar coherencia y facilidad en la búsqueda.

📊 `Eliminación de Datos Constantes`: Identificar y eliminar la columna "last_update" en todas la tablas,ya que contenía valores constantes, lo que no aportaba información relevante.

📊 `Creación de la Tabla "staff" y "customer"`:He utilizado la información de la tabla "rental" para generar una tabla que registre la información del personal y la otra para realizar una gestión eficiente de los clientes.


📊 `Creación de la Tabla "film_actor"`: Esta tabla, contiene únicamente los identificadores ("id") de actores y películas. Esto facilita la relación entre actores y películas sin la necesidad de consultar la tabla original, simplificando la gestión de datos.

📊 `Selección de Muestras Representativas`:He tomado muestras representativas de tablas con un gran volumen de datos, como "film_actor" reduciendo el tamaño a 10,000 filas para facilitar la manipulación y análisis.

📊 `Añadido de la Columna "category_id" en "film"` : He introducido una nueva columna en film_ denominada 'category_id'para evitar la necesidad de utilizar la tabla "old_HDD.", ya que,sus valores se repetían en el resto de tablas.

📊 `Conversiones de Tipo de Datos`:He señalado la necesidad de convertir las columnas "rental_date" y "return_date" de tipo "object" a tipo "datetime" en la tabla "rental" para facilitar análisis temporales.


# Análisis

He llevado a cabo consultas y análisis de datos para obtener información valiosa. Ejemplos:

💡Obtener la cantidad total de películas en cada categoría, ordenadas en orden DESC:

![Query1](https://github.com/Carolina-MH/Proyecto-1/blob/main/img/cantidad_total_de_películas_en_cada_categoría.png)

💡Encontrar los 10 actores que aparecen en la mayoría de las películas:

![Query2](https://github.com/Carolina-MH/Proyecto-1/blob/main/img/10_actores_que_aparecen_en_la_mayoría_de_las_películas.png)

💡Nombre de las películas que no han sido alquiladas:

![Query3](https://github.com/Carolina-MH/Proyecto-1/blob/main/img/Nombre_de_las_películas_que_no_han_sido_alquiladas.png)


# Conclusión

Todas estas actividades de exploración, limpieza y análisis de datos son esenciales para respaldar los objetivos de "Cineflix Rentals" en la gestión eficiente de películas y clientes, la toma de decisiones informadas, el seguimiento de transacciones y la gestión del personal.

![GIFT](https://github.com/Carolina-MH/Proyecto-1/blob/main/img/gif_final.png)
