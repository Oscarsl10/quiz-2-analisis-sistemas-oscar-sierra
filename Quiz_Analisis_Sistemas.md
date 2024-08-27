## Quiz-2-analisis-sistemas.
### Cordial saludo.

Proyecto Tienda:

La tienda tiene la intención de implementar un programa de fidelización mensual mediante el cual premiará a tres clientes destacados, con la particularidad de que estos premios serán otorgados de manera recurrente, es decir, cada mes se llevará a cabo una nueva selección de ganadores. 

Es fundamental mantener un registro detallado de todos
los premios entregados, así como de los clientes agraciados en cada ocasión.
El proceso de selección de los ganadores se basa en la acumulación de puntos por parte
de los clientes. Cada cliente acumula puntos mediante la realización de compras, con un
sistema de bonificación especial para productos seleccionados. Los clientes también
pueden obtener puntos mediante acciones adicionales, como recomendar la tienda a
amigos o completar encuestas de satisfacción.
Una vez que un cliente acumula una cantidad determinada de puntos, se le asigna
automáticamente una entrada para el sorteo mensual. El número de entradas asignadas
a cada cliente varía según la cantidad de puntos acumulados, lo que permite una
distribución equitativa de oportunidades entre todos los participantes.
El sorteo se lleva a cabo utilizando todas las entradas acumuladas por los clientes
durante el mes, garantizando así la imparcialidad y transparencia en el proceso de
selección de los ganadores.

Además, se establece un registro histórico completo de todos los premios entregados y
los respectivos clientes agraciados, lo que facilita un seguimiento preciso y sistemático
de cada sorteo realizado por la tienda. Este registro también proporciona información
valiosa para futuras promociones y estrategias de fidelización de clientes.

• ¿Cómo podríamos diseñar una contrapropuesta para optimizar el programa de
fidelización y la selección de ganadores?

### Solución 

### Datos de entrada

•	Información de los clientes: Nombre, id, historial de compras y puntos acumulados.
•	Datos de los productos: Id de los productos y las bonificaciones especiales que algunos productos tienen.
•	Registros de datos de los sorteos anteriores: Los ganadores, premios entregados y los puntos que llegaron a obtener los clientes en cada periodo.

### Datos de salida
•	Lista de los ganadores de cada mes: Contiene la información de los tres clientes que ganaron y los detalles de los premios.
•	Registro de los sorteos y premios: Contiene la información de cada sorteo, sus ganadores y los puntos obtenidos.
•	Estadísticas para la fidelización: Contiene la información de los puntos acumulados de los clientes y su comportamiento en el sistema de ventas o en la tienda como tal.

### 2. Requerimientos 

### •	Requerimientos funcionales:

Cálculo de puntos.
Asignación de entradas.
Sorteo mensual.
Registro de los datos.
Notificación de ganadores.
Reportes de fidelización.
### •	Requerimientos no funcionales:

Seguridad.
Accesibilidad.
Escalabilidad.
Transparencia.

### Contrapropuesta:

### Mejora en la fidelización:

Se podría implementar un sistema de bonificaciones que se pueda adaptar a los hábitos de los clientes y así mismo poder incentivarlos para comprar mas productos que les interese y así mejorar más la fidelización, además de eso se pueden implementar mas sorteos en los que los clientes puedan ganar solo cumpliendo unas metas.
### Mejora en la transparencia:

También se puede implementar una interfaz o un apartado para que el cliente vea en tiempo real su acumulación de puntos y también poder mirar las posibilidades que tiene de ganar un premio, esto con el fin de mejorar la transparencia.
