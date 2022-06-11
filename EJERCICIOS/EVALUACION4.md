## Práctica 8.
### Disparadores (Triggers)

Objetivo: Demostrar las operaciones que se realizan en una base de datos.

Ejercicio: Crea una base de datos llamada test que contenga una tabla llamada
alumnos con las siguientes columnas. (valor 18)

Evaluación:

Creación de la base de datos : 9 puntos.

Creación de los Disparadores(Triggers): 9 puntos.

Tabla alumnos:

● id (entero sin signo)

● nombre (cadena de caracteres)

● apellido1 (cadena de caracteres)

● apellido2 (cadena de caracteres)

● nota (número real)

Una vez creada la tabla escriba dos triggers con las siguientes características:

● Trigger 1: trigger_check_nota_before_insert

  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de inserción.
  
  o Se almacena la leyenda 'se ingreso un registro'
  
  ![image](https://user-images.githubusercontent.com/101481188/173206448-f131f921-c565-474f-b5d0-146aabec5287.png)


Mi código SQL: https://www.db-fiddle.com/f/tcWxQFMtGx9fLivrAPVng5/0

● Trigger2 : trigger_check_nota_before_update
  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de actualización.
  
  o Se ingresa la leyenda 'se modifico un regisstro'
  
  
  ![image](https://user-images.githubusercontent.com/101481188/173206602-edaf77ed-8991-4b39-b7ba-5c3b759ce98f.png)



Mi código SQL: https://www.db-fiddle.com/f/tcWxQFMtGx9fLivrAPVng5/1
  
Una vez creados los triggers escribe varias sentencias de inserción y actualización
sobre la tabla alumnos y verifica que los triggers se están ejecutando
correctamente.

