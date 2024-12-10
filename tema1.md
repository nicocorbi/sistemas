# Examen
## Componentes del ordenador
### Tema 1
#### partes del pc:
     - caja
     - placa base
     - fuente de alimentacion
     - CPU
     - GPU
     - sistema de disipacion (ventilador o liquida)
     - disco duro (mecanico a poder ser) SSD o MDD
     - grafica
     - memoria ram
     - tarjeta de sonido(a dia de hoy esta integrada en la placa)
     - tarjeta de red
     - unidades de almacenamiento adicionales como CD-ROM o discos secundarios
     - perifericos de entrada y salida (teclado y raton)

- administrador de dispositivos : nos muestra una lista de todos los componentes hardware conectados y es donde podemos actualizar drivers, podemos ver si todo funciona correctamente y si algo no funciona bien nos apareceran iconos amarillos o rojos, es muy importante tener los dirvers de la grafica actualizados.

- para que todo funciona correctamente debemos tener una arquitectura interna correcta(CPU,UC y ALU)

- unidad central de proceso (CPU) ejecuta instrucciones de un  progama 
- unidad de control (UC) su tarea es recibir informacion para intrepetarla y procesarla
- unidad aritmetico-logica(ALU) calcula operaciones aritmeticas

- memoria principal = random acces memory, se utliza cuando necesitamos almacenar ciertos procesos que requieren mayor rapidez que un disco duro.
funciona de esta manera: disco duro-ram-cache-cpu

- bases: vias de comunicacion donde se comunican las diferentes partes del ordenador

- ciclo de instruccion: conjunto de pasos para procesar la instruccion de un programa

#### tipos y topologias de red
una red de ordenadores es un conjunto de equipos interconectados entre si que permiten compartir recursos e informacion para ello hace falta una tarjeta de red 
- PAN como por ejemplo el adaptador del raton , el bluetoh
- WLAN red LAN inalambrica 
- LAN red de una area local 
- MAN red de area metropolitana puede abarcar varios edificios
- WAN red de area externa son las que usan las compañias de moviles y permiten conectar todo el pais 

- conectores de red 
     - BNC se usaba antes para las camaras, desventaja:un cable por camara
     - RJ45 cable de ethernet de 8 pines, es el mas frecuente
     - inalambrica: wifi, no usa cables
el bluetoh es PAN 
#### mapa fisico y logico de una red
- mapa fisico: se usan para distribuis y estructurar como va la red en una zona del mundo real
- mapa logico: documentacion con los aspectos internos de la red , saber que direccion ip tiene cara pc.

ip config/all en la tabla de comandos  para darte todos los datos sobre la ip del ordenador
#### arquitectura del sistema operativo
- necleo de sistema se encarga de trabajar con la cpu y la ram 
- API conjunto de servicios que ofrece el os a las aplicaciones
- sistema de archivos carpetas para almacenar cosas
- controladores de dirvers tanto manual como automatico sirve para que todas las partes del pc funcionen correctamente y actualmemte se instalan solos en las ultimas versiones.
#### funciones del sistema operativo
- administrador de procesos : decide el orden de procesamiento de los programas
- administrador de recursos : asigna recursos a laos diferentes programas 
- control de operaciones de entrada y salida : teclado y raton 
- administracion de prueba ram
- recuperacion de errores: en caso de que la aplicacion se cuelgue tiene un autoguardado para no perderlo todo
- gestion de usuarios y permisos
- control de seguridad
#### tipos de sistemas operativos
- monotarea : solo una tarea
- multitarea : varias aplicaciones trabajando al mismo tiempo

- monousuario
- multiusuario

- monoproceso
- multiproceso

- centralizados
- distribuido : se puede hacer en diferentes maquinas

- propietarios
- libres
#### tipos de aplicaciones
- locales: se almacenan en el disco local
- en redes
- en web o en nube :como office
#### licencias
- gratuita(freeware) tiene codigo fuente pero no te permite modificarlo
- libre: libre modificacion 
- propietarios: modificacion o distribucion esta prohibida por el propietario
- comerciales: desarrolladas por una empresa
- retal : son las que compras fisicamente 
- licencia por volumen :destinado a empresas que usan varios equipos
#### gestores de arranques
es un pequeño programa que se ejecuta una vez iniciada la bios su funcion es preparar los elementos mas basicos que precisa el sistema operativo para funcionar
#### maquinas virtuales 
programa que simula un sistema operativo dentro de tu propio SO
#### actualizaciones 
- importante de hacer por temas de seguridad
- como funcionanan:
        - sobreescribir el programa
        - desinstalar e instalar la nueva version
- ejemplo: windows update
#### registro de sistemas
todos los sistemas operativos lo tienen sirven para cambiar ciertos comportamientos del equipo como modificar usuarios