# TEMA 4
## ESTRUCTURA CLIENTE-USUARIO
cliente: es el sistema que precisa servicios
servidor: es el sistema que los proporciona
peticion-respuesta
## PROTOCOLO LDAP
se utiliza para acreditar a los usuarios ,busca datos y da permisos y da la posibilidad de replicar la base de datos
es como una base de datos para almacenar escritorios
## CONCEPTO DE DOMINIO ,SUBDOMINIOS.REQUISITOS PARA UN DOMINIO
cuando creas una pagina web , el nombre de dominio se establece para que nos acordemos facilmente de donde queremos acceder, en vez de ser de numeros.
Recomendado usar el .com , las geolocalizadas son las .es
y las org para organizaciones sin animos de lucro
.net protocolos de internet
- para crear un dominio necesitamos un servidor, windows R,etc
## CONCEPTOS CLAVE DE ACTIVE DIRECTORY 
- objeto: un usuario,una impresora,etc componentes que conforman el directorio
- directorio: repositorio que guarda informacion
- dominio: conjunto de objetos dentro del directorio dentro de un "bosque"puede haber varios dominios 
lo mejor para usar en caso de tener varios correos es el programa outlook donde puedes meter todas tus cuentas cada cuenta de correo crea un archivo y el programa te lo gestiona (pst o ost)
- controlador de dominio:conjunto de objetos  del directorio 
- arboles : universidad de granada,jaen, es decir,red local
- bosque: por ejemplo la red de universidad de españa, red nacional
- unidades de organizacion: contenedor de objetos para organizar jerarquicamente dentro del dominio
- relaciones de confianza: metodo de comunicacion de los dominios
          - unidireccional
          - bidireccional
          - transitivas
- delegacion de control entre dominios: permite a los usuarios de un dominio administrar recursos de otro dominio. 
es recomendable que haya varias personas que puedan acceder al sistema en caso de ser una empresa con un numero considerable de personas