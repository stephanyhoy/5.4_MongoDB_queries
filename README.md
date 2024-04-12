# Entrega 5.4: MongoDB queries

Descripción

Tenemos una colección de Restaurantes en la ciudad de Nueva York, y necesitamos las siguientes consultas:

1. Escribe una consulta para mostrar todos los documentos en la colección Restaurantes.
2. Escribe una consulta para mostrar el restaurante_id, name, borough y cuisine de todos los documentos en la colección Restaurantes.
3. Escribe una consulta para mostrar el restaurante_id, name, borough y cuisine, pero excluyendo el campo _id por todos los documentos en la colección Restaurantes.
4. Escribe una consulta para mostrar restaurando_id, name, borough y zip code, pero excluyendo el campo _id por todos los documentos en la colección Restaurantes.
5. Escribe una consulta para mostrar todos los restaurantes que están en el Bronx.
6. Escribe una consulta para mostrar los primeros 5 restaurantes que están en el Bronx.
7. Escribe una consulta para mostrar los 5 restaurantes después de saltar los primeros 5 que sean del Bronx.
8. Escribe una consulta para encontrar los restaurantes que tienen algún score más grande de 90.
9. Escribe una consulta para encontrar los restaurantes que tienen un score más grande que 80 pero menos que 100.
10. Escribe una consulta para encontrar los restaurantes que están situados en una longitud inferior a -95.754168.
11. Escribe una consulta de MongoDB para encontrar los restaurantes que no cocinan comer 'American ' y tienen algún score superior en 70 y longitud inferior a -65.754168.
12. Escribe una consulta para encontrar los restaurantes que no preparan comer 'American' y tienen algún score superior en 70 y que, además, se localizan en longitudes inferiores a -65.754168. Nota: Fez esta consulta sin utilizar operador $and.
13. Escribe una consulta para encontrar los restaurantes que no preparan comer 'American ', tienen alguna nota 'A' y no pertenecen a Brooklyn. Se tiene que mostrar el documento según la cuisine en orden descendente.
14. Escribe una consulta para encontrar el restaurante_id, name, borough y cuisine para aquellos restaurantes que contienen 'Wil' en las tres primeras letras en su nombre.
15. Escribe una consulta para encontrar el restaurante_id, name, borough y cuisine para aquellos restaurantes que contienen 'ces' en las últimas tres letras en su nombre.
16. Escribe una consulta para encontrar el restaurante_id, name, borough y cuisine para aquellos restaurantes que contienen 'Riego' en cualquier lugar de su nombre.
17. Escribe una consulta para encontrar los restaurantes que pertenecen al Bronx y preparan platos Americanos o chinos.
18. Escribe una consulta para encontrar el restaurante_id, name, borough y cuisine por aquellos restaurantes que pertenecen a Staten Island, Queens, Bronx o Brooklyn.
19. Escribe una consulta para encontrar el restaurante_id, name, borough y cuisine para aquellos restaurantes que NO pertenecen a Staten Island, Queens, Bronx o Brooklyn.
20. Escribe una consulta para encontrar el restaurante_id, name, borough y cuisine para aquellos restaurantes que consigan una nota menor que 10.
21. Escribe una consulta para encontrar el restaurante_id, name, borough y cuisine para aquellos restaurantes que preparan marisco ('seafood') excepto si son 'American ', 'Chinese' o el name del restaurante empieza con letras 'Wil'.
22. Escribe una consulta para encontrar el restaurante_id, name y gradas para aquellos restaurantes que consigan un grade de "A" y un score de 11 con un ISODate "2014-08-11T00:00:00Z".
23. Escribe una consulta para encontrar el restaurante_id, name y gradas para aquellos restaurantes donde el 2.º elemento del array de grados contiene un grade de "A" y un score 9 con un ISODate "2014-08-11T00:00:00Z".
24. Escribe una consulta para encontrar el restaurante_id, name, dirección y ubicación geográfica para aquellos restaurantes donde el segundo elemento del array coord contiene un valor entre 42 y 52.
25. Escribe una consulta para organizar los restaurantes por nombre en orden ascendente.
26. Escribe una consulta para organizar los restaurantes por nombre en orden descendente.
27. Escribe una consulta para organizar los restaurantes por el nombre de la cuisine en orden ascendente y por el barrio en orden descendente.
28. Escribe una consulta por saber si las direcciones contienen la calle.
29. Escribe una consulta que seleccione todos los documentos en la colección de restaurantes donde los valores del campo coord es de tipo Double.
30. Escribe una consulta que seleccione el restaurante_id, name y grade para aquellos restaurantes que devuelven 0 como residuo después de dividir alguno de sus score por 7.
31. Escribe una consulta para encontrar el name de restaurante, borough, longitud, latitud y cuisine para aquellos restaurantes que contienen 'mi' en algún lugar de su name.
32. Escribe una consulta para encontrar el name de restaurante, borough, longitud, latitud y cuisine para aquellos restaurantes que contienen 'Mad' como primeras tres letras de su name.

⭐ Nivel 1
17 consultas correctas.

⭐⭐ Nivel 2
Entre 17 y 25 consultas correctas.

⭐⭐⭐ Nivel 3
Más de 25 consultas correctas.
