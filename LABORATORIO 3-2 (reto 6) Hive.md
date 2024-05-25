## LABORATORIO 3-2 (reto 6) Hive:

 - En la instancia master , accedemos al beeline, creamos una base de datos
 svgdb y creamos la tabla HDI.
 ![image](https://github.com/sebastianvelezg/laboratorios-st0263-svg/assets/68916783/98784dad-07cf-437a-8d1b-75bf28cdf89d)
 - cargamos la tabla con los datos del archivo de hdi-data.csv y realizamos una consulta para revisar que los datos si fueron montados
![image](https://github.com/sebastianvelezg/laboratorios-st0263-svg/assets/68916783/26638f4d-88e5-4d72-b1af-30a5260db4f7)
![image](https://github.com/sebastianvelezg/laboratorios-st0263-svg/assets/68916783/4bc2487b-393a-44fe-9857-072898505632)
![image](https://github.com/sebastianvelezg/laboratorios-st0263-svg/assets/68916783/cb28c23e-87b5-4a58-a682-d651e2c99a19)
 - Mostramos las tablas y pedimos descripcion de la tabla HDI
 ![image](https://github.com/sebastianvelezg/laboratorios-st0263-svg/assets/68916783/5f584bd5-061f-4ae1-a0e4-0a5002a34d47)
 - Realizamos una consulta que muestra los paises con un ingreso nacional bruto mayor a 2000
![image](https://github.com/sebastianvelezg/laboratorios-st0263-svg/assets/68916783/cdc82438-b3c1-4d2e-a6ba-725de09d1285)
- Creamos la tabla DOCS y se realizamos un conteo de palabras ordenado en orden decendente, despues realizamos otro llamado pero ya ordenado por frecuencia de mayor a menor.
-![image](https://github.com/sebastianvelezg/laboratorios-st0263-svg/assets/68916783/2fe77c50-f6d5-40f3-8807-2f8b3a9d5e8b)
![image](https://github.com/sebastianvelezg/laboratorios-st0263-svg/assets/68916783/758e8382-83d3-4fbb-8463-371ceff66834)
- Creamos la tabla word_count_results en Hive para almacenar los resultados del conteo de palabras. Se inserta el conteo de palabras desde la tabla docs a word_count_results
![image](https://github.com/sebastianvelezg/laboratorios-st0263-svg/assets/68916783/f5a0fea2-9d62-42ca-ab02-d66d97debc66)
![image](https://github.com/sebastianvelezg/laboratorios-st0263-svg/assets/68916783/23be5c76-d20e-4e5e-8fe0-fb92d4cb6cef)
- listamos las tablas en la base de datos, se describen las tablas docs y word_count_result, y mostramos un límite de 10 filas de cada tabla.
![image](https://github.com/sebastianvelezg/laboratorios-st0263-svg/assets/68916783/cb79e224-57c4-4380-ab1b-f3fcc8b83b37)
![image](https://github.com/sebastianvelezg/laboratorios-st0263-svg/assets/68916783/2c18bbd3-2525-4c35-96eb-9e9abb082fad)
