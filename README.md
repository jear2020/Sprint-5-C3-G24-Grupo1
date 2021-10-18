# Sprint-5-C3-G24-Grupo1
Proyecto InvectaSoft


La base de datos se encuentra montada en el programa HEIDISQL 
en el proyecto se encuentra un archivo .sql donde se encuentra el script de la base de datos para la creación de tablas y la inserción de datos de prueba 

Para correr la api en netbeans se necesita importar 
la libraria Jersey 2.5.1 (JAX-RS RI)
la libraria JAX-RS 2.0 
la libraria Java EE 7 API Library 

Verificar que se encuentren importadas antes de ejercutar 

Además se debe verificar la existencia de los JAR commons-lang3-3-12-0.jar, mysql-connector-java-8.0.26.jar y gson-2.8.2.jar 
que se encuentran el la raiz del proyecto en la carpeta lib


Por útimo se debe modificar los datos de la conexión en el paquete restful.Model en el archivo Conexion.java (nombre de la base de datos [DB] y contraseña[PASSWORD]) 
con los datos configurados en el programa de base de datos usado para este proyecto 

La pagina que se debe ejecutar de inicio es la de login.html 

Usuarios de prueba 
Para ir a administrador
user: admin
pass: admin1234

Para ir a usuarios
user: usuario
pass: usuario1234

Para ir a almacén
user: almacen
pass: almacen1234
