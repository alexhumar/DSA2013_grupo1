Sistema de manejo de CV's

-Instalar Apache2, MySQL y PHP5 y PHP-PEAR.

-Instalar la libreria MDB2 ejecutando:
	pear install MDB2-2.5.0b5

-Instalar los drivers de MySQL para MDB2 ejecutando:
	pear install MDB2_Driver_mysql-1.5.0b4

-Crear una base de datos local con el nombre "proyecto2012" (si no conecta, verificar que las credenciales de MySQL sean las correctas en el archivo "config/database.php").

-Importar el archivo "data/proyecto2012.sql" a la base de datos.

-Acceder mediante un browser al archivo "index.php".

Las credenciales son las siguientes:

Usuarios:
	fede - fede
	ale  - ale
	juan - juan

Administrador:
	admin - admin

Secretaria:
	secretaria - secretaria

Nota: la funcion que destaca a la secretaria es la de poder marcar un CV como publico o privado.
