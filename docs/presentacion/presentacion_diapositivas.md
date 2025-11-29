---
marp: true
paginate: true
class: portada
html: true


style: |

  /* Fondo general estilo Material Design */
  section {

    background: #5587b50d; /* gris claro */
    color: #212121; /* texto oscuro */
    font-size: 30px;
    font-family: 'Open sans', 'Helvetica', sans-serif;
    strong { color: #2980b9; }
    .highlight { color: #c0392b; }
     }

  /* Títulos grandes y llamativos */
  h1 {
    color: #1976d2; /* azul vibrante */
    font-size: 50px;
    font-weight: 700;
    text-transform: uppercase;
  }

  h2 {
    color: #e67e22;
    font-size: 40px;
    font-weight: 600;
  }

  h3 {
    color: #8e44ad;
    font-size: 30px;
    font-weight: 600;
  }
  
  /* Caja de información estilo Material */
  .box {
    background: #bbdefb; /* azul claro */
    color: #0d47a1; /* azul oscuro */
    padding: 16px;
    border-radius: 8px;
    margin: 16px 0;
  }


    .question-box {
    font-weight: 600;
    background-color: #f4f3f3ff;
    border-left: 8px solid #e67e22;
    padding: 20px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    border-radius: 4px;
    margin-bottom: 20px;
  }


    /* Clase personalizada para notas/definiciones */
  .note {
    background-color: #eaf2f8;
    border-left: 6px solid #2980b9;
    padding: 20px;
    border-radius: 4px;
    margin: 20px 20px 20px 0;
    font-size: 25px;
  }

    /* Estilo para fórmula matemática grande */
  .formula-box {
    text-align: center;
    font-size: 1.2em;
    padding: 10px;
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    margin: 10px 0;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
  }

    /* Estilos de tabla */
  table { width: 100%; border-collapse: collapse; font-size: 23px; margin-top: 10px; margin-left: auto; margin-right: auto; }
  th { background-color: #2c3e50; color: white; border: 1px solid #2c3e50; }
  td { border: 1px solid #ddd; padding: 14px; }
  tr:nth-child(even) { background-color: #f2f2f2; }

  .examples {
    padding-left: 0;
    margin-top: 25px;
    border-top: 1px solid #ccc;
    padding-top: 15px;
  }
  .examples h3 {
    color: #2c3e50;
    margin-bottom: 10px;
  }
  /* Ajuste de lista para mejor espacio */
  ul {
    padding-left: 20px;
    margin-top: 10px;
  }

  /* Estilo para bloques de código */
  pre {
    background: #f5f5f5;
    padding: 15px;
    border-radius: 8px;
    overflow-x: auto;
    font-size: 18px;
    line-height: 1.4;
  }
  .highlight-prop {
    color: #226457cd;
    font-weight: bold;
  }
  .definition-box {
    margin-top: 20px;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 8px;
    background-color: #eaf2f8;
    color: #2c3e50;
    font-size: 22px;
  }

  /* Columnas flexibles */
  .cols { display:flex; gap:18px; margin-top:20px; font-size: 0.9em; }
  .col1 { flex:1; }
  .col2 { flex:2; }
  .col15 { flex:1.5; }

  /* Portada centrada */
  .portada {
    text-align:right;
  }

  /* Pie de página más pequeño */
  footer {
    font-size: 0.6em;
    color: #616161;
  }

  /* Columnas flexibles */
  .cols { display:flex; gap:18px; margin-top:20px; font-size: 0.9em; }
  .col1 { flex:1; }
  .col2 { flex:2; }
  .col15 { flex:1.5; }


  /* Pie de página más pequeño */
  footer {
    font-size: 0.6em;
    color: #616161;
  }
---
# ⚡ Fundamentos de la Electricidad

## Un Viaje desde el Átomo hasta la Ley de Ohm

_Una forma de energía cómoda, limpia y fácil de transformar en luz, calor o movimiento_.

---


# La Estructura de la Materia



<div class="note">

  El **átomo** es el componente fundamental de la materia, y proporciona sus propiedades

</div>

![bg right:30% fit](../media/atomo.gif)

| *ZONA*    | PARTÍCULA                    | CARGA              | FUNCIÓN                               |
| :------ | :---------------------------- | :----------------- | :------------------------------------- |
| NÚCLEO | **Protón** ($p^+$)   | Positiva (+)       | Carga positiva del átomo              |
| NÚCLEO | **Neutrón** ($n$)    | Neutra (sin carga) | Sin carga eléctrica                   |
| CORTEZA | **Electrón** ($e^-$) | Negativa (-)       | Responsable de la corriente eléctrica |


--- 
## Fuerzas de atracción y de repulsión
* **Cargas iguales** se **repelen** ($+$/$+$ o $-$/$-$).
  * *Experimento*: Frotar dos bolas con lana las carga positivamente y se alejan.
* **Cargas opuestas** se **atraen** ($+$/$-$).
  * *Experimento*: Frotar una bola con lana (+) y otra con un globo (-) hace que se atraigan.

> 💡 Un **átomo neutro** tiene el mismo número de protones que de electrones.

---


# LA CORRIENTE ELÉCTRICA

La **corriente eléctrica** es el **movimiento ordenado** de **electrones** a lo largo de un cuerpo (conductor) en un mismo sentido.

* Si el salto de electrones es **caótico**, no hay corriente eléctrica.
* Si los electrones se mueven en una **dirección específica** (ordenada), sí hay corriente.

### Generadores Eléctricos: Los Impulsores

Los **generadores** (pilas, baterías...) son los responsables de este orden.
Mantienen una **fuerza (Voltaje)** que **empuja** a los electrones desde el polo **negativo** al polo **positivo**.

---

# El CIRCUITO ELÉCTRICO

Un **circuito eléctrico** es un **camino cerrado** por el que circulan los electrones.

### Requisitos Esenciales

Para que haya corriente eléctrica, son imprescindibles:

1. **Fuerza/Energía**: Que mueva los electrones (ej: pila).
2. **Material Conductor**: Por el que circulen los electrones.
3. **Camino Cerrado**: Para que el movimiento sea continuo.

---

## 1. Generadores

| CATEGORÍA            | FUNCIÓN                                                                               | EJEMPLOS                                                          | SÍMBOLO |
| :-------------------- | :------------------------------------------------------------------------------------- | :---------------------------------------------------------------- | :------- |
| **Generadores** | Producen la corriente eléctrica (Voltaje).                                            | Pila, batería, dinamo.                                           |          |


---

## 2. Conductores

| CATEGORÍA            | FUNCIÓN      | EJEMPLOS      | SÍMBOLO |
| :------------ | :---------------- | :------------ | :------- |
| **Conductores** | Sirven para**conectar** los demás componentes y permiten el paso de electrones. | Cables de **cobre** (por ser dúctil y excelente conductor). |          |

> 🧐 **Curiosidad**: Los cables de cobre están recubiertos de plástico (aislante) para poder manipularlos sin riesgo de descarga.
---


## 3. Receptores (Transformadores de Energía)

Los receptores transforman la energía eléctrica en otro tipo de energía **útil**.

| RECEPTOR                    | TRANSFORMACIÓN DE ENERGÍA                                | SÍMBOLO | USO TÍPICO             |
| :-------------------------- | :--------------------------------------------------------- | :------- | :---------------------- |
| **Lámpara/Bombilla** | Eléctrica$\rightarrow$ **Luminosa**               |          | Iluminación            |
| **Motor Eléctrico**  | Eléctrica$\rightarrow$ **Cinética** (Movimiento) |          | Batidoras, ventiladores |
| **Zumbador**          | Eléctrica$\rightarrow$ **Sonora**                 |          | Alarmas, indicadores    |

---



## 4. Elementos de Control (Maniobra)

Permiten **conectar y desconectar** el circuito a voluntad o **dirigir** la corriente.

| ELEMENTO                | FUNCIÓN                                                                                  | ESTABILIDAD | SÍMBOLO |
| :---------------------- | :---------------------------------------------------------------------------------------- | :---------- | :------- |
| **Interruptor**   | Abre o cierra el circuito de forma **permanente** (biestable).                       | Biestable   |          |
| **Pulsador N.A.** | Cierra el circuito **solo al oprimir** (Normalmente Abierto).                        | Monoestable |          |
| **Conmutador**    | Abre un circuito al mismo tiempo que **cierra otro** (selecciona entre dos caminos). | Biestable   |          |

---

## 5. Elementos de Protección

Protegen a los usuarios y a los componentes de **subidas inesperadas de tensión** o sobrecargas.

| ELEMENTO                              | FUNCIÓN                                                                                                                                          | MECANISMO          |
| :------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------ | :----------------- |
| **Fusible**                     | Se **funde** (se rompe el hilo) si la intensidad supera un valor, interrumpiendo la corriente.                                               | Calor/Fusión      |
| **Interruptor Magnetotérmico** | Dispositivo que  **corta la corriente** cuando detecta que está pasando más electricidad de la que los cables soportan (evita sobrecargas). | Magnetismo y calor |

---

# ESQUEMAS ELÉCTRICOS

> Es posible conectar receptores en **serie** (uno a continuación del otro) o en **paralelo** (permitiendo control individual).

---

# MAGNITUDES ELÉCTRICAS FUNDAMENTALES
Las tres magnitudes eléctricas básicas son:
1. **Voltaje o Tensión ($V$)**
2. **Resistencia Eléctrica ($R$)**
3. **Intensidad de Corriente ($I$)**

---


## 1. Voltaje o Tensión ($V$)

* **Definición**: Es la "fuerza" que **empuja** a los electrones para que se muevan.
* **Símil**: La **altura** de una rampa que facilita el movimiento de coches. A más voltaje, más electrones se mueven.
* **Unidad**: **Voltio** ($v$).
* **Medición**: Se usa un **Voltímetro** y se conecta en **paralelo** al circuito.

---



## 2. Resistencia Eléctrica ($R$)

* **Definición**: Es la **oposición** o **dificultad** que ofrece el material al paso de la corriente.
* **Símil**: El **estrechamiento** de una carretera que genera "atascos".
* **Unidad**: **Ohmio** ($\Omega$).

* **Medición**: Se usa un **Óhmetro** (desconectando el elemento a medir).

### Factores que afectan a la Resistencia
Depende de la **naturaleza** del material, su **longitud** y su **sección** (grosor).
  * *Relación*: A más resistencia, menos electrones en movimiento.
---



## 3. Intensidad de Corriente ($I$)

* **Definición**: El **número de cargas** (electrones) que atraviesan la sección de un conductor en la **unidad de tiempo** (1 segundo).
* **Símil**: La **cantidad de tráfico** (coches) que circula por la carretera en 1 segundo.
* **Unidad**: **Amperio** ($A$).
* **Medición**: Se usa un **Amperímetro** y se conecta en **serie** con los otros componentes.

---

# LE LEY DE OHM


El físico **George Simon Ohm** (1827) estableció la relación entre las tres magnitudes.

### Enunciado

> La **Intensidad de corriente** ($I$) es **directamente proporcional** al **Voltaje** ($V$) aplicado e **inversamente proporcional** a la **Resistencia eléctrica** ($R$) del circuito.

### Fórmula Principal

$$
\Large I = \frac{V}{R}
$$

---

### Relaciones Clave

| Factor              | Si...             | Entonces $I$ ...   | Proporcionalidad |
| :------------------ | :---------------- | :------------------ | :--------------- |
| Voltaje ($V$)     | **Aumenta** | **Aumenta**   | Directa          |
| Resistencia ($R$) | **Aumenta** | **Disminuye** | Inversa          |

---


## Despejes

A partir de la fórmula principal, podemos despejar las otras magnitudes:

### 1. Para calcular la Intensidad ($I$)
$$
\ I = \frac{V}{R}
$$

### 2. Para calcular el Voltaje ($V$)

$$
\ V = I \times R
$$

### 3. Para calcular la Resistencia ($R$)

$$
\ R = \frac{V}{I}
$$

---

### Ejercicio de Ejemplo

Un circuito tiene una pila de **$9v$** y una bombilla de **$3\Omega$**. ¿Cuál es la Intensidad ($I$) que circula?

**Solución:**

$$
I = \frac{V}{R} = \frac{9v}{3\Omega} = 3A
$$

La Intensidad es de **3 Amperios**.