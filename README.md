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


Capítulo 18

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


4. VIDEO

5. CONCLUSIONES

6. BIBLIOGRAFÍA

Floyd, T. (2007). Principio de Circuitos Eléctricos. Pearson, Prentice Hall
