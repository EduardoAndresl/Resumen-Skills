# Resumen-Skills
Resumen Skills



Modelamiento de datos basado en. :  

    TABLAS FACT SON EVENTOS MEDIDOS ( VISITAS , QUEJAS,ASISTENCIA,CALIFICACIONES,VENTAS ,DEVOLUCIONES) SIEMPRE SON POCAS COLUMNAS

    TABLAS DIMENSIONES (SON UTILIZADAS PARA SEGMENTAR QUE, QUIEN ,COMO ,CUANDO DONDE SUCEDIO EL EVENTO)
    
    
    DAX = DATA ANALUSIS EXPRESSIONS 
    
    
    hoy analizaremos las ventas de una compania comenzando desde lo mas general hasta lo mas especifico, lo primero que haremos sera cargar la base de datos llamada 'contososales'

2 Hemos organizado las tablas intentando primero realizar un modelo estrella para este projecto pero  este projecto requiere otro tipo de modelamiento donde existan en la parte superior las dimensiones y en la parte inferios las tablas de FACT

<img width="1416" alt="image" src="https://user-images.githubusercontent.com/112581327/196887080-120310c4-af45-4294-b3f7-570d747ff429.png">


3 Dejaremos de actualizar ciertas tablas para optimizar el trabajo.

<img width="1416" alt="image" src="https://user-images.githubusercontent.com/112581327/196887346-4e43127b-59e0-4388-89c9-9852b9f6a4f3.png">



4 Crearemos una tabla calendario para todo el modelo 

5 Una vez creada la estructura del modelo de datos , es necesario buscar dimensiones para analizar.

6 En este caso analizaremos las ventas por categoria comparando las ventas del año anterior con el presente

![image](https://user-images.githubusercontent.com/112581327/196888883-8162ad14-519b-45d7-8ff6-c4ab797a4a6d.png)




En este graphico resumen se pueden obtener las ventas, costos y utilizad por ano , ademas de analizar cada uno de los item por continente , por categoria o subcateoria 

![image](https://user-images.githubusercontent.com/112581327/196500267-c23b8927-2a36-4bdc-80bb-b83af7d96853.png)


Ademas con la informacion obtenida en la base de datos es posible crear escenarios creando a traves de dax una funcion calculada que me permite generar una variacion % del precio unitario, Siempre y cuando los costos se mantengan igual, de esta manera podemos obtener diferentes escenarios puntos de equilibro  que sran utiles para crear escenarios y planes de contingencia

![image](https://user-images.githubusercontent.com/112581327/196502031-eada1b6c-4908-43d1-9c9b-662a7d348cf0.png)






