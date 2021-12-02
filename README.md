PRÁCTICA N° 03 ANÁLISIS DE NODOS

1. OBJETIVOS DE LA PRÁCTICA 

1.1. OBJETIVO GENERAL

- Comprobar de forma experimental el análisis de nodos, mediante la simulación de un circuito mixto, para poder implementar los conocimientos adquiridos en clase.

1.2. OBJETIVOS ESPECÍFICOS

- Identificar los nodos existentes dentro del circuito mixto.
- Utilizar de forma correcta los conceptos obtenidos de la Ley de Ohm.
- Emplear la Ley de las corrientes de Kirchhoff para poder obtener el voltaje que pasa por cada uno de los nodos.

2. MARCO TEÓRICO

LEY DE CORRIENTES DE KIRCHHOFF

Esta ley establece que en cualquier nodo, la suma algebraica de las corrientes que entran debe ser igual a la suma de las corrientes que salen.

![image](https://user-images.githubusercontent.com/94008521/144301738-17fa208c-40f2-4f48-b12e-7c0d5e6c33b3.png)

LEY DE OHM

Esta ley establece la relación entre tensión, corriente y resistencia de cualquier circuito eléctrico. Con referencia a esa relación se tiene que:

- El voltaje y la corriente son directamente proporcionales, es decir que si una aumenta la otra también. Por otro lado, la corriente y la resistencia son inversamente proporcionales, en otras palabras, si una aumenta la otra baja y viceversa. 

FORMULAS LEY DE OHM

![image](https://user-images.githubusercontent.com/94008521/144302747-18c195e3-f57c-4741-aa1f-6ac7d360edba.png)

DEFINICIÓN: VOLTAJE EN UN NODO

El voltaje en un nodo se le puede definir como la diferencia de potencial entre dos nodos de un circuito, como por ejemplo:

![image](https://user-images.githubusercontent.com/94008521/144297026-33ae8f3b-30c6-47cc-8802-3672c9805dee.png)

Para poder calcular el voltaje en un nodo se debe de seleccionar un nodo de referencia, dado que el voltaje se mide con respecto a este. Por lo general se lo llama como nodo de tierra , el potencial de este nodo se define con 0V.

MÉTODO DEL VOLTAJE DE NODOS

Para poder calcular en voltaje existente en cada uno de los nodos presentes se debe de realizar un análisis siguiendo los pasos a continuación:

- Determinar el nodo de referencia (tierra).
- Asignar una variable a cada uno de los nodos.
- Comenzar el análisis por los nodos que tengan cerca las fuentes de voltaje.
- Aplicar la Ley de corrientes de Kirchhoff en cada nodo.
- Plantear el sistema de ecuaciones obtenido aplicando la Ley de Ohm.
- Resolver el sistema de ecuaciones encontrando el valor de voltaje que pasa por el nodo analizado.

3. EXPLICACIÓN DEL PROCEDIMIENTO

3.1. MATERIAL Y EQUIPO REQUERIDO

![image](https://user-images.githubusercontent.com/94008521/144334652-8696b2e6-7980-4213-8158-ce4ffe258a72.png)

3.2. IDENTIFICACIÓN DE LOS NODOS

![image](https://user-images.githubusercontent.com/94008521/144304043-bf3f8e49-3e95-488f-af7c-f668d5abb084.png)

3.3. ECUACIONES DE ANÁLISIS DE NODOS 

NODO A

- Es un nodo trivial (no genera ecuación)

NODO B

![image](https://user-images.githubusercontent.com/94008521/144324371-f131017d-7a96-4f66-99ae-2d352b9e612c.png)

NODO C

![image](https://user-images.githubusercontent.com/94008521/144324383-ec405b7c-a247-4612-b3cc-02632a152526.png)

NODO D

- Es un nodo trivial (no genera ecuación)

NODO DE REFERENCIA

Es un nodo conocido como tierra por tanto nos da 0V.

3.4. PLANTEAMOS EL SISTEMA DE ECUACIONES

![image](https://user-images.githubusercontent.com/94008521/144324451-f9b5e703-a280-40b8-88a6-e9457bdc29cb.png)

3.5. RESOLUCIÓN DEL SISTEMA DE ECUACIONES

![image](https://user-images.githubusercontent.com/94008521/144325113-ac434da6-ab4a-4bb0-905a-19545a81004e.png)

![image](https://user-images.githubusercontent.com/94008521/144325120-b4d0e90e-800a-434e-9a58-ecfc2efeec8e.png)

3.6. POR TANTO EL VOLTAJE EN LOS NODOS B y C.

![image](https://user-images.githubusercontent.com/94008521/144326498-0ed615ed-4114-4c1d-8de8-8744b2de1909.png)

3.7. TABLA DE DATOS 

![image](https://user-images.githubusercontent.com/94008521/144329712-13a50ce0-1641-4ffb-bd90-9be65c5b30dd.png)

3.8. SIMULACIÓN MULTISIM

![image](https://user-images.githubusercontent.com/94008521/144330333-a15630a0-0dad-4101-94af-6dad5ae922b6.png)

3.9. EXPERIMENTAL TINKERCAD

![image](https://user-images.githubusercontent.com/94008521/144330403-2678dd13-2dbe-4358-bf7e-d9f71eb8ae07.png)

4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

5. VIDEO

6. CONCLUSIONES

7. BIBLIOGRAFÍA

-	Bravo, E. (26 de Febrero de 2017). Obtenido de http://www.inacap.cl/web/material-apoyo-cedem/alumno/Electricidad/Redes-Electricas/AAI_ELSP01_GE9-METODODE-ANALISIS-Y-RESOLUCION-DE-CIRCUITOS-EN-CC.pdf 
-	García, A. (21 de Marzo de 2021). Panama Hitek. Obtenido de http://panamahitek.com/ley-de-las-corrientes-de-kirchhoff-metodo-de-nodos/
-	Hernandez, M. (18 de Septiembre de 2019). Obtenido de https://innovacionumh.es/Proyectos/P_19/Tema_1/UMH_07.htm
-	Marín, A. (11 de Marzo de 2021). Obtenido de https://economipedia.com/definiciones/ley-de-ohm.html
-	Salazar, A. (15 de Julio de 2019). Obtenido de http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/02_Leyes_de_Voltajes_y_Corrientes_de_Kirchhoffs.pdf

