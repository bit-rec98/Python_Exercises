# Python_Exercises
Repositorio dedicado a ejercicios de práctica

## Ejercicios: 

1. Diseña un algoritmo que introduzca por teclado el nombre de 3 países, se almacenen en una lista y los muestre por pantalla.
2. Diseña un algoritmo que almacene los precios de 4 productos que compré en una lista y luego me muestre el total en pantalla.
3. Diseña un algoritmo que almacene las letra de tu nombre en una lista y luego muestre el nombre.
4. Diseña un algoritmo que introduzca por teclado el nombre, materia, profesor y nota. Se almacene en una tupla y luego muestre los datos en pantalla.
5. Diseña un algoritmo que introduzca por teclado el nombre de 3 materias y sus notas correspondientes. Deben almacenarse las materias en una tupla y las notas en otra. Luego muestre en pantalla la materia con su nota correspondiente.
6. Diseña un algoritmo con un diccionario que contenga como clave 3 materias que estás cursando y como valores uses tuplas para almacenar 2 notas por materia. Luego por pantalla muestres las notas de cada materia.
7. Diseña un algoritmo creando una tupla que almacene 3 categorías de música y luego crea un diccionario donde utilices como clave la tupla y almacenes 2 músicos por categoría de música. Luego mostrar en pantalla los artistas.

---------------------------------------------------------------------
## Ejercicio ATM: 
### 1) Escribir un programa que permita validar el ingreso a un sistema. Se deberá solicitar el ingreso por teclado de nombre de usuario y contraseña. Será valido como nombre de usuario “admin” y como contraseña “1234”. Si el ingreso es correcto deberá mostrar por pantalla el mensaje “Ingreso exitoso”.

Opcional 1: permitir como usuario valido también su propio nombre y su propia contraseña.
Opcional 2: solamente permitir el ingreso incorrecto de los datos 3 veces, luego de ello, no permitir más ingresos y mostrar por pantalla “Cuenta bloqueada”.
Opcional 3: Puede incluir parte de la lógica del programa en una o más funciones.

### 2) Mostrar por pantalla el siguiente menú:
---------------------------------------------------------------------
## CAJERO AUTOMATICO
## ISPC

### Listado de opciones:                                            
  1) Ingreso de dinero                                               
  2) Extracción de dinero                                            
  3) Consulta de salto                                               
  4) Salir                                                           
                                                                     
  - Ingrese su selección: _                                          
                                                                     
---------------------------------------------------------------------

El programa deberá mostrar luego del ingreso de cada opción “Usted ha seleccionado la opción x”, por ejemplo, en el caso de ingresar un 1, deberá mostrar por pantalla “Usted ha seleccionado la opción 1” y así sucesivamente. Al seleccionar la opción 4 se debe terminar la ejecución del programa.

### 3) Deberá continuar con el ejercicio 2 y escribir la lógica del cajero automático de la siguiente manera.

1. Su saldo inicial será de $10000.
2. Al seleccionar la opción 1 se pedirá al usuario que ingrese un importe por teclado el cual se sumará a su saldo inicial.
3. De la misma manera al seleccionar la opción 2, se solicitará un importe por teclado el cual se restará al saldo inicial.
4. Con la opción 3 se consultará su saldo actual.
5. En todo momento se deberá contralar que no se pueda extraer dinero, si no se cuentan con fondos suficientes.

### 4) Deberá en un solo programa unir el logueo del sistema con los ejercicios 2 y 3. Esto quiere decir que, si el ingreso al sistema es exitoso, se mostrará el menú del cajero automático y el usuario podrá comenzar a operar.
