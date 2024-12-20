Problema:
La empresa FastDelivery, que ofrece un servicio de entrega de alimentos, cuenta con una base de datos de clientes y pedidos en constante crecimiento.
Inicialmente, toda la información de sus clientes, como nombre, dirección y teléfono, se almacenaba en una hoja de cálculo simple en Excel.
Sin embargo, con el tiempo, esa hoja ha crecido considerablemente, y ahora han decidido contratarte para manipular los datos y optimizar su análisis para estudios futuros.

Padronizar los nombres de los clientes en letra mayúscula
Padronizar la columna de teléfonos al formato XX XXXXX-XXXX
Crear una columna únicamente con los códigos postales
Separar la dirección en dos columnas: calle y número
Padronizar los nombres de los clientes en letra mayúscula
Para facilitar la búsqueda y evitar duplicidades causadas por variaciones en la capitalización de los nombres, se debe convertir todos los nombres a mayúsculas. Esto puede hacerse con una función que aplique .str.upper() a la columna de nombres.
