# TAREA-1-CAPITULO-7-8
## 1. OBJETIVOS
- Encontrar la resistencia total de una
red que consiste de resistores conectados
en varias configuraciones
serie-paralelo.
-  Determinar la corriente a través de
cualquier rama o componente de un
circuito serie-paralelo.
-  Determinar la diferencia de potencial
entre dos puntos cualesquiera
en un circuito serie-paralelo.
-  Calcular la caída de voltaje en un
resistor conectado a un potenciómetro.
-  Analizar de qué manera el valor de
un resistor de carga conectado a un
potenciómetro afecta el voltaje de
salida.
-  Calcular los efectos de carga de un
voltímetro o un amperímetro cuando
se usan para medir el voltaje o la
corriente en algún circuito.
- Convertir una fuente de corriente en
una fuente de voltaje equivalente.
-  Analizar los circuitos que tienen dos
a más fuentes de corriente en
paralelo.
-  Plantear y resolver ecuaciones de
rama para una red.
- Plantear y resolver ecuaciones de
malla para una red.
-  Plantear y resolver ecuaciones de
nodo para una red.
- Convertir un delta resistivo en un
circuito Y equivalente o un Y en
su circuito delta equivalente y
resolver el circuito simplificado
resultante.
- Determinar el voltaje o la corriente
en cualquier elemento de una red de
puente.
-  Usar PSpice y Multisim para analizar circuitos
de múltiples lazos.

## 2. MARCO TEÓRICO (RESUMEN)
## 7. CIRCUITOS EN SERIE-PARALELO

### 7-1 LA ROJA EN SERIE-PARALELO
### 7-2 ANÁLISIS DE CIRCUITOS EN SERIE - PARALELO
### 7-3 APLICACIONES DE LOS CIRCUITOS EN SERIE-PARALELO

### 7-4 POTENCIÓMETROS

![image](https://user-images.githubusercontent.com/84431598/123877815-8a19ad80-d903-11eb-8b22-86aa24ace235.png)

### 7-5 EFECTOS DE CARGA DE LOS INSTRUMENTOS
### 7-6 ANÁLISIS DE CIRCUITOS POR COMPUTADORA

## 8. MÉTODO DE ANÁLISIS

### 8-1 FUENTES DE CORRIENTE CONSTANTE
### 8-2 CONVERSIONES DE FUENTES
### 8-3 FUENTES DE CORRIENTE EN PARALELO Y EN SERIE
### 8-4 ANÁLISIS DE CORRIENTE DE RAMAS
### 8-5  ANÁLISIS DE MALLAS(LAZOS)
### 8-6 ANÁLISIS DE NODOS
### 8-7 CONVERSIÓN DELTA-Y(PI-T)

![image](https://user-images.githubusercontent.com/84431598/123878184-3a87b180-d904-11eb-8f02-7c31a2f83410.png)

### 8-8 REDES PUENTE

![image](https://user-images.githubusercontent.com/84431598/123878296-6a36b980-d904-11eb-9456-804224b46b14.png)

### 8-9 ANÁLISIS DE CIRCUITOS POR COMPUTADORA

![image](https://user-images.githubusercontent.com/84431598/123882657-dcab9780-d90c-11eb-9e71-13a778217381.png)

##  3. EXPLICACIÓN Y RESOLUCIÓN DE LOS EJERCICIOS
## 7. CIRCUITOS EN SERIE-PARALELO
### 7-1  LA RED EN SERIE - PARALELO
### 7-2 ANÁLISIS DE CIRCUITOS EN SERIE - PARALELO
### 7-3 APLICACIONES DE LOS CIRCUITOS EN SERIE - PARALELO

23. Considere el circuito de la figura 7-65 y los valores indicados:
a. Determine I_D.
b. Calcule el valor requerido de R_S.
c. Encuentre V_DS.

![image](https://user-images.githubusercontent.com/84431598/124848027-a9e34e00-df61-11eb-8e11-6b0379d7c0df.png)

a)

![image](https://user-images.githubusercontent.com/84431598/124854455-f8e2b080-df6c-11eb-8588-80d7a70eb34c.png)

b)

![image](https://user-images.githubusercontent.com/84431598/124854513-0e57da80-df6d-11eb-8120-14d7412bdf8d.png)

c)

![image](https://user-images.githubusercontent.com/84431598/124854644-3f380f80-df6d-11eb-9465-ae4ceed2404c.png)

### 7-4 POTENCIÓMETROS 

27. Vea el circuito de la figura 7-69:
a. Determine el intervalo de voltajes que aparecerán en R_L a medida que el
potenciómetro varié entre sus valores mínimo y máximo.
b. Si R2 se ajusta para tener 2.5 kΩ. ¿Cuál será el voltaje V_L? Si se remueve el
resistor de carga. que voltaje aparecerá entre las terminales a y b?

![image](https://user-images.githubusercontent.com/84431598/124994914-39ddd200-e00c-11eb-9303-3ca0e6d5498a.png)

a)

![image](https://user-images.githubusercontent.com/84431598/125360722-e8965100-e331-11eb-9222-48b1ffa6f3f6.png)

b)

![image](https://user-images.githubusercontent.com/84431598/125360796-019f0200-e332-11eb-975f-b6776aacbe2f.png)

c)

![image](https://user-images.githubusercontent.com/84431598/125360906-2a26fc00-e332-11eb-9032-9571aada2e82.png)

29. Si el potenciómetro de la figura 7-70 se ajusta para que R_2 = 200 Ω, determine
los voltajes V_ab y V_bc.

![image](https://user-images.githubusercontent.com/84431598/124994998-4feb9280-e00c-11eb-8439-14317d54fd06.png)

![image](https://user-images.githubusercontent.com/84431598/125367049-06b57e80-e33d-11eb-8a63-a3d1b7febc44.png)

31.-Vea el circuito de la figura 7-71:

![image](https://user-images.githubusercontent.com/84458025/125376099-e7741c80-e34f-11eb-8e33-8130c1d7856b.png)



a. Determine el intervalo del voltaje de salida (del mínimo al máximo) que se espera cuando el potenciómetro se ajusta del mínimo al máximo.



b. Calcule R2 cuando Vsal=20 V.


33.-En el circuito de la figura 7-72 calcule el voltaje de salida Vsal cuando RL=0 ohms, 250 ohms y 500 ohms.
![image](https://user-images.githubusercontent.com/84458025/125376269-45086900-e350-11eb-9607-19a5993dff42.png)



### 7-5 EFECTOS DE CARGA DE LOS INSTRUMENTOS
35.-Un voltímetro con una sensibilidad de S=20 kohms/V se usa en la escala de 10 V (con una resistencia interna total de 200 k) para medir el voltaje en el
resistor de 750 komhs de la figura 7-74. El medidor indica un voltaje de 5.00 V.

![image](https://user-images.githubusercontent.com/84458025/125376482-b3e5c200-e350-11eb-816b-3917b6cd21ca.png)


a. Determine el valor de la fuente de voltaje E.
b. ¿Qué voltaje se presentará en el resistor de 750 kohms cuando el voltímetro se quite del circuito?
c. Calcule el efecto de carga del medidor cuando se utilice como se muestra.
d. Si se usa el mismo voltímetro para medir el voltaje en el resistor de 200kohms, ¿cuál será la lectura?

37.-Un amperímetro se usa para medir la corriente en el circuito que se muestra en la figura 7-76.

![image](https://user-images.githubusercontent.com/84458025/125473944-274b7c60-f84d-409d-a80a-e9800bf1b985.png)

a. Explique cómo conectar de manera correcta el amperímetro para medir la corriente I1.

La forma correcta es colocando nuestro multimetro en serie ya que para realizar esta medicion nuestro multimetro actua como un cable mas.


### 7-6 ANÁLISIS DE CIRCUITOS POR COMPUTADORA
39. Use Multisim para encontrar V2, V4, IT, I1 e I2 en el circuito de la figura 7-10.

![image](https://user-images.githubusercontent.com/84458025/125468262-5611242a-eb9d-4572-87a4-ed3ebe2efd43.png)

41.-Use Multisim para encontrar las lecturas del medidor en el circuito de la figura 7-75, si está en la escala de 50 V.

![image](https://user-images.githubusercontent.com/84458025/125466670-1dc92a10-3bd7-4af8-ae52-bfed80b33a85.png)

43. Use PSpice para encontrar V2, V4, IT, I1 e I2 en el circuito de la figura 7-10.

![image](https://user-images.githubusercontent.com/84458025/125469454-f753ef22-546b-48bc-b6cc-d27e6257af14.png)


## 8. MÉTODO DE ANÁLISIS
### 8-1 FUENTES DE CORRIENTE CONSTANTE
1.-Encuentre el voltaje VS para el circuito de la figura 8-64.

![image](https://user-images.githubusercontent.com/84458025/125379398-12fa0580-e356-11eb-9676-41bd59b5b3e6.png)

![image](https://user-images.githubusercontent.com/84458025/125397951-43509c80-e374-11eb-90fc-77ac26dbf18d.png)


3.-Vea el circuito de la figura 8-66:

![image](https://user-images.githubusercontent.com/84458025/125379499-3de45980-e356-11eb-8e5b-ad99f75d8c4f.png)

a. Encuentre la corriente I3.

![image](https://user-images.githubusercontent.com/84458025/125398551-15b82300-e375-11eb-9534-730070cec3f0.png)

b. Determine los voltajes VS y V1.

![image](https://user-images.githubusercontent.com/84458025/125399712-99beda80-e376-11eb-80e1-6ba03f5ca956.png)


5. Para el circuito de la figura 8-68 encuentre las corrientes I1 e I2.

![image](https://user-images.githubusercontent.com/84458025/125379603-6d936180-e356-11eb-9fe0-6e6f76d9fd9f.png)

![image](https://user-images.githubusercontent.com/84458025/125400325-603a9f00-e377-11eb-85a7-74c62e35a49a.png)


7. Verifique que la potencia suministrada por las fuentes es igual a la suma de las potencias disipadas por los resistores en el circuito de la figura 8-68.

![image](https://user-images.githubusercontent.com/84458025/125379656-8865d600-e356-11eb-9897-a5bbbfdb67ab.png)

![image](https://user-images.githubusercontent.com/84458025/125395732-2ebed500-e371-11eb-9f51-aecb18270607.png)



### 8-2 CONVERSIONES DE FUENTE
9. Convierta cada fuente de voltaje de la figura 8-70 en su fuente de corriente equivalente.

![image](https://user-images.githubusercontent.com/84458025/125379777-be0abf00-e356-11eb-94f0-43a603e5db29.png)

![image](https://user-images.githubusercontent.com/84458025/125396363-0c798700-e372-11eb-85b2-edfa3841dd72.png)


11. Vea el circuito de la figura 8-72:

![image](https://user-images.githubusercontent.com/84458025/125379889-f8745c00-e356-11eb-8492-082965ad18f7.png)

a. Encuentre la corriente a través del resistor de carga con la regla del divisor de corriente.

![image](https://user-images.githubusercontent.com/84458025/125394606-8c522200-e36f-11eb-8279-8c423f5aa1af.png)


b. Convierta la fuente de corriente en su fuente de voltaje equivalente y determine,otra vez, la corriente a través de la carga.

![image](https://user-images.githubusercontent.com/84458025/125394877-fb2f7b00-e36f-11eb-8c5c-04b35f501871.png)


13. Vea el circuito de la figura 8-74:

![image](https://user-images.githubusercontent.com/84458025/125380086-45f0c900-e357-11eb-8afd-770fce510385.png)


a. Convierta la fuente de corriente y el resistor de 330 ohms en su fuente de voltaje equivalente.

b. Encuentre la corriente I a través de RL.

c. Determine el voltaje Vab.

![image](https://user-images.githubusercontent.com/84458025/125396919-d8529600-e372-11eb-9899-026f170f8041.png)

![image](https://user-images.githubusercontent.com/84458025/125463988-ca3fa8af-2a8a-4855-9ce9-b510f52b1031.png)
![image](https://user-images.githubusercontent.com/84458025/125464041-05d73fc4-4515-4db7-8b45-57c3234504a5.png)


### 8-3 FUENTES DE CORRIENTE EN PARALELO Y EN SERIE
15. Encuentre el voltaje V2 y la corriente I1 para el circuito de la figura 8-76.

![image](https://user-images.githubusercontent.com/84458025/125380221-759fd100-e357-11eb-8eb8-048bcad995f7.png)

17. Para el circuito de la figura 8-78 convierta la fuente de corriente y el resistor de 2.4 kohms en una fuente de voltaje y calcule el voltaje Vab y la corriente I3

![image](https://user-images.githubusercontent.com/84458025/125401126-667d4b00-e378-11eb-961b-a297f1180c70.png)


### 8-4 ANÁLISIS DE CORRIENTE DE RAMA
### 8-5 ANÁLISIS DE CORRIENTE DE MALLAS (LAZOS)
### 8-6 ANÁLISIS DE NODOS
### 8-7 CONVERSÍON DELTA-Y (PI-T)
39. Convierta cada una de las redes 
 de la figura 8-92 en su configuración Y
equivalente.

![image](https://user-images.githubusercontent.com/84431598/124812347-17bf5380-df29-11eb-9b1b-2be030108c08.png)

![image](https://user-images.githubusercontent.com/84431598/124812520-53f2b400-df29-11eb-89fc-ea0877aaeac9.png)

Equivale a: 

![image](https://user-images.githubusercontent.com/84431598/124812685-8b616080-df29-11eb-8289-e56c3cad400a.png)

b)

![image](https://user-images.githubusercontent.com/84431598/124821077-e1d39c80-df33-11eb-953f-e0f4d616d088.png)

Equivale a:

![image](https://user-images.githubusercontent.com/84431598/124821252-19424900-df34-11eb-929c-79df87f06dc7.png)


41. Convierta cada una de las redes Y de la figura 8-94 en su configuración 

equivalente.

![image](https://user-images.githubusercontent.com/84431598/124821609-8a81fc00-df34-11eb-96d1-e0698995ea6d.png)

a)

![image](https://user-images.githubusercontent.com/84431598/124842916-4d2e6600-df56-11eb-81a1-b8cc25cae055.png)

![image](https://user-images.githubusercontent.com/84431598/124842996-8bc42080-df56-11eb-8fe4-b1026617c09d.png)

b)

![image](https://user-images.githubusercontent.com/84431598/124843025-a3030e00-df56-11eb-9d95-6e53c18542de.png)

Equivale a:

![image](https://user-images.githubusercontent.com/84431598/124843202-055c0e80-df57-11eb-9f74-d192aaf59c1c.png)


### 8-8 ROJOS PUENTE
47. Vea el circuito puente de la figura 8-100:
a. El puente esta balanceado? Explique.
b. Escriba las ecuaciones de malla.
c. Calcule la corriente a través de R_5.
d. Determine el voltaje en R_5.

![image](https://user-images.githubusercontent.com/84431598/124700201-ece5e880-deb1-11eb-9d1e-dd1c18e12b2a.png)

a) Para que el circuito este balanceado tiene que cumplir lo siguiente:

![image](https://user-images.githubusercontent.com/84431598/124702561-23bdfd80-deb6-11eb-9414-3216b5d65ee2.png)

Como no se cumple el circuito no está balanceado.

b)

![image](https://user-images.githubusercontent.com/84431598/124702618-42bc8f80-deb6-11eb-8a06-a3c7c1037266.png)

![image](https://user-images.githubusercontent.com/84431598/124702760-9a5afb00-deb6-11eb-91ae-eedef9335bcc.png)

Sistema de Ecuaciones:

![image](https://user-images.githubusercontent.com/84431598/124702825-bd85aa80-deb6-11eb-8a13-6d7534697bb5.png)

![image](https://user-images.githubusercontent.com/84431598/124703009-19503380-deb7-11eb-85a8-08bca99607af.png)


c)

![image](https://user-images.githubusercontent.com/84431598/124703071-371d9880-deb7-11eb-92f1-634c279ef8a2.png)


d)

![image](https://user-images.githubusercontent.com/84431598/124703132-56b4c100-deb7-11eb-8111-9155baf1c030.png)


49. En el circuito puente de la figura 8-102 encuentre la corriente a través de cada
resistor.

![image](https://user-images.githubusercontent.com/84431598/124701038-79dd7180-deb3-11eb-8b09-8ffe0bdfb540.png)

Comprobamos que el circuito este balanceado

![image](https://user-images.githubusercontent.com/84431598/124701339-012ae500-deb4-11eb-86d8-7b737ee83a9d.png)

Se observa que el puente del circuito anterior está balanceado, ya que
R1/R3  R2/R4, por lo que se puede eliminar R5 y reemplazarlo con un cortocircuito
(debido a que el voltaje en el corto es cero) o con un circuito abierto (debido
a que la corriente a través del circuito abierto es cero).

La resistencia total se encuentra como sigue:

![image](https://user-images.githubusercontent.com/84431598/124703916-cf684d00-deb8-11eb-9d14-5ed0a1528d95.png)

La corriente del circuito es:

![image](https://user-images.githubusercontent.com/84431598/124703987-eeff7580-deb8-11eb-81a4-fbc876172b45.png)

La corriente en cada rama se calcula entonces con la regla del divisor de corriente:

![image](https://user-images.githubusercontent.com/84431598/124704058-0cccda80-deb9-11eb-981b-fe1c861f52b9.png)

Tomando en cuenta que I_R1=I_R3 y I_R2=I_R4 entonces:

![image](https://user-images.githubusercontent.com/84431598/124704396-a1cfd380-deb9-11eb-81a0-c616f33c62ae.png)

### 8-9 ANÁLISIS DE CIRCUITOS POR COMPUTADORA

51. Utilice Multisim para encontrar las corrientes a través de todos los resistores
del circuito que se muestra en la figura 8-86.

53. Utilice PSpice para encontrar las corrientes a través de todos los resistores del
circuito de la figura 8-96.

## 4. CONCLUSIONES
- Un circuito en serie-paralelo es una combinación de trayectorias tanto en serie como en paralelo.
- Para determinar la resistencia total en un circuito en serie-paralelo, identifique las relaciones serie y para-
lelo, y luego aplique las fórmulas para resistencia en serie y resistencia en paralelo.
- Para determinar corrientes de rama, aplique la fórmula del divisor de corriente, la ley de la corriente de
Kirchhoff o ley de Ohm. Considere cada problema de circuito individualmente para encontrar el méto-
do más apropiado.
- El método de la corriente en ramas está basado en las leyes del voltaje y de la corriente de Kirchhoff.
- El método de la corriente en lazos está basado en la ley del voltaje de Kirchhoff.
- La corriente que circula en un lazo no es necesariamente la corriente real presente en una rama.
- El método del voltaje en nodos está basado en la ley de la corriente de Kirchhoff.
- Se puede utilizar un puente Wheatstone equilibrado para medir una resistencia desconocida.
- Un puente está equilibrado cuando el voltaje de salida es de cero. La condición equilibrada produce co-
rriente de cero a través de una carga conectada entre las terminales de salida del puente.
- Se puede utilizar un puente Wheatstone desequilibrado para medir cantidades físicas por medio de un
transductor.
## 5. VIDEO
## 6. BIBLIOGRAFÍA

Roobins, A y Miller, W. (2007). *Análisis de circuitos teoría y práctica (4ta ed),* México DF, México: Cengage Learning.

Floyd, T. (2007). *Principios de circuitos eléctricos (8va ed),* México DF, México: Pearson Educación.

Ingeniería Mecafenix.(2017). Potenciómetro ¿Que es y como funciona?. Recuperado de  https://www.ingmecafenix.com/electronica/potenciometro/

Pererira, R.(nd) .  *Conversiones Delta ( ∆ ) - Estrella ( Y ) Estrella ( Y ) - Delta ( ∆ ).* Escuela de Ingeniería Electrónica . Recuperado de  https://repositoriotec.tec.ac.cr/bitstream/handle/2238/10133/Conversiones%20Delta-Estrella%20y%20Estrella-Delta%20%28presentaci%C3%B3n%29.pdf?sequence=1&isAllowed=y.



