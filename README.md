# REST_API
-se observa como interactuar y probar la REST AP
se almacenara datos en una lista de python

-en que va tener diccionarios para cada articulo con el monbre del articulo como collar y el precio del articulo como 15.99.

-Para la ejecucion de la aplicacion:
   
   Api Rest suele trabajar con Jason recibira dactos de Json en la solisitud y respondera con datos de Jason en la respuesta
    Datos de Jason (jason es una cadena de texto)
    EJ'tienen claves y estan asociadas con valores  similares a un diccionario de python , con una coma se separa las claves y   valores.
    Los valores pueden ser cadenas o numeros (enteros_decimales) puede tener listas u subobjetos tambien boleanos (v o f).
   
 Imagen1
![Image text](https://github.com/tcarolina/REST_API/blob/main/imagenes/Insomia1_tienda.PNG)

--Como se crea la tienda en la API REST utilizando INSOMIA (muestra la obtencion)

  Se crea una variable para la nueva tienda que vamos añadir a nuestra lista,  y que va ser un nombre de datos de solisitud y tambien elementos que va ser una lista vacia y para empezar se muestra un diccionario con 2 claves , el nombre y los articulos, luego se añade la tienda oh nueva tienda tendra que devolver (RETURN) diremos que devuelva a la tienda nueva y tambien a un codigo de estado ( 201 ) que significa bien.
 
 Imagen2
![Image text](https://github.com/tcarolina/REST_API/blob/main/imagenes/Insomia2_tienda.PNG)  

--Como crear articulos en cada tienda 

con el / y < > pondremos nombre de cadena, : en su interior despues barra tienda, barra nombre de la tienda y luego barra del articulo la idea sera recorrer la lista de tiendas y vamos a ver si el nombre de la tienda coincide con el nombre que venia en la URL que es mi tienda. Entonces vamos a crear un nuevo elemento y su nombre sera daros de solicitud.
tendra un diccionario con dos claves, el nombre y el precio luego decimos articulos de la tienda añade un nuevo elemento, despues se realiza (RETURN) NEW ITEM 201 y sera el final de la funcion.
return 404 no fue encontrada

Imagen3
![Image text](https://github.com/tcarolina/REST_API/blob/main/imagenes/Insomia3_tienda.PNG)

--como conseguir una tienda especifica y sus articulos 

endpoint que es get store y el nombre, este nombre va a llenar el parametro name an la funcion
al continuar se revisa la lista de tiendas si el nombre coincide va a devolver esa tienda,en el diccionario FLASK lo va a convertir en JSON y si no sucede,dara mensaje tienda no encontrada 404.

Imagen4
![Image text](https://github.com/tcarolina/REST_API/blob/main/imagenes/Insomia4_tienda.PNG)

Articulos de una tiienda especifica tambien codigo es similar

Imagen5
![Image text](https://github.com/tcarolina/REST_API/blob/main/imagenes/Insomia5_tienda.PNG)
