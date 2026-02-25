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
