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
### 7-2 ANÁLISIS DE CIRCUITOS EN SEIRE - PARALELO
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
### 7-4 POTENCIÓMETROS 
### 7-5 EFECTOS DE CARGA DE LOS INTRUMENTOS
### 7-6 ANÁLISIS DE CIRCUITOS POR COMPUTADORA
## 8. MÉTODO DE ANÁLISIS
### 8-1 FUENTES DE CORRIENTE CONSTANTE
### 8-2 CONVERSIONES DE FUENTE
### 8-3 FUENTES DE CORRIENTE EN PARALELO Y EN SERIE
### 8-4 ANÁLISIS DE CORRIENTE DE RAMA
### 8-5 ANÁLISIS DE CORRIENTE DE MALLAS (LAZOS)
### 8-6 ANÁLISIS DE NODOS
### 8-7 CONVERSÍON DELTA-Y (PI-T)
### 8-8 REDES PUENTE
47. Vea el circuito puente de la figura 8-100:
a. El puente esta balanceado? Explique.
b. Escriba las ecuaciones de malla.
c. Calcule la corriente a través de R_5.
d. Determine el voltaje en R_5.

![image](https://user-images.githubusercontent.com/84431598/124700201-ece5e880-deb1-11eb-9d1e-dd1c18e12b2a.png)

a) Para que el circuito este balanceado tiene que cumplir lo siguiente:

![image](https://user-images.githubusercontent.com/84431598/124700375-42ba9080-deb2-11eb-8f4b-76c8ceb02f63.png)

Como no se cumple el circuito no está balanceado.

b)

![image](https://user-images.githubusercontent.com/84431598/124700589-97f6a200-deb2-11eb-9b03-c753012965f9.png)

![image](https://user-images.githubusercontent.com/84431598/124700695-c7a5aa00-deb2-11eb-8cb5-65c1332b8b69.png)

Sistema de Ecuaciones:

![image](https://user-images.githubusercontent.com/84431598/124700840-17847100-deb3-11eb-863d-b0c0e273e85b.png)

c)

![image](https://user-images.githubusercontent.com/84431598/124700903-3e42a780-deb3-11eb-9b17-f438cc30e1d6.png)

d)

![image](https://user-images.githubusercontent.com/84431598/124700998-69c59200-deb3-11eb-99c7-7581d7a038af.png)

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

![image](https://user-images.githubusercontent.com/84431598/124701524-5bc44100-deb4-11eb-808a-ad29913e654d.png)

La corriente del circuito es:

![image](https://user-images.githubusercontent.com/84431598/124701654-91692a00-deb4-11eb-8148-4349f6646728.png)

La corriente en cada rama se calcula entonces con la regla del divisor de corriente:

![image](https://user-images.githubusercontent.com/84431598/124701746-b6f63380-deb4-11eb-96f3-d4db44eebced.png)

Tomando en cuenta que I_R1=I_R3 y I_R2=I_R4 entonces:

![image](https://user-images.githubusercontent.com/84431598/124702160-8ebb0480-deb5-11eb-9a70-9c6b4590d632.png)

### 8-9 ANÁLISIS DE CIRCUITOS POR COMPUTADORA

## 4. CONCLUSIONES
## 5. VIDEO
## 6. BIBLIOGRAFÍA

Roobins, A y Miller, W. (2007). *Análisis de circuitos teoría y práctica (4ta ed),* México DF, México: Cengage Learning.

Floyd, T. (2007). *Principios de circuitos eléctricos (8va ed),* México DF, México: Pearson Educación.

Ingeniería Mecafenix.(2017). Potenciómetro ¿Que es y como funciona?. Recuperado de  https://www.ingmecafenix.com/electronica/potenciometro/

Pererira, R.(nd) .  *Conversiones Delta ( ∆ ) - Estrella ( Y ) Estrella ( Y ) - Delta ( ∆ ).* Escuela de Ingeniería Electrónica . Recuperado de  https://repositoriotec.tec.ac.cr/bitstream/handle/2238/10133/Conversiones%20Delta-Estrella%20y%20Estrella-Delta%20%28presentaci%C3%B3n%29.pdf?sequence=1&isAllowed=y.



