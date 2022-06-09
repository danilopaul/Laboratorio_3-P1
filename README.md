# Laboratorio-3-P1

                                                   Universodad de las Fuerzas Armadas - ESPE
                                                     Fundamentos de Circuitos Electróinicos
        Integrantes:
        - Cholca Paul
        - Sandal Andrés
        - Vasquez Lady
 
1.OBJETIVOS

1.1 Objetivo General

Definir las características y pasos empleados en el método de las tensiones (voltajes) en los nodos, para aplicarlos en la resolución y cálculos de los ejercicios planteados, por medio del uso adecuado de la ley de ohm y especialmente de la ley de kirchhoff de corrientes en el planteamiento de ecuaciones.

1.2 Objetivo  Especificos

-  Realizar una inspección analítica correcta en el circuito para poder aplicar el método de nodos de la forma adecuada.
-  Relacionar la ley de ohm con la ley de kirchhoff de corrientes adecuadamente, para el planteamiento de ecuaciones y la resolución de las mismas.
-  Obtener las ecuaciones necesarias para poder determinar los datos requeridos con los cuales se pueda comprobar que está bien armado el circuito.

2.MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/105684550/172757453-2fbc3181-0da9-4e44-83a8-e569f79edb79.png)

Link del mapa mental: https://gitmind.com/app/doc/15e11351016 

3.REQUISITOS PREVIOS

- Circuito armado en el simulador:

![image](https://user-images.githubusercontent.com/105684550/172763168-27a933b0-65ad-423a-b430-c2252338c780.png)

- Voltajes en los nodos A y B:

![image](https://user-images.githubusercontent.com/105684550/172763116-ebbe61d4-23c1-4e05-bc29-7d74897da5cf.png)

4.MATERIALES Y EQUIPOS REQUERIDOS

![image](https://user-images.githubusercontent.com/105684550/172757602-17712b39-4c07-4a12-89ef-0e0134fddfba.png)

5.RESOLUCIÓN

![image](https://user-images.githubusercontent.com/105684550/172763138-b37df56f-bef3-4bd0-a4c0-a15fe852d117.png)

- Nodo A: I1=I2+I3

(5-VA)/1800=(VA-VB)/2200+(VA-VC)/470

5/1800-VA/1800=VA/2200-VB/2200+VA/470-0/470

5/1800-VA/1800=VA/2200-VB/2200+VA/470

(-1)(-VA/1800-VA/2200-VA/470+VB/2200)=(-5/1800)(-1)

VA/1800+VA/2200+VA/470-VB/2200=5/1800

(73×VA)/23265+-VB/2200=5/1800       →     Ecuación N°1

- Nodo B: I4+I6=I5

(VA-VB)/2200+(10-VB)/1500=(VB-VC)/3900

VA/2200-VB/2200+10/1500-VB/1500=VB/3900-0/3900

VA/2200-VB/2200-VB/1500-VB/3900=-10/1500

VA/2200-(197×VB)/143000=-10/1500          →        Ecuación N°2

Resolvemos el sistema de ecuaciones 1 y 2:

VA=1.67V

VB=5.39V

6.VIDEO


7.CONCLUSIONES:

Los nodos principales que se encuentran en circuito son 3 de los cuales en nodo Vc es nuestro nodod de referencia, puesto que este nodo se encuentran mas de dos elementos conectados, ademas de ser el que se encuentra mas cerca del polo negativo.

Para medir el voltaje  de los nodos que fueron identificados, se los debe medir en paralelo y con ello obtener los valores del circuito buscados, ademas el nodo C se asume que es tierra, con ello se puede identificar donde se debe colocar el multimetro.

Los calculos realizados se lograron obtner mediante un analisis entre las leyes de Kirchhoff y la ey de Ohm y con ellas obtner las ecuaciones necesarias para obtner el valor del V1 y V2.

8.BIBLIOGRAFÍA

Floyd, TL (2007). Principios de Circuitos Eléctricos. CDMX: Persona Educación.
