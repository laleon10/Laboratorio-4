# Laboratorio-4
 el Teorema de Superposición.

# OBJETIVO GENERAL

El teorema de superposición se demuestra teórica y prácticamente utilizando un simulador numérico para comparar los dos resultados y determinar la validez del método utilizado.

# OBJETIVOS ESPECÍFICOS

-Definir el teorema de Superposición.

-Entender sus pasos y la aplicación de estos.

-Realizar el circuito propuesto de manera correcta y funcional.

# MARCO TEÓRICO
![image](https://user-images.githubusercontent.com/116819463/209230598-d62b47c4-43e3-4e9f-b81a-fa1741d52746.png)
![image](https://user-images.githubusercontent.com/116819463/209230619-3a29c58b-042b-4a25-8d4b-a98d0bf00efe.png)

# PROCEDIMIENTO

Para empezar a realizar el circuito nesesitamos

2 Fuente de Voltaje de C.D.

2 Multímetros Digitales

1 Resistor de 1 kΩ

1 Resistor de 2.2 kΩ

1 Resistor de 820 Ω

1 Resistor de 470 Ω

1 Protoboard

-Establecemos el valor del voltaje que las fuentes nos va a brindar, en este caso 10V y 3V

-Siguiendo el diagrama, empezaremos a armar el circuito

![image](https://user-images.githubusercontent.com/116819463/209029232-70389e78-1f9b-4cad-b2e6-ab6df936b5d5.png)

tinkercad:

![Stunning Duup-Vihelmo](https://user-images.githubusercontent.com/116819463/209029403-e5134da2-0eda-4be1-8152-330cab89d920.png)

1.Primero mediremos el voltaje Total de Va que pasa por la segunda resistencia.

![Stunning Duup-Vihelmo (1)](https://user-images.githubusercontent.com/116819463/209030629-9cd52cb3-6ada-463e-bad2-baec43853a4e.png)

El voltaje total medido es de 2.11mV

2.Ahora mediremos el Va cuando V1 = 0.

![Stunning Duup-Vihelmo (2)](https://user-images.githubusercontent.com/116819463/209031102-feb17dc3-4168-4047-bfcb-d754df5a3b6f.png)


El voltaje de Va es -1.63 cuando V1 = 0

3. Ahora mediremos el Va cuando V2 = 0

![Stunning Duup-Vihelmo (3)](https://user-images.githubusercontent.com/116819463/209031063-2d36b1cb-aeca-48e5-93ab-fae373949f25.png)

El voltaje de Va es 3.74V cuando V2 = 0.

4. Para saber si las medidas hechas de Va cuando V1 y V2 son 0, debemos sumar sus voltajes y esta tendria que ser igual al voltaje total medido.

VA = -1.63 en cuando V1 = 0

VA = 3.74 en cuando V2 = 0

entonses -1.63+3.74=2.11

El teorema superposicion en el simuladar funciona

5. Ahora mediremos la Corriente total de Ix en Tinkercad.

![Stunning Duup-Vihelmo (1)](https://user-images.githubusercontent.com/116819463/209030654-aa8fc704-4640-4738-8707-171c2315c033.png)

La corriente total de Ix es: 6.38 mA.

6. Luego mediremos las corrientes de Ix cuando V1 = 0.

![Stunning Duup-Vihelmo (2)](https://user-images.githubusercontent.com/116819463/209031107-427c5745-e639-4a7f-8a63-080b851a076d.png)

La corriente Ix = 6.38 mA, cuando V1 = 0.

7. Luego mediremos las corrientes de Ix cuando V2 = 0

![Stunning Duup-Vihelmo (3)](https://user-images.githubusercontent.com/116819463/209031032-2a0f3a69-ae23-45b3-92b8-817ca569156d.png)

La corriente Ix =0 mA, cuando V2 = 0

8. Para saber si las medidas hechas de Ix cuando V1 y V2 son 0, debemos sumar sus corrientes y esta tendria que ser igual a la corriente total medida.

Ix = 6.38 en cuando V1 = 0

Ix = 0 en cuando V2 = 0

entonses 6.38+0=6.38

El teorema superposicion en el simuladar funciona

# RESPUESTA A INTERROGANTES 

Verifique el cumplimiento del Teorema de Superposición y compare los resultados obtenidos.

Solución del circuito con el método de superposición en el voltaje de 10 V

R=R2+R4=820+470

R=1290 OHM

R=(R2*R4)/(R2+R4)=(2200*1290)/(2200+1290)

R=813.18 OHM

VR3=(V1*R3)/(R1+R3)=(10*813.18)/(820+470)

VR3=4.48V

VA1=(VR3*R2)/(R2+R4)=(4.48*820)/(820+470)

VA1=2.85V

Solución del circuito con el método de superposición en el voltaje de 3V

R=(R4*R3)/(R4+R3)=(1000*2200)/(1000+2200)

R=687.5

R=R2+R3=820+687

R=1507.5

Ix=3/470

Ix=0.006A=6.38mA

VA2=(-3*820)/(687.5+820)

VA2=-1.632

VT=VA1+VA2=2.85+(-1.63)

VT=1.22

![image](https://user-images.githubusercontent.com/116819463/209233393-3c2a66f8-1141-4302-95ee-140b32569501.png)

# CONCLUSIONES

1) El Teorema o principio de Superposición es muy util e importante en los análisis de circuitos ya que este método solamente se utiliza para circuitos lineales y para obtener voltajes e intensidades en un circuito.

2) Los pasos en el teorema de superposicion empieza anulando todas las fuentes menos una, despues se calcula la respuesta del circuito (tensión o corriente) a la única fuente que hemos dejado, 
se repite los pasos 1 y 2 con cada fuente y finalmente se suman las respuestas de cada fuente
