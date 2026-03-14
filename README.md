
# :fa-plug: Laboratorio de Electrónica Digital  
## Circuito 555 + Compuertas Lógicas + Control de LED con Switch

![Electronics](https://img.shields.io/badge/Electrónica-Digital-blue)
![IC](https://img.shields.io/badge/IC-555-green)
![Logic Gates](https://img.shields.io/badge/Logic-Gates-orange)

Este repositorio presenta el desarrollo de un **laboratorio de electrónica digital**, donde se estudian tres conceptos fundamentales:

- Funcionamiento de **compuertas lógicas**
- Uso de **circuitos integrados serie 74HC y 74LS**
- Implementación de un **circuito con temporizador 555**
- Control de un **LED mediante un switch**

El objetivo es comprender cómo los **sistemas digitales procesan señales binarias (0 y 1)** y cómo estos conceptos pueden implementarse físicamente en un circuito electrónico.

---

#:fa-desktop: 1. Fundamentos de Electrónica Digital

En la electrónica digital los circuitos trabajan con **dos estados lógicos**.

| Valor | Significado | Voltaje |
|------|-------------|-------|
| 0 | Nivel Bajo (LOW) | 0V |
| 1 | Nivel Alto (HIGH) | 5V |

Las **compuertas lógicas** reciben una o más señales de entrada y producen una salida según reglas matemáticas.

Estas compuertas se encuentran dentro de **circuitos integrados (IC)** utilizados en:

- Computadores
- Microprocesadores
- Teléfonos celulares
- Sistemas digitales
- Automatización electrónica

---

# :fa-rocket: 2. Series de Circuitos Integrados

## Serie 74HC

**HC = High-Speed CMOS**

| Característica | Descripción |
|---------------|-------------|
| Tecnología | CMOS |
| Consumo de energía | Muy bajo |
| Voltaje de alimentación | 2V a 6V |
| Velocidad | Alta |
| Inmunidad al ruido | Alta |

### Ventajas

- Bajo consumo de energía
- Puede trabajar con diferentes voltajes
- Alta inmunidad al ruido
- Muy usado en electrónica moderna

---

## Serie 74LS

**LS = Low Power Schottky**

| Característica | Descripción |
|---------------|-------------|
| Tecnología | TTL |
| Voltaje de alimentación | 5V |
| Consumo de energía | Mayor que CMOS |
| Velocidad | Alta |

### Ventajas

- Muy robustos
- Respuesta rápida
- Muy usados en sistemas digitales clásicos

---

# :fa-calculator: 3. Compuertas Lógicas

Las compuertas lógicas realizan operaciones matemáticas sobre señales binarias.

---

## :fa-steam-square: Compuerta AND

La salida es **1 solamente cuando todas las entradas son 1**.

| A | B | Salida |
|---|---|---|
|0|0|0|
|0|1|0|
|1|0|0|
|1|1|1|

---

## :fa-steam-square: Compuerta OR

La salida es **1 cuando al menos una entrada es 1**.

| A | B | Salida |
|---|---|---|
|0|0|0|
|0|1|1|
|1|0|1|
|1|1|1|

---

## :fa-steam-square: Compuerta NOT

Invierte la señal de entrada.

| A | Salida |
|---|---|
|0|1|
|1|0|

---

## :fa-steam-square: Compuerta NAND

Es la **negación de la compuerta AND**.

| A | B | Salida |
|---|---|---|
|0|0|1|
|0|1|1|
|1|0|1|
|1|1|0|

---

## :fa-steam-square: Compuerta NOR

Es la **negación de la compuerta OR**.

| A | B | Salida |
|---|---|---|
|0|0|1|
|0|1|0|
|1|0|0|
|1|1|0|

---

## :fa-steam-square: Compuerta XOR

La salida es **1 cuando las entradas son diferentes**.

| A | B | Salida |
|---|---|---|
|0|0|0|
|0|1|1|
|1|0|1|
|1|1|0|

---

#  :fa-plug:  4. Circuitos Integrados de Compuertas

| Circuito Integrado | Tipo de Compuerta | Cantidad |
|-------------------|------------------|----------|
| 74HC08 / 74LS08 | AND | 4 |
| 74HC32 / 74LS32 | OR | 4 |
| 74HC04 / 74LS04 | NOT | 6 |
| 74HC00 / 74LS00 | NAND | 4 |
| 74HC02 / 74LS02 | NOR | 4 |
| 74HC86 / 74LS86 | XOR | 4 |

Esto significa que **un solo chip contiene varias compuertas lógicas**.

---

# :fa-clock-o: 5. Temporizador 555

El **circuito integrado 555** es uno de los componentes más usados en electrónica.

Puede funcionar como:

- Temporizador
- Oscilador
- Generador de pulsos

En este laboratorio se utiliza para generar una señal que permite **encender y apagar un LED periódicamente**.

---

# :fa-lightbulb-o: 6. Circuito LED con Switch

El LED puede ser controlado mediante un **interruptor (switch)**.

### Funcionamiento

1. El switch se conecta a la entrada del circuito  
2. Cuando el switch se cierra → pasa corriente  
3. El LED recibe energía → se enciende  
4. Cuando el switch se abre → se corta la corriente → el LED se apaga

### Componentes utilizados

- LED
- Resistencia limitadora
- Switch
- Fuente de 5V
- Protoboard
- Cables de conexión

La resistencia es importante para **evitar que el LED se queme por exceso de corriente**.

---

# :fa-file-text: 7. Conclusión

Las **compuertas lógicas y los circuitos integrados** constituyen la base de la electrónica digital.

Mediante el uso de dispositivos como el **temporizador 555**, resistencias, LEDs y switches, es posible construir circuitos que representen operaciones lógicas reales.

Este laboratorio demuestra cómo los conceptos teóricos de la lógica digital pueden **implementarse físicamente en un circuito electrónico**, permitiendo comprender el funcionamiento fundamental de los sistemas digitales modernos.




<p>

</p>
