# Ejercicios entregables de plpgsql

Continuando con la batería anterior de ejercicios (https://github.com/maximofernandezriera/cursores), durante la sesión de hoy deberéis resolver los siguientes enunciados propuestos:

    1. Crear un cursor con parámetros que pasando el número de departamento visualice el número de empleados de ese departamento. 
    (este ya estaba en el repositorio de la clase pasada pero por temas organizativos, lo pasamos a este)
    
    2. Utilizando un bucle FOR declara una subconsulta que nos devuelva el nombre de los empleados cuyo nombre sea ST_CLERCK.  
    (Esto puede no  declararse en el cursor sino que lo podríamos declarar directamente en el FOR)
    
    3. Crea una aplicación que tenga un cursor utilizando FOR UPDATE para la gestión de los empleados. Debes tener en cuanta que:
    
      o Por cada fila de empleados recuperada, si el salario es mayor de 8000 incrementamos el salario un 2%
      o Si es menor de 800 lo hacemos en un 3%
      o Debes hacer uso de la cláusula  WHERE CURRENT OF
      o Finalmente deberás comprobar que los salarios se han modificado correctamente.
