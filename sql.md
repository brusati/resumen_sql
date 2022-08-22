# resumen SQL

siempre primero usar `WHERE` y luego `ORDER BY`

# resumen SQL

siempre primero usar `WHERE` y luego `ORDER BY`

- [Tablas](https://github.com/brusati/resumen_sql/blob/main/sql.md#tablas)
	- [Crear tablas](https://github.com/brusati/resumen_sql/blob/main/sql.md#crear-tablas)
	- [Agregar columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#agregar-columna)
	- [Eliminar columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#eliminar-columna)
	- [Tipos de datos](https://github.com/brusati/resumen_sql/blob/main/sql.md#tipos-de-datos)
	- [Agregar filas](https://github.com/brusati/resumen_sql/blob/main/sql.md#agregar-filas)
	- [Eliminar filas](https://github.com/brusati/resumen_sql/blob/main/sql.md#eliminar-filas)
	- [Actualizar valores](https://github.com/brusati/resumen_sql/blob/main/sql.md#actualizar-valores-de-la-tabla)
	- [Clasificar resultados](https://github.com/brusati/resumen_sql/blob/main/sql.md#clasificar-resultados)

- [Columnas](https://github.com/brusati/resumen_sql/blob/main/sql.md#columnas)
	- [Seleccionar toda la tabla](https://github.com/brusati/resumen_sql/blob/main/sql.md#seleccionar-toda-la-tabla)
	- [Seleccionar todas las filas de ciertas columnas](https://github.com/brusati/resumen_sql/blob/main/sql.md#seleccionar-todas-las-filas-de-ciertas-columnas)
	- [Seleccionar todas las filas de ciertas columnas y ordenarlas](https://github.com/brusati/resumen_sql/blob/main/sql.md#seleccionar-todas-las-filas-de-ciertas-columnas-y-ordenarlas)
	- [Seleccionar todos los valores posibles de una columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#seleccionar-todos-los-valores-posibles-de-una-columna)
	- [Contar cuántos valores posibles tiene una columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#contar-cuántos-valores-posibles-tiene-una-columna)
	- [Contar cuántas filas tiene una determinada columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#contar-cuántas-filas-tiene-una-determinada-columna)
	- [Contar cuántas filas que cumplen una condición tiene una determinada columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#contar-cuántas-filas-que-cumplen-una-condición-tiene-una-determinada-columna)
	- [Contar cuántos valores hay en una columna para cada valor posible de otra columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#contar-cuántos-valores-hay-en-una-columna-para-cada-valor-posible-de-esa-columna)
	- [Promediar los valores de una determinada columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#promediar-los-valores-de-una-determinada-columna)
	- [Promediar los valores que cumplen una condición de una determinada columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#promediar-los-valores-que-cumplen-una-condición-de-una-determinada-columna)
	- [Promediar los valores de una columna para cada valor posible de otra columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#promediar-los-valores-de-una-columna-para-cada-valor-posible-de-otra-columna)
	- [Sumar los valores de una determinada columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#sumar-los-valores-de-una-determinada-columna)
	- [Sumar los valores que cumplen una condición de una determinada columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#sumar-los-valores-que-cumplen-una-condición-de-una-determinada-columna)
	- [Sumar los valores de una columna para cada valor posible de otra columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#sumar-los-valores-de-una-columna-para-cada-valor-posible-de-otra-columna)


- [Filas](https://github.com/brusati/resumen_sql/blob/main/sql.md#filas)
	- [Seleccionar primeras n filas](https://github.com/brusati/resumen_sql/blob/main/sql.md#seleccionar-primeras-n-filas)
	- [Seleccionar las filas que cumplen una condición en una o más columnas](https://github.com/brusati/resumen_sql/blob/main/sql.md#seleccionar-las-filas-que-cumplen-una-condición-en-una-columna)
	- [Seleccionar las filas cuyo valor en una columna está incluído en un string](https://github.com/brusati/resumen_sql/blob/main/sql.md#seleccionar-las-filas-cuyo-valor-en-una-columna-está-incluído-en-un-string)
 

- [Trabajando con 2 tablas](https://github.com/brusati/resumen_sql/blob/main/sql.md#trabajando-con-dos-tablas)
	- [Unions](https://github.com/brusati/resumen_sql/blob/main/sql.md#unions)
	- [Joins](https://github.com/brusati/resumen_sql/blob/main/sql.md#joins)
 
 
- [Algunas consultas interesantes](https://github.com/brusati/resumen_sql/blob/main/sql.md#algunas-consultas-interesantes)
	- [Obtener el n mayor o menor elemento de una columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#obtener-el-n-mayor-o-menor-elemento-de-una-columna)
	- [Obtener el máximo o mínimo de una columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#obtener-el-máximo-o-mínimo-de-una-columna)
	- [Obtener el máximo o mínimo de una columna numérica para cada categoría de otra columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#obtener-el-máximo-o-mínimo-de-una-columna-numérica-para-cada-categoría-de-otra-columna)
	- [Agregar una columna que sea el resultado de aplicarle una función a una columna numérica para cada categoría de una columna](https://github.com/brusati/resumen_sql/blob/main/sql.md#agregar-una-columna-que-sea-el-resultado-de-aplicarle-una-función-a-una-columna_numérica-para-cada-categoría-de-una-columna)
	- [Agregar una columna que numere elementos de una columna por cada categoría](https://github.com/brusati/resumen_sql/blob/main/sql.md#agregar-una-columna-que-numere-elementos-de-una-columna-por-cada-categoría)
	- [Obtener el n elemento de cada categoría en una columna ordenado por una columna numérica](https://github.com/brusati/resumen_sql/blob/main/sql.md#obtener-el-n-elemento-de-cada-categoría-en-una-columna-ordenado-por-una-columna_numérica)

## tablas

### crear tablas
```
CREATE TABLE table_name (
  column_name TIPO_DE_DATO,
  another_column_name TIPO_DE_DATO
);
```

si queremos que una columna no pueda tener valores nulos `column_name TIPO_DE_DATO NOT NULL,`

si queremos que una columna no pueda tener valores repetidos `column_name TIPO_DE_DATO UNIQUE,`

si queremos que una columna no pueda tener valores repetidos ni tampoco nulos `column_name TIPO_DE_DATO PRIMARY KEY,`

si queremos dejar un valor predeterminado en caso de que la fila no contenga ningún dato para esa columna `column_name TIPO_DE_DATO DEFAULT valor_default,`

### agregar columna
`ALTER TABLE table_name ADD column TIPO_DE_DATO;`

### eliminar columna
`ALTER TABLE table_name DROP COLUMN column;`

### tipos de datos

| Data type     | Description                                                     |
| -----------   | -----------                                                     |
| INT           | Whole numbers                                                   |
| DECIMAL(M,N)  | Decimal numbers with M total digits of which N are decimals     |
| VARCHAR(N)    | String of length N                                              |
| DATE          | 'YYYY-MM-DD'                                                    |
| TIMESTAMP     | 'YYYY-MM-DD HH:MM:SS'                                           |

### agregar filas
`INSERT INTO table_name VALUES(v1, ..., vn);`

donde `n` es la cantidad de columnas que tiene la tabla

aclaración: el orden de los `v1, ..., vn` es el mismo orden que tienen las columnas en la tabla

ejemplo: si tenemos una tabla cuyas columnas son `id` y `nombre` podríamos agregar una fila haciendo `INSERT INTO student VALUES(1, 'Nacho');`

si no queremos agregar datos para todas las columnas entonces podemos realizar lo siguiente: `INSERT INTO table_name(column1, column2) VALUES(v1, v2);`

### eliminar filas
```
DELATE FROM table_name
WHERE nombre = valor_de_referencia;
```

### actualizar valores de la tabla
```
UPDATE table_name
SET column = nuevo_valor
WHERE column = valor_de_referencia
```

ejemplo: si tenemos una tabla cuyas columnas son `id`, `nombre` y `nacionalidad` podríamos cambiar la `nacionalidad` al valor `desconocido` para todas las personas cuyo nombre sea `Ignacio`
```
UPDATE table_name
SET nacionalidad = 'desconocido'
WHERE nombre = 'Ignacio'
```

en la línea del `WHERE` podemos utilizar operaciones lógicas como `OR`, `AND`, `>`, `<`, `=`, `>=`, `<=`, `<>`

atención: `<>` equivale a `!=`

si queremos modificar todas las filas de una columna, entonces simplemente eliminamos la línea del `WHERE`

si queremos modificar más de una columna entonces las agregamos con `,`

ejemplo: `SET column1 = nuevo_valor_1, column2 = nuevo_valor_2`


### clasificar resultados
```
SELECT *,
	CASE WHEN condición THEN resultado_para_esta_condición
	ELSE resultado_para_otros_casos
	END AS nombre_nueva_columna
FROM table_name;
```

ejemplo: crear una nueva columna en la que el valor sea `true` si el nombre del jugador empieza con la letra `L` y `false` en caso contrario

| jugador          | país    | goles      |
| ----             | ------- | ---------- |
| Gustavo Bou      | ARG     | 10         |
| Lisandro López   | ARG     | 8          |
| Lautaro Martínez | ARG     | 15         |
| Diego Milito     | ARG     | 7          |
| Rubén Paz        | URU     | 4          |
| Luis Suárez      | URU     | 11         |
| Edinson Cavani   | URU     | 11         |

```
SELECT *,
	CASE WHEN nombre LIKE 'L%' THEN 'true'
	ELSE 'false'
	END AS empieza_con_L
FROM table_name;
```

| jugador          | país    | goles      | empieza_con_L |
| ----             | ------- | ---------- | -----------   |
| Gustavo Bou      | ARG     | 10         | false         |
| Lisandro López   | ARG     | 8          | true          |
| Lautaro Martínez | ARG     | 15         | true          |
| Diego Milito     | ARG     | 7          | false         |
| Rubén Paz        | URU     | 4          | false         |
| Luis Suárez      | URU     | 11         | true          |
| Edinson Cavani   | URU     | 11         | false         |


## columnas

### seleccionar toda la tabla
`SELECT * FROM table_name;`

### seleccionar todas las filas de ciertas columnas
```
SELECT column, another_column 
FROM table_name;
```

### seleccionar todas las filas de ciertas columnas y ordenarlas
```
SELECT column, another_column 
FROM table_name
ORDER BY another_column ASC;
```

el `ASC` marca que queremos un orden ascendente, mientras que el `DESC` indica que queremos un orden descendente

si queremos ordenar por varias columnas (primero ordenar por una, luego por otra):  
```
SELECT column, another_column 
FROM table_name
ORDER BY another_column ASC, column DESC;
```

### seleccionar todos los valores posibles de una columna
```
SELECT DISTINCT column
FROM table_name;
```

### contar cuántos valores posibles tiene una columna
```
SELECT COUNT(DISTINCT column)
FROM table_name;
```

### contar cuántas filas tiene una determinada columna
atención: el `COUNT` cuenta valores no nulos
```
SELECT COUNT(column)
FROM table_name;
```

### contar cuántas filas que cumplen una condición tiene una determinada columna
atención: el `COUNT` cuenta valores no nulos
```
SELECT COUNT(column)
FROM table_name
WHERE column = valor_de_referencia;
```

ejemplo:
```
SELECT COUNT(nationality)
FROM artists
WHERE nationality = 'Italian';
```

### contar cuántos valores hay en una columna para cada valor posible de esa columna
atención: el `COUNT` cuenta valores no nulos

```
SELECT COUNT(column), another_column
FROM table_name
GROUP BY another_column;
```

ejemplo:
```
SELECT COUNT(nationality), nationality
FROM artists
GROUP BY nationality;
```


### promediar los valores de una determinada columna
```
SELECT AVG(column)
FROM table_name;
```

### promediar los valores que cumplen una condición de una determinada columna
```
SELECT AVG(column)
FROM table_name
WHERE column = valor_de_referencia;
```

ejemplo:
```
SELECT AVG(paintings)
FROM artists
WHERE nationality = 'Italian';
```

### promediar los valores de una columna para cada valor posible de otra columna
```
SELECT AVG(column), another_column
FROM table_name
GROUP BY another_column;
```

ejemplo:
```
SELECT AVG(paintings), nationality
FROM artists
GROUP BY nationality;
```

### sumar los valores de una determinada columna
```
SELECT SUM(column)
FROM table_name;
```

### sumar los valores que cumplen una condición de una determinada columna
```
SELECT SUM(column)
FROM table_name
WHERE column = valor_de_referencia;
```

ejemplo:
```
SELECT SUM(paintings)
FROM artists
WHERE nationality = 'Italian';
```

### sumar los valores de una columna para cada valor posible de otra columna
```
SELECT SUM(column), another_column
FROM table_name
GROUP BY another_column;
```

ejemplo:
```
SELECT SUM(paintings), nationality
FROM artists
GROUP BY nationality;
```



## seleccionar filas

### seleccionar primeras n filas
```
SELECT *
FROM table_name
LIMIT n;
```

### seleccionar las filas que cumplen una condición en una columna
```
SELECT *
FROM table_name
WHERE column = valor_de_referencia;
```

ejemplo:
```
SELECT *
FROM artists
WHERE nationality = 'French';
```

en lugar de usar una serie de `OR`s podemos utilizar `WHERE column IN (valor1, valor2, ...)`

### seleccionar las filas cuyo valor en una columna está incluído en un string
```
SELECT *
FROM table_name
WHERE column LIKE pattern;
```

atención, el `pattern` puede ser de las siguientes maneras:
- si queremos que el string exacto --> `palabra`
- si queremos cualquier string que termine con un cierto pattern --> `%palabra`
- si queremos cualquier string que empiece con un cierto pattern --> `palabra%`
- si queremos cualquier string que contenga un cierto pattern --> `%palabra%`



## trabajando con dos tablas

### unions

- las tablas a unir deben tener la misma cantidad de columnas
- las columnas deben tener un tipo de dato similar

```
SELECT column1, column2, etc
FROM table1
UNION
SELECT column3, column4, etc
FROM table2;
```

### joins

- los usamos cuando dos tablas tienen una columna en común
- queremos combinar filas de 2 o más tablas basados en una columna en común

```
SELECT tabla.columna, tabla.otra_columna, otra_tabla.otra_otra_columna
FROM tabla
JOIN otra_tabla
ON tabla.columna_común = otra_tabla.columna_común
```

ejemplo: si tenemos una tabla `city` cuyas columnas son `countrycode`, `nombre` y `population` y tenemos otra tabla `country` en la que tenemos las columnas `countrycode`, `lifeexpectancy` podríamos joinear ambas tablas usando la columna en común `countrycode`
```
SELECT city.countrycode, city.name, country.lifeexpectancy
FROM city
JOIN country
ON city.countrycode = country.countrycode;
```

tenemos diferentes tipos de `joins`:
- `JOIN` toma todos los valores de `tabla` y `otra_tabla` en los que la columna `columna_común` de ambas tablas no es nula
- `LEFT JOIN` toma todos los valores en los que la columna `columna_común` de `tabla` no es nula
- `RIGHT JOIN` toma todos los valores en los que la columna `columna_común` de `otra_tabla` no es nula
- `FULL OUTER JOIN` toma todos los valores de `tabla` y `otra_tabla` por más que sean nulos









## algunas consultas interesantes


### obtener el n mayor o menor elemento de una `columna`
`DESC` para mayor y `ASC` para menor

el `OFFSET` saltea la cantidad de registros indicados antes de dar la respuesta

```
SELECT *
FROM table_name
ORDER BY columna DESC
LIMIT 1
OFFSET n-1;
```

ejemplo: obtener toda la información del máximo goleador

| jugador          | país    | goles      |
| ----             | ------- | ---------- |
| Gustavo Bou      | ARG     | 10         |
| Lisandro López   | ARG     | 8          |
| Lautaro Martínez | ARG     | 15         |
| Diego Milito     | ARG     | 7          |
| Rubén Paz        | URU     | 4          |
| Luis Suárez      | URU     | 11         |
| Edinson Cavani   | URU     | 11         |

```
SELECT *
FROM table_name
ORDER BY goles DESC
LIMIT 1
OFFSET 1-1;
```

| jugador          | país    | goles      |
| ----             | ------- | ---------- |
| Lautaro Martínez | ARG     | 15         |


### obtener el máximo o mínimo de una `columna`
```
SELECT MAX(columna)
FROM table_name;
```


### obtener el máximo o mínimo de una `columna_numérica` para cada categoría de otra `columna`
```
SELECT columna, MAX(columna_numérica)
FROM table_name
GROUP BY columna;
```

ejemplo:

| jugador        | país    | goles      |
| ----           | ------- | ---------- |
| Gustavo Bou    | ARG     | 10         |
| Lisandro López | ARG     | 8          |
| Rubén Paz      | URU     | 15         |
| Luis Suárez    | URU     | 7          |

```
SELECT país, MAX(goles)
FROM table_name;
GROUP BY país;
```

| país    | max    |
| ------- | ------ |
| ARG     | 10     |
| URU     | 15     |


### obtener los n máximos o mínimos de una `columna_numérica` para cada categoría de otra `columna`
`DESC` para máximo y `ASC` para mínimo

atención: el `RANK` asgina el mismo número ante valores duplicados pero saltea una posición cuando pasa al siguiente número

```
SELECT *
FROM (
	SELECT *, RANK() OVER(PARTITION BY columna ORDER BY columna_numérica DESC) AS rank
	FROM table_name
) AS sub_table
WHERE rank < n;
```

ejemplo: encontrar los 2 máximos goleadores de cada país

| jugador          | país    | goles      |
| ----             | ------- | ---------- |
| Gustavo Bou      | ARG     | 10         |
| Lisandro López   | ARG     | 8          |
| Lautaro Martínez | ARG     | 15         |
| Diego Milito     | ARG     | 7          |
| Rubén Paz        | URU     | 4          |
| Luis Suárez      | URU     | 11         |
| Edinson Cavani   | URU     | 11         |

```
SELECT *
FROM (
	SELECT *, RANK() OVER(PARTITION BY país ORDER BY goles DESC) AS rank
	FROM table_name
) AS sub_table
WHERE rank < 3;
```

| jugador          | país    | goles      | rank |
| ----             | ------- | ---------- | ---- |
| Lautaro Martínez | ARG     | 15         | 1    |
| Gustavo Bou      | ARG     | 10         | 2    |
| Luis Suárez      | URU     | 11         | 1    |
| Edinson Cavani   | URU     | 11         | 1    |

observar que tanto a `Luis Suárez` como a `Edinson Cavani` les asignó el número 1

también observar que a `Rubén Paz` le hubiera asignado el número 3, no el número 2


### agregar una columna que sea el resultado de aplicarle una función a una `columna_numérica` para cada categoría de una `columna`
las funciones podrían ser el máximo, el mínimo, el promedio, la suma o la cuenta

```
SELECT *,
MAX(columna_numérica) OVER(PARTITION BY columna) AS nuevo_nombre
FROM table_name;
```

ejemplo:

| jugador        | país    | goles      |
| ----           | ------- | ---------- |
| Gustavo Bou    | ARG     | 10         |
| Lisandro López | ARG     | 8          |
| Rubén Paz      | URU     | 15         |
| Luis Suárez    | URU     | 7          |

```
SELECT *,
MAX(goles) OVER(PARTITION BY país) AS max_país
FROM table_name;
```

| jugador        | país    | goles      | max_país  |
| ----           | ------- | ---------- | --------  |
| Gustavo Bou    | ARG     | 10         | 10        |
| Lisandro López | ARG     | 8          | 10        |
| Rubén Paz      | URU     | 15         | 15        |
| Luis Suárez    | URU     | 7          | 15        |


### agregar una columna que numere elementos de una `columna` por cada categoría
```
SELECT *,
ROW_NUMBER() OVER(PARTITION BY columna) as number_in_categoría
FROM table_name;
```

ejemplo:

| jugador        | país    | goles      |
| ----           | ------- | ---------- |
| Gustavo Bou    | ARG     | 10         |
| Lisandro López | ARG     | 8          |
| Rubén Paz      | URU     | 15         |
| Luis Suárez    | URU     | 7          |

```
SELECT *,
ROW_NUMBER() OVER(PARTITION BY país) as number_in_categoría
FROM table_name;
```

| jugador        | país    | goles      | number_in_categoría  |
| ----           | ------- | ---------- | --------             |
| Gustavo Bou    | ARG     | 10         | 1                    |
| Lisandro López | ARG     | 8          | 2                    |
| Rubén Paz      | URU     | 15         | 1                    |
| Luis Suárez    | URU     | 7          | 2                    |


### obtener el n elemento de cada categoría en una `columna` ordenado por una `columna_numérica`
```
SELECT *
FROM (
	SELECT *,
	ROW_NUMBER() OVER(PARTITION BY columna ORDER BY columna_numérica) AS rn
	FROM table_name
) AS sub_table
WHERE rn = n;
```

ejemplo: obtener la tercera compra de cada usuario ordenado por la fecha en la que se hicieron esas compras

| user | producto   | fecha      |
| ---  | -------    | ---------- |
| 1    | gorra      | 01/02      |
| 2    | lentes     | 05/03      |
| 1    | pelota     | 12/10      |
| 1    | short      | 07/08      |
| 2    | camiseta   | 09/09      |
| 2    | toallón    | 07/11      |

```
SELECT *
FROM (
	SELECT *,
	ROW_NUMBER() OVER(PARTITION BY user ORDER BY fecha) AS rn
	FROM table_name
) AS sub_table
WHERE rn = 3;
```

| user | producto   | fecha      | rn  |
| ---  | -------    | ---------- | --- |
| 1    | pelota     | 12/10      | 3   |
| 2    | toallón    | 07/11      | 3   |


