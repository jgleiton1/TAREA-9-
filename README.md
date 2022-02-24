# TAREA-9-

1. OBJETIVOS

  1.1. Objetivo General
  
  Resolver los ejercicios planteados empleando teoria y formulas fundamentales, mediante la reflexiòn, creatividad y el orden que el estudiante genere, para que sus respuestas sean las correctan y se las presente su soluciòn de manera clara. 
  
  1.2. Objetivos específicos
  
  Diseñar un mapa conceptual u organizador gràfico que contenga un resumen claro y eficaz sonbre los temas de circuitos RLC, resonancia y filtros pasivos. 
  
  Analizar los ejercicios planteados para relacionarlo coon cada uno de los temas vistos en el resumen. 
  
  Resover los problemas por medio de aplicaciòn de teoria y formulas fundamentales para los temas principales. 
  
2. MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/93958596/155450263-5a2a5a61-1016-4f4f-8f90-235d9692a795.png)
![image](https://user-images.githubusercontent.com/93958596/155450268-c36deecf-246b-4f57-9067-4c2cb346d40c.png)

3. EXPLICACIÓN Y RESOLUCIÓN DE LOS EJERCICIOS

Capítulo 17

1. Cierto circuito RLC en serie tiene los siguientes valores: R 10 Æ, C 0.047 mF, y L 5 mH. Determine la impedancia en forma polar. ¿Cuál es la reactancia neta? La frecuencia de la fuente es de 5 kHz.

        Xc=1/2π(5)(0.047) =677.26
        X_L=2π(5)(5)=157.08
        X_tot=|157.08- 677.26|=520.18
        Z= √(10^2+〖520.18〗^2 )∠〖 tan〗^(-1) (520.18/10)
        Z=520 ∠88.9°
        520 Ω capacitivo

2. Si en la figura 17-59 la frecuencia del voltaje de fuente se duplica a partir del valor que producen las reactancias indicadas, ¿cómo cambia la magnitud de la impedancia?

![image](https://user-images.githubusercontent.com/94153604/155454199-d8d200bf-6895-4f61-bb0d-b68620e43df5.png)

        X_tot=|80- 35|=45
        La impedancia se incrementa a 150 Ω

3. Para el circuito de la figura 17-59, determine Itot, VR, VL y VC en forma polar.

![image](https://user-images.githubusercontent.com/94153604/155454274-61ff59ae-cf37-4a03-83d8-e598669b114f.png)

        X_tot=|80- 35|=45
        Z=47Ω-j45Ω
        Z=65 ∠43.75°
        I=Vs/Z=(4 ∠ 0°)/(65 ∠ 43.75)=61.5 ∠-43.75° mAI=Vs/Z=(4 ∠ 0°)/(65 ∠ 43.75)=61.5 ∠-43.75° mA
        V_R=IR=(61.5 ∠-43.75°)(47 ∠0°)=2.89 ∠-43.75° V
        V_L=IX_L=(61.5 ∠-43.75°)(80 ∠90°)=4.92 ∠46.25° V
        V_C=IX_C=(61.5 ∠-43.75°)(35 ∠-90°)=2.15 ∠-134° V 

4. Analice el circuito de la figura 17-60 para determinar lo siguiente (f 25 kHz):

![image](https://user-images.githubusercontent.com/94153604/155454471-4a573583-8ac2-4bf3-aca3-37d58bc7b463.png)

        R_T=140.66 Ω
        L_T=1.5 mH            
        C_T=1.81 μF     
        Xc=1/2π(25)(1.81) =0.369
        X_L=2π(25)(1.5)=235.6
        X_tot=|235.6- 3.52|=304.04    
        Z=335 ∠-65.1°     
        I=Vs/Z=(12 ∠ 0°)/(335 ∠-65.1°)=35.8 ∠65.1° mA
        P_real=VsICosθ=12(35.8)Cos(65.1)=181 mW     
        P_r=〖Ic〗^2 Xc= 〖32.52〗^2 (0.369)=390 mVAR 
        Pa=√(〖P_real〗^2+〖P_r〗^2 )= √(181^2+390^2 )=430 mVA    

5. Para el circuito de la figura 17-61, ¿cuál es el voltaje a través de R en condición de resonancia?

![image](https://user-images.githubusercontent.com/94153604/155454649-93398206-bedd-4eb5-8e49-4e652b51802f.png)

        I=Vs/(R )=12/22=0.55 A 
        V_R=12

6. Cierto circuito resonante dispuesto en serie tiene una corriente mínima de 50 mA y un VL de 100 V. El voltaje aplicado es de 10 V. ¿Cuál es el valor de Z? ¿Cuáles los valores de XL y XC?

        R =Vs/I=200 Ω 
        Z=200 Ω   
        X_L=Xc=100/50=2 kΩ      

7. Para la figura 17-62, ¿cuál es el valor de la corriente en los puntos de potencia media?

![image](https://user-images.githubusercontent.com/94153604/155454890-5a72a54d-0ac0-4c28-910a-f48eeaa0cd38.png)

        I=Vs/(R )=500 mA 

8. Diseñe un circuito en el cual las siguientes frecuencias resonantes en serie se puedan seleccionar con un conmutador:Diseñe un circuito en el cual las siguientes frecuencias resonantes en serie se puedan seleccionar con un conmutador:

![image](https://user-images.githubusercontent.com/94153604/155454967-303649ff-6b65-46f5-b067-9a4ed82163bd.png)

![image](https://user-images.githubusercontent.com/94153604/155454981-396e0163-a6b1-4180-86f1-c54777be5b9d.png)

9. ¿Es capacitivo o inductivo el circuito de la figura 17-63? Explique su respuesta.

![image](https://user-images.githubusercontent.com/93958596/155450695-816f2585-ae56-45df-b601-a54f0268260c.png)

    XL = 2πfL = 2π*12000*0.015 = 1130.97 Ω
    XC = 1 / 2πfC = 1 / 2π*12000*0.000000022 = 602.86 Ω
    Como XL > XC, el circuito es capacitivo.

10. Para el circuito de la figura 17-63, determine todas las corrientes y los voltajes en forma polar.

![image](https://user-images.githubusercontent.com/93958596/155450744-ea6f5b34-b950-4662-8ea9-514992e4a35d.png)

    XL = 2πfL = 2π*12000*0.015 = 1130.97 Ω
    XC = 1 / 2πfC = 1 / 2π*12000*0.000000022 = 602.86 Ω 
    Vs = VR = VL = VC = 5∠0° V
    IR = Vs / R = 5∠0° V / 100∠0° Ω = 0.05∠0° A
    IL = Vs / XL = 5∠0° V / 1.13∠90° kΩ = 4.425∠-90° mA
    IC = Vs / XC = 5∠0° V / 0.6∠-90° kΩ = 8.33∠90° mA

11. Cambie la frecuencia a 100 kHz en la figura 17-63 y repita el problema 19.

        XL = 2πfL = 2π*100000*0.015 = 9424.78 Ω
        XC = 1 / 2πfC = 1 / 2π*100000*0.000000022 = 72.34 Ω 
        Vs = VR = VL = VC = 5∠0° V
        IR = Vs / R = 5∠0° V / 100∠0° Ω = 0.05∠0° A
        IL = Vs / XL = 5∠0° V / 9.42∠90° kΩ = 0.53∠-90° mA
        IC = Vs / XC = 5∠0° V / 72.34∠-90° Ω = 69.1∠90° mA

12. Determine Z en condición de resonancia y fr para el circuito tanque de la figura 17-64.

![image](https://user-images.githubusercontent.com/93958596/155450830-67f955cb-3d75-49ab-b629-3bfa410ca72e.png)

    Z en resonancia de un circuito paralelo es infinita.

La frecuencia resonante es:

![image](https://user-images.githubusercontent.com/93958596/155450872-2ae41623-fa4c-44b0-b98b-a54b1bfac876.png)

13. Determine Preal, Pr y Pa en el circuito de la figura 17-64 en condición de resonancia.

![image](https://user-images.githubusercontent.com/93958596/155450893-2d5b0028-2903-4f09-97d8-2b8edf68fca9.png)

    Preal = 538 mW
    Pr = 0 W
    Pa = 7.45 µW

14. Para cada circuito de la figura 17-65, determine el ángulo de fase entre el voltaje de fuente y la corriente total.

![image](https://user-images.githubusercontent.com/93958596/155450919-655afa42-38f8-461e-a1b6-73acb142d51c.png)

    a.	-1.97° (Vs retrasado con respecto a Itot)
    b.	23.0° (Vs adelantado con respecto a Itot)

15. Convierta el circuito de la figura 17-66 a una forma equivalente dispuesta en serie.

![image](https://user-images.githubusercontent.com/93958596/155450946-6847bc2b-984e-48fa-9318-6d5da83b289d.png)

    XL = 2πfL = 2π*2000*1.5 = 18849.55 Ω = 18.85 kΩ
    Q = XL / R1 = 18.85 / 33 = 0.571
    Req1 = R1 * (Q^2 +1) = 33 * (0.571^2 +1) = 43.76 kΩ
    Leq = L * ((Q^2 +1) / (Q^2)) = 1.5 * ((0.571^2 +1) / (0.0571^2)) = 1.38 H

31. En la figura 17-67, ¿cuál es el ángulo de fase entre I2 y el voltaje de fuente?

![image](https://user-images.githubusercontent.com/94011974/155536243-0c198e71-1cd3-4f0b-a31f-6ed4277ed424.png)

33. Determine la corriente a través de cada componente mostrado en la figura 17-68. Encuentre el voltaje entre las terminales de cada componente.

![image](https://user-images.githubusercontent.com/94011974/155536302-8ecdb909-e3eb-4a7b-8dde-f2858ae8927e.png)

35. Si el valor de C es de 0.22 mF, ¿cuál es la corriente a través de un resistor de 100 Æ conectado de a a b en la figura 17-69?

![image](https://user-images.githubusercontent.com/94011974/155536357-4de83d88-410f-438e-9212-fe24a3d1db38.png)

37. Determine las frecuencias resonantes y el voltaje de salida en cada frecuencia mostrada en la figura 17-70.

![image](https://user-images.githubusercontent.com/94011974/155536397-d210ea2a-a195-412e-b7a5-7c0ed1775497.png)

![image](https://user-images.githubusercontent.com/94011974/155536419-4f3c2ad7-b67d-4bf6-9e9e-ab986f0a3faa.png)

39. En condición de resonancia, XL 2 kÆ y RW 25 Æ en un circuito RLC en paralelo. La frecuencia resonante es de 5 kHz. Determine el ancho de banda. 

![image](https://user-images.githubusercontent.com/94011974/155536457-e49a6acf-5456-4c31-bd7a-e3a8f7ba360e.png)

41. En cierto circuito RLC, la potencia en condición de resonancia es de 2.75 W. ¿Cuál es la potencia a la frecuencia crítica baja?

![image](https://user-images.githubusercontent.com/94011974/155536494-fbbf4d0a-f5b0-4490-a70b-0f86118fccf5.png)

43. Cierto circuito resonante en paralelo tiene un factor Q de 50 y un AB de 400 Hz. Si Q se duplica, ¿cuál es el ancho de banda a la misma fr?

![image](https://user-images.githubusercontent.com/94011974/155536536-87f6202f-1231-472d-a7f8-ab33566d7654.png)

Capítulo 18

1. En cierto filtro pasabajas, XC 500 Æ y R 2.2 kÆ. ¿Cuál es el voltaje de salida (Vsal) cuando la entrada es de 10 V rms? 

![image](https://user-images.githubusercontent.com/94011974/155536598-df40b118-4874-4954-8d50-8513bddbbf40.png)

3. Determine el voltaje de salida (Vsal) de cada filtro mostrado en la figura 18-38 a la frecuencia especificada cuando Vent 10 V.

![image](https://user-images.githubusercontent.com/94011974/155536629-485ac628-0304-41ab-9168-9e6e31acbc1d.png)

![image](https://user-images.githubusercontent.com/94011974/155536646-f3f5fdaf-3ed8-4ba8-bd4c-2d23a8c75603.png)

5. Para el filtro de la figura 18-39, calcule el valor de C requerido para cada una de las siguientes frecuencias críticas: 

![image](https://user-images.githubusercontent.com/94011974/155536714-df57ab13-c71c-4733-857c-fd58765ab7d2.png)

![image](https://user-images.githubusercontent.com/94011974/155536739-079962e2-90b9-4b3a-83b8-2a8b20a0db26.png)

7. Trace una curva de Bode para cada una de las partes del problema 5

![image](https://user-images.githubusercontent.com/94011974/155536784-85578b9a-88a1-46be-a946-d8dda24d20ba.png)

9. El voltaje de entrada a un filtro RC pasabajas es de 8 V rms. Determine el voltaje de salida a los siguientes niveles de dB:

![image](https://user-images.githubusercontent.com/94011974/155536844-fe76485b-b059-40e2-b0a8-f5d74bdbaa18.png)

6. En un filtro pasaaltas, XC = 500 Ω y R = 2.2 kΩ. ¿Cuál es el voltaje de salida (Vsal) cuando Vent = 10 Vrms?

![image](https://user-images.githubusercontent.com/93958596/155451015-7b0b478a-6301-459d-827e-73ede6999b17.png)

7. Determine el voltaje de salida de cada filtro mostrado en la figura 18-41 a la frecuencia especificada cuando Vent = 10 V.

![image](https://user-images.githubusercontent.com/93958596/155451033-72567b36-59d8-4ca0-acdf-24207b75124a.png)

a. XC = 1 / 2πfC = 1 / 2π * 60 Hz *0.00001 F = 265.26 Ω

![image](https://user-images.githubusercontent.com/93958596/155451081-87dc9b92-e84f-4e3c-86b4-1450b7bcc805.png)

b. XC = 1 / 2πfC = 1 / 2π * 400 Hz *0.0000047 F = 84.66 Ω

![image](https://user-images.githubusercontent.com/93958596/155451094-33907baf-29f2-4d59-a541-3c11f9a85736.png)

c. XL = 2πfC = 2π * 1000 Hz *0.005 H = 31.42 Ω
 
![image](https://user-images.githubusercontent.com/93958596/155451108-a7bd3c31-03ad-4814-bb4c-24dcf01d5dff.png)

d. XL = 2πfC = 2π * 2000 Hz *0.00008 H = 1 Ω

![image](https://user-images.githubusercontent.com/93958596/155451131-2f153110-e1a7-4990-a5b5-4e8f50b0afd4.png)

8. Trace la curva de Bode para cada filtro mostrado en la figura 18-41.

![image](https://user-images.githubusercontent.com/93958596/155451151-3340a064-6788-419c-b657-15339c5245bb.png)

9. Determine la frecuencia central para cada filtro de la figura 18-43.

![image](https://user-images.githubusercontent.com/93958596/155451172-07b20bd1-fad8-4867-a38a-fc8d933076e2.png)

a. Fc = fo

![image](https://user-images.githubusercontent.com/93958596/155451192-a20ee3af-3edf-4fcc-827b-3d7593e20083.png)

b. Fc = fo

![image](https://user-images.githubusercontent.com/93958596/155451220-7234b6c0-e087-4ef7-86f0-447875b649cf.png)

10. ¿Cuáles son las frecuencias críticas alta y baja para cada filtro de la figura 18-43? Suponga que la respuesta es simétrica con respecto a f0.

![image](https://user-images.githubusercontent.com/93958596/155451242-bcec12a7-9873-4907-945c-1ab5e62427f8.png)

    a. Frecuencia alta: 15.06 kHz
       Frecuencia baja: 13.94 kHz

    b. Frecuencia alta: 25.3 kHz
       Frecuencia baja: 22.7 kHz

11. Si la resistencia de devanado de las bobinas que aparecen en la figura 18-44 es de 4 Ω, ¿cuál es el voltaje de salida en condición de resonancia cuando Vent 120 V?

![image](https://user-images.githubusercontent.com/94153604/155455066-e95dfd9f-eb7d-4718-8db4-8fdad22d1876.png)

        V_sal=(R/(R+Rw)) V_ent= (680/(680+4))120=117 V

![image](https://user-images.githubusercontent.com/94153604/155455107-357188b9-4a6f-4520-991c-82e3b45e4985.png)

        V_sal=(R/(R+Rw)) V_ent= (1000/(1000+4))120=115 V

12. Diseñe un filtro pasabanda utilizando un circuito resonante paralelo que satisfaga las siguientes especificaciones: AB  500 Hz; Q 40; e Ic(máx) 20 mA, Vc(máx) 2.5 V.

        f=500(40)=20 kHz  
        Xc=2.5/20=0.125     
        C =1/2π(20)(0.125) =0.064 μF
        L=989 μH    

![image](https://user-images.githubusercontent.com/94153604/155455221-39030b28-0ce8-459e-8a1a-44fbdfa65e17.png)

13. Para cada filtro de la figura 18-47, determine la frecuencia central de la banda de rechazo.

![image](https://user-images.githubusercontent.com/94153604/155455277-e0d61124-bceb-4799-9dc1-819c6b0bb942.png)

        f=1/(2π√LC)=1/(2π√(0.5(6.8) ))=86.3 Hz

![image](https://user-images.githubusercontent.com/94153604/155455305-3c7affc2-07d0-455b-9efe-a3b44ce15561.png)

        f=1/(2π√LC)=1/(2π√(10(47) ))=7.34 MHz

14. Determine los valores de L1 y L2 en la figura 18-48 para dejar pasar una señal con frecuencia de 1200 kHz y rechazar una señal con frecuencia de 456 kHz.

![image](https://user-images.githubusercontent.com/94153604/155455371-f1416529-3640-4f10-85cc-b6ec15c182e0.png)

        f=1/(2π√LC)   
        L1=1/C(f×2π) =1/(0.22(1200×2〖π)〗^2 )=0.08 μH
        L2=1/C(f×2π) =1/(0.22(456×2〖π)〗^2 )=0.554 μH  

4. VIDEO

https://www.youtube.com/watch?v=bT0s80PITGk

5. CONCLUSIONES

Los circuito RCL de la misma manera se trata de hablar de los que estan en serie, paralelo  y los que se encuentran en serie-paralelo, ademàs se puede dar a concer temas especiales como su aplicación y el ancho de banda de circuitos resonantes .Del mismo modo en el caso de filtros pasivos se puede dividir en varios subtemas como lo son filtros pasabajas, filtros pasaaltas, filtros pasabanda y filtros rechazabanda, todos estos temas son sumamente importantes. 

Cada ejercicio que se encuentra presentado en el informe se relaciona a caa uno de los temas que se ha presentado en el resumen por ello es sumamanete importante leer toda la teoria, puesto que todo tiene relación y así se podra tener clao los temas a tratar y cuando se necesite aplicar y relacionar formulas y teoría, puesto que hay puntos que no solo se debe a formulas sino también a la teoria. 

Las formulas que se aplica son para obtener Xc y XL y estas se las encuentra en los anteriores capítulos, sin embargo en esta ocación una de las formulas m´s importantes es de la frecuencua crítica,  frecuencia resonante, entre otras. Siempre se debe tener en cuenta que se va a trabajar tanto en forma rectanfgular y polar y esos temas se presentaron en el anterior trabajo, sin embargo se debe tener en cuenta que cada clase tiene secuencua y se van a aplicar formulas que ya se han observado. 

6. BIBLIOGRAFÍA

Floyd, T. (2007). Principio de Circuitos Eléctricos. Pearson, Prentice Hall
