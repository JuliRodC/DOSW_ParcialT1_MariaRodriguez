# DOSW_ParcialT1_MariaRodriguez
Parcial Practico  DOSW 1 corte 2026-1

## Punto 2
En este punto debemos identificar los patrones de diseño que usaremos, estos son:
#### Patron Strategy:
Este patron es de comportamiento. Se usara debiado que permite definir una familia de algoritmos, colocandolos en clases
separadas. Realizando asi varias clases como la principal "Silabinfo" que contendra metodos individuales para no sobre 
saturar a una sola clase, asi dividinedo responsabilidades. Asi tambien podremos usar herencias para las diferentes
clases con comportamientos compartidos

### Patron Factory Method
Este patron es de creacionales. Se usara factory Method ya que proporciona una interfaz para crear objetos en una super 
clase, siendo asi al necesitar mas recuersos de los que ya extiste, no se deba reestructurar el codigo haciendo mas
condicionales innecesarias y que hacen mas codigo del necesario.

## Punto 3

### Requerimientos Funcionales

+ Silabinfo debe permitir hacer reservas para la gestion de diferentes recursos de la universidad, estas siendo
manejadas por los profesores, estudiantes y monitores, no solo por colaboradores del laboratorio. Asi mismo, debe 
validar primero todos los requrimientos de su recurso, como el usuario, numero de puestos, tiempo de reserva y si ya hay
alguna reserva en el tiempo
+ Inicialmente Silabinfo debe gestionar 5 recursos: laboratorios, salones de clases, oficinas, salas de estudio y 
equipos, cada una de estas debe tener condicionales o reglas especificas, los datos del recurso que se necesite
+ Silabinfo debe tener la informacion de Enlace para poder manejar los datos de: Materias y estudiantes,y el de
recuersos humanos para los profesores, ya que esta por si sola no guarda la informacion

### Requerimientos No Funcionales

+ Silabinfo debe mantener los colores alusivos al programa de
  Ingeniería de Sistemas
+ Silabinfo debe tener una tipografia legible