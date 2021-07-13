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

### 7-1 LA RED EN SERIE-PARALELO

![La red en serie-paralelo](https://user-images.githubusercontent.com/84425276/125489854-7ebae040-b2d8-41b4-8c0f-b249cbe67cdd.png)

### 7-2 ANÁLISIS DE CIRCUITOS EN SERIE - PARALELO

![Análisis de circuitos en serie-paralelo](https://user-images.githubusercontent.com/84425276/125489906-9261f68c-c2f1-46e9-b8fe-86f1ef0b9554.png)

### 7-3 APLICACIONES DE LOS CIRCUITOS EN SERIE-PARALELO

![image](https://user-images.githubusercontent.com/84431598/125483912-9f795ad8-89a1-4a89-92f2-3c66b8e515c3.png)

### 7-4 POTENCIÓMETROS

![image](https://user-images.githubusercontent.com/84431598/123877815-8a19ad80-d903-11eb-8b22-86aa24ace235.png)

### 7-5 EFECTOS DE CARGA DE LOS INSTRUMENTOS

![image](https://user-images.githubusercontent.com/84458025/125496084-6c3c5f66-c960-46a9-ab88-fdd27753dc13.png)

### 7-6 ANÁLISIS DE CIRCUITOS POR COMPUTADORA

![image](https://user-images.githubusercontent.com/84458025/125496029-50c01f5d-3211-441b-a37f-20b8219a322f.png)


## 8. MÉTODO DE ANÁLISIS

### 8-1 FUENTES DE CORRIENTE CONSTANTE

![Diapositiva1](https://user-images.githubusercontent.com/84458025/125495383-fc710c1f-4c7e-4139-a04e-20807615b303.JPG)

### 8-2 CONVERSIONES DE FUENTES

![Diapositiva2](https://user-images.githubusercontent.com/84458025/125495581-54e7cb34-6e76-4d14-8381-a21f8cf54dac.JPG)


### 8-3 FUENTES DE CORRIENTE EN PARALELO Y EN SERIE

![Diapositiva3](https://user-images.githubusercontent.com/84458025/125495612-da14e103-b4f0-49a8-9045-caf2452f2f9f.JPG)

### 8-4 ANÁLISIS DE CORRIENTE DE RAMAS

![Análisis de corriente de rama](https://user-images.githubusercontent.com/84425276/125489985-79a9fd75-01dc-446b-9324-7f6840058480.png)

### 8-5  ANÁLISIS DE MALLAS(LAZOS)

![Análisis de mallas (lazos)](https://user-images.githubusercontent.com/84425276/125490023-df172a01-efa6-459f-a3c5-f0e64ae812f0.png)

### 8-6 ANÁLISIS DE NODOS

![Análisis de nodos](https://user-images.githubusercontent.com/84425276/125490058-9beae920-f40a-4f2b-9b17-662ffba595a7.png)

### 8-7 CONVERSIÓN DELTA-Y(PI-T)

![image](https://user-images.githubusercontent.com/84431598/123878184-3a87b180-d904-11eb-8f02-7c31a2f83410.png)

### 8-8 REDES PUENTE

![image](https://user-images.githubusercontent.com/84431598/123878296-6a36b980-d904-11eb-9456-804224b46b14.png)

### 8-9 ANÁLISIS DE CIRCUITOS POR COMPUTADORA

![image](https://user-images.githubusercontent.com/84431598/123882657-dcab9780-d90c-11eb-9e71-13a778217381.png)

##  3. EXPLICACIÓN Y RESOLUCIÓN DE LOS EJERCICIOS
## 7. CIRCUITOS EN SERIE-PARALELO
### 7-1  LA RED EN SERIE - PARALELO

1. Para las redes de la figura 7-46, determine cuales resistores y ramas están en serie y cuales en paralelo. Escriba una expresión para la resistencia total, RT.

![image](https://user-images.githubusercontent.com/84425276/125490271-e6b94e3e-3e9a-42f7-854d-4c9c8a42e9c9.png)

![image](https://user-images.githubusercontent.com/84425276/125490369-c2a22ec8-71e0-4695-b6d6-b1a4ac00cb7c.png)

![image](https://user-images.githubusercontent.com/84425276/125490510-e1a0ab00-aa38-41ab-8524-f7287ca0a56d.png)

3. Escriba una expresión para RT1 y RT2 para las redes de la figura 7-48.

![image](https://user-images.githubusercontent.com/84425276/125490535-18be7b0a-6680-4093-8fbd-dc555e3b27f7.png)

![image](https://user-images.githubusercontent.com/84425276/125490592-0326cf99-51f4-4db4-857d-c9fd674e556c.png)

![image](https://user-images.githubusercontent.com/84425276/125490634-08d221a9-ffdd-4522-a802-1000bd15849b.png)

5. Las redes de resistores tienen las resistencias totales que se muestran a continuación.
Dibuje un circuito que corresponda a cada expresión.
a. RT = (R1||R2||R3) + (R4||R5)

![image](https://user-images.githubusercontent.com/84425276/125490679-b862ae5d-1970-4c27-9e3e-a0a1e38a4c43.png)

b. RT = R1 + (R2||R3) + [R4||(R5 + R6)]

![image](https://user-images.githubusercontent.com/84425276/125490735-901de44f-b31a-454b-be9c-38e8deca3e7b.png)

### 7-2 ANÁLISIS DE CIRCUITOS EN SERIE - PARALELO

7. Determine la resistencia total para cada red de la figura 7-50.

![image](https://user-images.githubusercontent.com/84425276/125490978-a1c25a7e-edcf-4f27-85f3-f012f7ef2f6f.png)

(a)

![image](https://user-images.githubusercontent.com/84425276/125491146-e486e2a1-45c2-4a64-80ee-16818c88875d.png)

![image](https://user-images.githubusercontent.com/84425276/125491168-037efefc-0686-4fc6-ac12-159b86bbf8d0.png)

![image](https://user-images.githubusercontent.com/84425276/125491197-5d45b3f8-8593-49a8-9acb-0495d84bec94.png)

![image](https://user-images.githubusercontent.com/84425276/125491223-0d1caff3-9d9e-4b38-bef6-f25a4f0b3d81.png)

![image](https://user-images.githubusercontent.com/84425276/125491292-9ec259ed-7e8e-43e8-9a55-154ad0b15384.png)

![image](https://user-images.githubusercontent.com/84425276/125491308-ebc97bef-ca49-40ab-b1bb-6e40f7fd4ae1.png)

![image](https://user-images.githubusercontent.com/84425276/125491340-88d12d39-d08e-433e-994e-c5e44710ee81.png)

(b)

![image](https://user-images.githubusercontent.com/84425276/125491380-5d01507b-1931-4a8a-a7dd-e177874293ec.png)

![image](https://user-images.githubusercontent.com/84425276/125491414-285ee834-b8a7-45dc-bfe7-94ac76cf8a05.png)

![image](https://user-images.githubusercontent.com/84425276/125491433-c6ef18fb-d936-470b-9ee3-323e4d0c4176.png)

![image](https://user-images.githubusercontent.com/84425276/125491455-f7806338-fde4-443f-bc29-5c7c01185a36.png)

![image](https://user-images.githubusercontent.com/84425276/125491469-ba1a5dea-1fa1-47d6-b44d-6bfd84f498c8.png)

![image](https://user-images.githubusercontent.com/84425276/125491490-c23cb68c-f1f3-4ce8-bfc6-466bddb1bcb9.png)

![image](https://user-images.githubusercontent.com/84425276/125491552-ad1a2c41-10cf-4ba7-b937-a5ba8ae0bedd.png)

![image](https://user-images.githubusercontent.com/84425276/125491553-6145b702-f85b-4e07-9471-b9e437d65cf1.png)

9. Calcule la resistencia Rab y Rcd en el circuito de la figura 7-52. 

![image](https://user-images.githubusercontent.com/84425276/125491598-7d5d5012-4373-4190-aeca-7defa9b007fa.png)

Para Rab ->

![image](https://user-images.githubusercontent.com/84425276/125491650-02b8b6ff-b0e5-4dca-b739-6d50874e6eec.png)

![image](https://user-images.githubusercontent.com/84425276/125491702-010dddd9-089f-4977-85c9-9ed3959bdb8d.png)

![image](https://user-images.githubusercontent.com/84425276/125491721-b7290330-c526-4edb-9619-d17035121d5b.png)

![image](https://user-images.githubusercontent.com/84425276/125491739-c36dccd4-1cfd-424a-927c-7d4aa7515251.png)

![image](https://user-images.githubusercontent.com/84425276/125491757-c5285ffc-4bcf-4885-b6b0-6a26bfc34005.png)

![image](https://user-images.githubusercontent.com/84425276/125491816-0ec1ccea-44ef-43b6-b4f1-e983600b0450.png)

Para Rcd ->

![image](https://user-images.githubusercontent.com/84425276/125491887-786ac648-80d3-4e19-bbde-14e125d100e9.png)

![image](https://user-images.githubusercontent.com/84425276/125491929-cab8ec80-7cd7-4eba-ab5d-a7bc9036eecf.png)

![image](https://user-images.githubusercontent.com/84425276/125492019-d0587e96-3144-4cb6-a891-c3bede0856cf.png)

11. Vea el circuito de la figura 7-54.

Encuentre las siguientes cantidades:

a. RT

b. IT, I1, I2, I3, I4

c. Vab, Vbc.

![image](https://user-images.githubusercontent.com/84425276/125492056-abfd01c0-596c-4ac6-b5d1-8d7c2c83ff87.png)

![image](https://user-images.githubusercontent.com/84425276/125492087-1961a4bf-0b9f-4c34-8c0c-3da4d3b3cf14.png)

![image](https://user-images.githubusercontent.com/84425276/125492170-f3b53891-ea9d-4235-bc1a-fe5500a229e1.png)

c)

![image](https://user-images.githubusercontent.com/84425276/125492229-4c850b0a-c00a-49e3-975a-6d5454f9ff40.png)

13. Vea el circuito de la figura 7-56.

a. Encuentre las corrientes I1, I2, I3, I4, I5 e I6.

b. Encuentre los voltajes Vab y Vcd.

c. Verifique que la potencia suministrada al circuito es igual a la suma de las potencias disipadas por los resistores.

![image](https://user-images.githubusercontent.com/84425276/125492271-c29611a5-e3e9-4ec3-b45f-1d3a21edfe20.png)

![image](https://user-images.githubusercontent.com/84425276/125492310-413526ea-967d-4fa6-8acf-f86847f654a7.png)

![image](https://user-images.githubusercontent.com/84425276/125492388-eef57852-46ec-491d-98d6-429930f83252.png)

15. Vea los circuitos de la figura 7-58:

a. Encuentre las corrientes indicadas.

b. Encuentre el voltaje Vab.

c. Verifique que la potencia suministrada al circuito es igual a la suma de las potencias disipadas por los resistores.

![image](https://user-images.githubusercontent.com/84425276/125492626-8d8c4113-ba55-4bf1-89a2-4df2f626e10c.png)

![image](https://user-images.githubusercontent.com/84425276/125492675-01f783d2-5949-4627-9c6e-e171017254ce.png)

![image](https://user-images.githubusercontent.com/84425276/125492699-5e8403b5-1642-4c72-972b-b9a377a89c8b.png)

![image](https://user-images.githubusercontent.com/84425276/125492747-9a70ad21-5e64-4b7f-8f38-8659861a2f9a.png)

![image](https://user-images.githubusercontent.com/84425276/125492786-c3174d71-cc4b-49d8-8bfa-ee48d4fdc56e.png)

![image](https://user-images.githubusercontent.com/84425276/125492809-f22b4cd0-95ce-4423-b0ed-d04ebbc0cd73.png)

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

![image](https://user-images.githubusercontent.com/84458025/125494270-a0fdb24d-bc4b-46c3-bfcb-92f375c07c50.png)

b. Calcule R2 cuando Vsal=20 V.

![image](https://user-images.githubusercontent.com/84458025/125494322-f3450170-4859-476f-8a17-b3488145c066.png)

33.-En el circuito de la figura 7-72 calcule el voltaje de salida Vsal cuando RL=0 ohms, 250 ohms y 500 ohms.
![image](https://user-images.githubusercontent.com/84458025/125376269-45086900-e350-11eb-9607-19a5993dff42.png)

![image](https://user-images.githubusercontent.com/84458025/125494402-a2e22f60-1b67-4f92-a3ee-ce42e3183a93.png)


### 7-5 EFECTOS DE CARGA DE LOS INSTRUMENTOS
35.-Un voltímetro con una sensibilidad de S=20 kohms/V se usa en la escala de 10 V (con una resistencia interna total de 200 k) para medir el voltaje en el
resistor de 750 komhs de la figura 7-74. El medidor indica un voltaje de 5.00 V.

![image](https://user-images.githubusercontent.com/84458025/125376482-b3e5c200-e350-11eb-816b-3917b6cd21ca.png)


a. Determine el valor de la fuente de voltaje E.

![image](https://user-images.githubusercontent.com/84458025/125481208-698fea29-e75b-432c-9fc7-1c4a0710a856.png)

b. ¿Qué voltaje se presentará en el resistor de 750 kohms cuando el voltímetro se quite del circuito?

![image](https://user-images.githubusercontent.com/84458025/125481852-51eb510b-7352-4521-aaa2-0b061ad7378f.png)

c. Calcule el efecto de carga del medidor cuando se utilice como se muestra.

![image](https://user-images.githubusercontent.com/84458025/125482161-091ddd13-fe35-419b-9859-9eeadf9fd4fa.png)

d. Si se usa el mismo voltímetro para medir el voltaje en el resistor de 200kohms, ¿cuál será la lectura?

![image](https://user-images.githubusercontent.com/84458025/125482714-bc60a750-2bf3-4874-b8e7-865af38eabdf.png)

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

19. Escriba las ecuaciones de corriente de rama para el circuito de la figura 8-79 y encuentre las corrientes de rama mediante determinantes.

![image](https://user-images.githubusercontent.com/84425276/125493017-ee9daf69-4b40-4776-bd8b-89c716166a00.png)

![image](https://user-images.githubusercontent.com/84425276/125493062-5485b469-18ad-4e46-8c68-05b409602e73.png)

21. Escriba las ecuaciones de corriente de rama para el circuito de la figura 8-81 y encuentre la corriente I2.

![image](https://user-images.githubusercontent.com/84425276/125493100-73ce3676-c1ea-4bcd-9b0e-27556717fd55.png)

![image](https://user-images.githubusercontent.com/84425276/125493150-5160099f-eb8b-416e-b8d9-07de138eae47.png)

23. Vea el circuito de la figura 8-83:

a. Escriba las ecuaciones de corriente de rama.

b. Encuentre la corriente I2.

c. Determine el voltaje Vab.

![image](https://user-images.githubusercontent.com/84425276/125493207-9657aa4d-f78a-4047-b60b-fa6e25d20082.png)

![image](https://user-images.githubusercontent.com/84425276/125493232-b635d6ad-11a9-4cea-ab35-1164ceb7fa9f.png)

### 8-5 ANÁLISIS DE CORRIENTE DE MALLAS (LAZOS)

25. Escriba las ecuaciones de malla para el circuito que se muestra en la figura
8-79 y encuentre las corrientes de lazo.

![image](https://user-images.githubusercontent.com/84425276/125493267-c66e371c-4edb-4719-817e-7c19ee678468.png)

![image](https://user-images.githubusercontent.com/84425276/125493310-46cf5399-d18b-48ff-a15a-4bf66df54422.png)

27. Utilice el análisis de malla para encontrar la corriente I2 en el circuito de la figura 8-81.

![image](https://user-images.githubusercontent.com/84425276/125493368-18423094-ac29-42ca-a1d6-8a5c27f53d24.png)

![image](https://user-images.githubusercontent.com/84425276/125493405-1607878b-070e-4697-a307-cfdb945ceb43.png)

29. Utilice el análisis de malla para encontrar las corrientes de lazo en el circuito de la figura 8-84. Use sus resultados para determinar I y Vab.

![image](https://user-images.githubusercontent.com/84425276/125493439-aeebb5ae-b6c6-4183-9054-70f085ad94cd.png)

![image](https://user-images.githubusercontent.com/84425276/125493450-3bccad46-ee2b-492f-9be4-5764d9ba5f9b.png)

![image](https://user-images.githubusercontent.com/84425276/125493460-e906a737-2df1-4702-b414-47d78eab7569.png)

31. Escriba las ecuaciones de malla para la red de la figura 8-86. Encuentre las corrientes de lazo con determinantes.

![image](https://user-images.githubusercontent.com/84425276/125493514-d9cbef37-005e-4974-9219-8a69e00188e6.png)

![image](https://user-images.githubusercontent.com/84425276/125493584-4263428a-0713-42ee-9437-a8e8e285b8f2.png)

![image](https://user-images.githubusercontent.com/84425276/125493614-5af3fca0-875d-4943-8f86-d83f4ff0d54b.png)

### 8-6 ANÁLISIS DE NODOS

33. Escriba las ecuaciones de nodos para el circuito de la figura 8-88 y encuentre los voltajes en los nodos.

![image](https://user-images.githubusercontent.com/84425276/125493642-ec719d7d-fe60-4d42-b3f3-a8e0ad4f684f.png)

![image](https://user-images.githubusercontent.com/84425276/125493663-c305e3db-8e8f-4ce4-9a01-95a2aa6f1334.png)

35. Repita el problema 33 para el circuito de la figura 8-90.

![image](https://user-images.githubusercontent.com/84425276/125493694-48f25e84-2fdd-44b8-a9d9-679fe9a3178d.png)

![image](https://user-images.githubusercontent.com/84425276/125493723-5119ed04-1208-4d64-8e01-6834350bd397.png)

![image](https://user-images.githubusercontent.com/84425276/125493735-7417048f-c8fa-4bab-b646-bede583a057b.png)

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

![image](https://user-images.githubusercontent.com/84458025/125494499-ea63b3e1-75dc-4284-8e7b-6f286be92911.png)


53. Utilice PSpice para encontrar las corrientes a través de todos los resistores del
circuito de la figura 8-96.

![image](https://user-images.githubusercontent.com/84458025/125494592-860f582e-5f65-4faf-945e-44aec384b0b2.png)


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

https://youtu.be/mNRnZ8CNKQI

## 6. BIBLIOGRAFÍA

Roobins, A y Miller, W. (2007). *Análisis de circuitos teoría y práctica (4ta ed),* México DF, México: Cengage Learning.

Floyd, T. (2007). *Principios de circuitos eléctricos (8va ed),* México DF, México: Pearson Educación.

Ingeniería Mecafenix.(2017). Potenciómetro ¿Que es y como funciona?. Recuperado de  https://www.ingmecafenix.com/electronica/potenciometro/

Pererira, R.(nd) .  *Conversiones Delta ( ∆ ) - Estrella ( Y ) Estrella ( Y ) - Delta ( ∆ ).* Escuela de Ingeniería Electrónica . Recuperado de  https://repositoriotec.tec.ac.cr/bitstream/handle/2238/10133/Conversiones%20Delta-Estrella%20y%20Estrella-Delta%20%28presentaci%C3%B3n%29.pdf?sequence=1&isAllowed=y.



