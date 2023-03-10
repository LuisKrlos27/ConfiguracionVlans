# Configuracion de vlans
Tutorial para la configuracion de vlans mediante el simulador cisco packet tracer student 

#### __INTRODUCCION:__ 
Como estudiante de Ingeniería en Sistemas de la Universidad de Nariño, puedo decir que la configuración de VLANs en el simulador Cisco Packet Tracer es esencial para la segmentación del tráfico y el diseño eficiente de redes. Para ello, es necesario crear y asignar VLANs en los switches, configurar la comunicación entre ellas mediante el uso de enrutadores o capas de enrutamiento interno, y crear subinterfaces virtuales. Este proceso permite una mayor flexibilidad en el diseño de redes y una segmentación efectiva del tráfico, lo que resulta en una red más eficiente y fácil de administrar.

## __LABORATORIO CONFIGURACION VLANS__

### PASO 1: 

Abrir el simulador packet tracer y en la parte inferior izquierda podemos seleccionar los dispositivos que querramos utilizar, para este caso empezaremos a ubicar los computadores eligiendolos de la opcion __end devicies__ donde escogemos el pc llamado __generic__ en la primera opcion. 

Seleccinamos la cantidad de PCs que vayamos a utilizar y los ubicaremos de la siguiente manera.

De preferencia nombrar cada PC con la ip que le vayamos asignar 

![paso1](image/paso1.png)

#### PASO 1.1

Para organizar nuestra area de trabajo y poder obervar mejor que PCs queremos en cada vlan se recomienda utilizar marcas para separar nuestras vlans como en la siguiente imagen.

![paso1.1](image/paso1.1png.png)

Ya seleccionada la forma le podemos dar color a cada seccion y nombrear cada recuadro con el nombre de nuestra vlan, asi: 

![paso1.2](image/paso1.2.png)

## PASO 2: 

Una vez organizado nombrando cada equipo y cada area de trabajo es hora de configurar cada PC que hemos puesto, para esto daremos click en el icono del PC y se nos abrira la configuracion y daremos clic en __destok__

![paso2](image/paso2.png)

Una vez dentro de la opcion __destok__ pulsaremos el mouse en la opcion __IP conguration__ y le pondremos la IP que le asignamos de nombre en la parte inicial junto con el __Default gateway__

![paso2.1](image/paso2.1.png)

__Obervacion:__ el __Default gateway__ en este caso 192.168.1.1 solo se utilizara la primera vlan llamada __vlan 50 sistemas__ en las siguientes dos imagenes se mostrara el __Default gateway__ de las vlans __vlan 60 contabilidad__ y la __vlan 70 atencion al usuario__

PC tomado de la segunda seccion de nuesta vlan llamada __vlan 60 contabilidad__

![paso2.2](image/paso2.2.png)

PC tomado de la segunda seccion de nuesta vlan llamada __vlan 70 atencion al usuario__

![paso2.3](image/paso2.3.png)