# Capítulo 0: El Mundo Secreto de los Algoritmos

## Introducción: El Pensamiento Computacional No Es Solo para Programadores

Te despiertas, agarras tu celular y abres TikTok. En segundos, tu feed está lleno de videos que parecen hechos solo para ti: clips graciosos, highlights de deportes, trucos de cocina, tal vez algunos tutoriales de programación. ¿Cómo "sabe" TikTok lo que te gusta? La respuesta: un **algoritmo**.

Le pides a Google Maps que te lleve a la casa de tu amigo. La app no elige cualquier ruta, encuentra la más rápida evitando el tráfico y las calles cerradas. ¿Cómo? Otro **algoritmo**.

Juegas FIFA y notas que el oponente controlado por la IA lee tus movimientos, ajusta su defensa y a veces se siente injustamente bueno. Eso no es magia, es un **algoritmo** tomando decisiones en tiempo real.

**Los algoritmos están en todas partes.** Deciden qué ves en línea, cómo responden tus juegos, qué productos aparecen cuando compras, e incluso cómo tu app de música crea playlists. Pero aquí está la clave: **no necesitas ser programador para entenderlos**. Antes de escribir una sola línea de código, necesitas aprender a **pensar algorítmicamente**, a descomponer problemas en pasos claros y lógicos.

De eso trata este capítulo. No de sintaxis de Python, no de memorizar comandos, sino de entrenar tu cerebro para ver el mundo a través del lente de **instrucciones, entradas y salidas**. Porque una vez que dominas esta forma de pensar, programar se vuelve la parte fácil.

> **💡 Objetivo del Capítulo:**
> Al final de este capítulo, podrás identificar algoritmos en situaciones cotidianas, entender su estructura básica (entrada, proceso, salida), y escribir tu primer algoritmo en **pseudocódigo**, una forma simple y amigable de describir lógica antes de traducirla a código.

## Definiendo los Algoritmos

### ¿Qué es un Algoritmo, Realmente?

Un **algoritmo** es una **secuencia finita de instrucciones bien definidas** diseñada para resolver un problema específico o cumplir una tarea. Piénsalo como una receta, un conjunto de direcciones, o un manual paso a paso que cualquiera (o cualquier cosa, como una computadora) puede seguir para ir de un punto de partida a un resultado deseado.

Desglosemos esa definición:

- **Finito:** Tiene un inicio y un final claros. No corre para siempre.
- **Bien definido:** Cada instrucción es precisa y sin ambigüedades. No hay espacio para la confusión.
- **Secuencial:** Los pasos ocurren en un orden específico.
- **Orientado a resolver problemas:** Está diseñado para lograr un objetivo.

Aquí está la revelación clave: **los algoritmos existen fuera de las computadoras**. Los humanos han usado algoritmos durante miles de años, mucho antes de que se construyera la primera computadora.

### Analogía 1: La Receta de Cocina

Imagina que quieres hacer huevos revueltos. No simplemente tiras huevos en una sartén y esperas lo mejor. Sigues una **receta**:

- Rompe 2 huevos en un tazón.
- Agrega una pizca de sal.
- Bate los huevos con un tenedor hasta que se mezclen.
- Calienta una sartén a fuego medio.
- Vierte los huevos en la sartén.
- Revuelve continuamente durante 2 minutos.
- Retira del fuego y sirve.

Esto es un **algoritmo**. Cada paso es claro. Sabes qué hacer, en qué orden, y cuándo parar. Si alguien más sigue la misma receta, obtendrá el mismo resultado.

Ahora, ¿qué pasaría si la receta dijera: "Cocina los huevos hasta que estén listos"? Eso es **ambiguo**. ¿Cómo sabes cuándo están "listos"? Por eso la **precisión** importa. En programación, la ambigüedad causa bugs.

### Analogía 2: Direcciones a la Casa de un Amigo

Digamos que le estás dando direcciones a tu amigo para llegar a tu casa:

- Sale de tu edificio y gira a la izquierda.
- Camina 3 cuadras derecho.
- Gira a la derecha en la farmacia azul.
- Camina 2 cuadras más.
- Mi casa es la blanca con la puerta roja, a la izquierda.

De nuevo, esto es un **algoritmo**. Tu amigo sigue los pasos en orden y llega a tu casa. Si omites un paso (como olvidar mencionar la farmacia azul), se perderá. Si dices "gira a la derecha en alguna farmacia", podría girar en la equivocada.

**La lección:** Los algoritmos deben ser **claros, completos y ordenados** para funcionar correctamente.

### Características Clave de los Algoritmos

Formalicemos qué hace que algo sea un algoritmo:

| Característica | Descripción | Ejemplo |
|----------------|-------------|---------|
| **Preciso** | Cada instrucción es inequívoca y específica. | "Gira a la derecha en la farmacia azul" (no "gira en algún lugar") |
| **Ordenado** | Los pasos ocurren en una secuencia definida. | No puedes servir los huevos antes de cocinarlos. |
| **Finito** | Debe eventualmente terminar. | La receta termina cuando sirves el platillo. |
| **Efectivo** | Cada paso debe ser realizable. | "Bate los huevos con un tenedor" es algo que cualquiera puede hacer. |
| **Orientado a objetivos** | Resuelve un problema específico o cumple una tarea. | El objetivo es hacer huevos revueltos o llegar a un destino. |

> **📝 Nota:**
> No todo conjunto de instrucciones es un algoritmo. "Sé feliz" es un consejo, pero no es un algoritmo, es demasiado vago y no define pasos. "Sonríe durante 10 segundos, piensa en algo gracioso, luego respira profundo" está más cerca de ser un algoritmo porque es accionable y específico.

### Algoritmos vs. Recetas: Una Comparación

Aquí hay una comparación lado a lado para solidificar el concepto:

| Receta | Algoritmo |
|--------|-----------|
| Ingredientes (huevos, sal) | **Entrada** (datos con los que empiezas) |
| Pasos de cocina (batir, calentar, revolver) | **Proceso** (transformaciones aplicadas a la entrada) |
| Platillo terminado (huevos revueltos) | **Salida** (el resultado) |
| Debe ser precisa ("2 minutos") | Debe ser preciso (sin ambigüedad) |
| Debe estar en orden (calentar sartén antes de verter) | Debe estar en orden (los pasos son secuenciales) |
| Tiene un final claro (servir) | Tiene un final claro (termina) |

## Pensamiento Algorítmico en Acción

### ¿Qué es el Pensamiento Algorítmico?

El **pensamiento algorítmico** es la habilidad mental de descomponer problemas complejos en pasos más pequeños y lógicos. Se trata de preguntar:

- ¿Con qué necesito empezar? (**Entrada**)
- ¿Qué pasos tomo para transformar esa entrada? (**Proceso**)
- ¿Qué quiero al final? (**Salida**)

Haces esto naturalmente en la vida cotidiana sin darte cuenta. Veamos algunos ejemplos del mundo real donde el pensamiento algorítmico ya está en acción.

### Ejemplo 1: El Algoritmo de Recomendación de TikTok

**El Problema:** TikTok tiene millones de videos. ¿Cómo decide cuáles mostrarte *a ti*?

**El Algoritmo (Simplificado):**

1. **Entrada:** Tu comportamiento pasado (videos que te gustaron, compartiste, viste hasta el final, o saltaste).
2. **Proceso:**
   - Analizar patrones: "Este usuario le gustan los videos de básquetbol."
   - Compararte con usuarios similares: "Los usuarios a quienes les gustó básquetbol también les gustaron videos de cocina."
   - Puntuar videos basándose en interés predicho: "Este nuevo video de básquetbol obtiene un puntaje de 9.5 para este usuario."
3. **Salida:** Tu feed personalizado, ordenado por puntaje.

**Por qué esto importa:** El algoritmo de TikTok no es magia. Es un conjunto de reglas que procesa tus datos y toma decisiones. Entre más interactúas, más datos tiene, y mejores se vuelven sus predicciones.

> **💡 Perspectiva del Programador:**
> Esto se llama un **algoritmo de recomendación**. Compañías como Netflix, Spotify y YouTube usan sistemas similares. La idea clave: convertir comportamiento humano en datos, procesarlos con reglas, y producir un resultado personalizado.

### Ejemplo 2: Google Maps Encuentra la Ruta Más Rápida

**El Problema:** Necesitas ir del Punto A (tu casa) al Punto B (la escuela). Google Maps necesita encontrar la mejor ruta.

**El Algoritmo (Simplificado):**

1. **Entrada:** Tu ubicación de inicio, destino, datos actuales de tráfico, calles cerradas, límites de velocidad.
2. **Proceso:**
   - Listar todas las rutas posibles.
   - Calcular tiempo de viaje para cada ruta (distancia ÷ velocidad, ajustado por tráfico).
   - Comparar rutas y clasificarlas.
3. **Salida:** La ruta más rápida, mostrada en tu pantalla.

**Por qué esto importa:** Google Maps no tiene a un humano sentado ahí dibujando rutas para ti. Tiene un algoritmo que corre en milisegundos, procesando cantidades masivas de datos para darte la mejor respuesta.

> **📝 Nota:**
> Este tipo de algoritmo se llama **algoritmo de búsqueda de rutas**. Se usa en videojuegos (cómo los enemigos te persiguen), robótica (cómo los robots navegan), y logística (cómo los camiones de entrega optimizan rutas).

### Ejemplo 3: IA de Videojuegos (Comportamiento del Oponente en FIFA)

**El Problema:** El oponente controlado por IA en FIFA necesita reaccionar a tus movimientos en tiempo real.

**El Algoritmo (Simplificado):**

1. **Entrada:** Posición de tu jugador, ubicación del balón, formación de tu equipo.
2. **Proceso:**
   - Si estás atacando, posicionar defensores cerca de tus delanteros.
   - Si pasas a la izquierda, predecir la trayectoria y mover un defensor para interceptar.
   - Si disparas, el portero calcula la trayectoria del balón y se lanza.
3. **Salida:** Los jugadores IA se mueven, bloquean, tackean, o interceptan según la situación.

**Por qué esto importa:** La IA no "piensa" como un humano. Está siguiendo un **árbol de decisiones**, un conjunto de reglas de si/entonces que reaccionan a tus acciones. Entre mejor sea el algoritmo, más realista se siente la IA.

> **⚠️ Errores Comunes:**
> Muchos principiantes piensan que la IA en juegos es "inteligente" en el sentido humano. No lo es. Es solo un conjunto de reglas muy rápido y muy bien diseñado. La ilusión de inteligencia viene del **buen diseño algorítmico**.

### Ejemplo 4: Netflix Decide Qué Recomendar Después

**El Problema:** Acabas de terminar de ver *Stranger Things*. ¿Qué debería sugerir Netflix a continuación?

**El Algoritmo (Simplificado):**

1. **Entrada:** El show que viste, tu historial de visualización, calificaciones que diste, shows que usuarios similares disfrutaron.
2. **Proceso:**
   - Etiquetar *Stranger Things* con géneros: ciencia ficción, thriller, nostalgia de los 80s.
   - Encontrar otros shows con etiquetas similares.
   - Filtrar por shows que aún no has visto.
   - Clasificar por interés predicho basado en tu comportamiento pasado.
3. **Salida:** Una lista de shows recomendados, mostrados en orden.

**Por qué esto importa:** Netflix no adivina aleatoriamente. Procesa tu historial de visualización para predecir lo que probablemente disfrutarás. Este es el poder del pensamiento algorítmico: convertir datos en decisiones.

> **💡 Consejo:**
> La próxima vez que veas una recomendación en cualquier plataforma, haz una pausa y pregúntate: "¿Qué datos usó? ¿Qué pasos siguió? ¿Qué resultado produjo?" Estás empezando a pensar como un programador.

## La Anatomía de un Algoritmo: Entrada, Proceso, Salida

Cada algoritmo, ya sea que esté recomendando videos, calculando rutas, o haciendo huevos revueltos, sigue la misma estructura de tres partes. Entender este patrón es fundamental para el pensamiento algorítmico.

### Parte 1: Entrada (Input)

La **entrada** son los datos o recursos con los que comienzas. Es lo que le das al algoritmo para que trabaje.

**Ejemplos:**
- **Receta de huevos:** Huevos, sal, sartén
- **Google Maps:** Ubicación actual, destino, datos de tráfico
- **TikTok:** Tu historial de likes, videos vistos, tiempo de visualización
- **Calculadora:** Dos números que quieres sumar

**Pregunta clave:** ¿Qué información o materiales necesito antes de poder empezar?

> **📝 Nota:**
> Sin entrada, no hay nada que procesar. Incluso un programa simple como "imprimir 'Hola Mundo'" tiene una entrada implícita: el texto "Hola Mundo" que el programador escribió en el código.

### Parte 2: Proceso

El **proceso** es el conjunto de pasos que transforman la entrada en la salida deseada. Aquí es donde ocurre la lógica, los cálculos y las decisiones.

**Ejemplos:**
- **Receta de huevos:** Batir, calentar sartén, revolver, cocinar 2 minutos
- **Google Maps:** Listar rutas posibles → calcular tiempos → comparar → clasificar
- **TikTok:** Analizar comportamiento → encontrar patrones → puntuar videos → ordenar
- **Calculadora:** Tomar los dos números y sumarlos usando la operación de adición

**Pregunta clave:** ¿Qué pasos específicos debo tomar para transformar mi entrada en el resultado que quiero?

> **⚠️ Advertencia:**
> Esta es la parte donde los principiantes cometen más errores. Los pasos deben ser:
> - **Ordenados:** en la secuencia correcta
> - **Completos:** sin pasos faltantes
> - **Precisos:** sin ambigüedad sobre qué hacer

### Parte 3: Salida (Output)

La **salida** es el resultado final que produce el algoritmo. Es la razón por la que ejecutas el algoritmo en primer lugar.

**Ejemplos:**
- **Receta de huevos:** Un plato de huevos revueltos perfectamente cocinados
- **Google Maps:** La ruta más rápida mostrada en tu pantalla con tiempo estimado
- **TikTok:** Tu feed personalizado con videos que probablemente te gustarán
- **Calculadora:** La suma de los dos números

**Pregunta clave:** ¿Qué resultado específico quiero obtener al final?

> **💡 Perspectiva del Programador:**
> En programación, la salida puede ser visible (texto en pantalla, una imagen, un archivo guardado) o invisible (datos almacenados en memoria, una señal enviada a otro programa). Lo importante es que siempre haya un resultado claro y medible.

### El Patrón Universal: Entrada → Proceso → Salida

Este patrón de tres partes aparece en absolutamente todo lo que hace una computadora, desde los programas más simples hasta los sistemas de inteligencia artificial más complejos. Reconocerlo es como tener visión de rayos X para entender cómo funcionan las cosas.

```
┌─────────┐      ┌─────────┐      ┌─────────┐
│ ENTRADA │  →   │ PROCESO │  →   │ SALIDA  │
└─────────┘      └─────────┘      └─────────┘
    │                 │                 │
    │                 │                 │
 Datos/          Transformación      Resultado
 Recursos           Lógica           Deseado
```

**Ejercicio mental rápido:** Piensa en cualquier app que uses regularmente. ¿Puedes identificar su entrada, proceso y salida?

| App | 📥 ENTRADA (Datos) | ⚙️ PROCESO (Lógica) | 📤 SALIDA (Resultado) |
|-----|-------------------|---------------------|-----------------------|
| **Instagram** | Tu foto nueva, filtros elegidos, caption. | Aplicar filtro, guardar en servidor, notificar seguidores. | Foto publicada en el feed de tus amigos. |
| **Spotify** | Canciones que escuchas, artistas que sigues. | Comparar tus gustos con otros usuarios, buscar coincidencias. | Playlist "Descubrimiento Semanal". |
| **WhatsApp** | Tu texto, emojis, botón "Enviar". | Encriptar mensaje, enrutar por internet al destinatario. | "Ding" en el celular de tu amigo. |

Ver el mundo a través de este lente de Entrada-Proceso-Salida es pensamiento algorítmico en su forma más pura.

## Introducción al Pseudocódigo: Tu Primer Lenguaje de Programación

Ahora que entiendes qué son los algoritmos y cómo funcionan, necesitas una forma de escribirlos que sea más estructurada que simplemente listar pasos en lenguaje natural, pero menos rígida que el código de programación real.

Aquí es donde entra el **pseudocódigo**.

### ¿Qué es el Pseudocódigo?

**Pseudocódigo** es una forma de describir algoritmos usando una mezcla de lenguaje natural (español) y elementos de estructura de programación, sin preocuparte por la sintaxis exacta de un lenguaje de programación específico.

Piénsalo como el "borrador" o "esqueleto" de tu código. Es lo suficientemente preciso para que otro programador entienda exactamente qué quieres hacer, pero lo suficientemente flexible para que puedas enfocarte en la lógica sin distraerte con detalles técnicos.

### ¿Por Qué Usar Pseudocódigo?

1. **Planifica antes de codificar:** Es mucho más fácil detectar errores de lógica en pseudocódigo que en 200 líneas de Python.
2. **Lenguaje agnóstico:** El mismo pseudocódigo puede traducirse a Python, JavaScript, C++, o cualquier otro lenguaje.
3. **Comunicación clara:** Puedes compartir tu lógica con otros sin que necesiten conocer Python.
4. **Enfoque en la lógica:** Te libera de preocuparte por sintaxis, permitiéndote concentrarte en resolver el problema.

> **💡 Perspectiva del Programador:**
> Los programadores profesionales escriben pseudocódigo antes de codificar, especialmente para algoritmos complejos. Es como hacer un boceto antes de pintar una obra maestra. Nadie salta directamente al código sin un plan, excepto los principiantes que quieren sufrir innecesariamente.

### Convenciones del Pseudocódigo

No existe un estándar universal para pseudocódigo (cada programador tiene su estilo), pero aquí están las convenciones que usaremos en este libro:

#### 1. Estructura General

```
ALGORITMO: NombreDelAlgoritmo

ENTRADA:
  - lista de datos o recursos necesarios

PROCESO:
  - paso 1
  - paso 2
  - paso 3
  ...

SALIDA:
  - resultado esperado
```

#### 2. Operaciones Básicas

| Operación | Pseudocódigo | Significado |
|-----------|--------------|-------------|
| Asignación | `x = 5` | Almacenar el valor 5 en la variable x |
| Suma | `total = a + b` | Sumar a y b, guardar en total |
| Multiplicación | `area = base * altura` | Multiplicar base por altura |
| División | `promedio = suma / cantidad` | Dividir suma entre cantidad |

#### 3. Entrada y Salida

| Acción | Pseudocódigo | Significado |
|--------|--------------|-------------|
| Pedir datos | `Leer nombre` | Solicitar al usuario que ingrese su nombre |
| Mostrar resultados | `Mostrar "Hola " + nombre` | Imprimir un mensaje en pantalla |
| Pedir número | `Leer edad` | Solicitar un valor numérico |

#### 4. Decisiones (Condicionales)

```
SI condición ENTONCES
  - acciones si la condición es verdadera
SINO
  - acciones si la condición es falsa
FIN SI
```

**Ejemplo:**
```
SI edad >= 18 ENTONCES
  Mostrar "Eres mayor de edad"
SINO
  Mostrar "Eres menor de edad"
FIN SI
```

#### 5. Decisiones Múltiples

```
SI condición1 ENTONCES
  - acciones para condición1
SINO SI condición2 ENTONCES
  - acciones para condición2
SINO
  - acciones si ninguna condición es verdadera
FIN SI
```

#### 6. Bucles (Repeticiones)

**Mientras (WHILE)** - Repite mientras una condición sea verdadera:
```
MIENTRAS condición HACER
  - acciones a repetir
FIN MIENTRAS
```

**Para (FOR)** - Repite un número específico de veces:
```
PARA contador = inicio HASTA fin HACER
  - acciones a repetir
FIN PARA
```

### Ejemplo Completo: Calculadora de Promedio de Notas

Veamos cómo aplicar estas convenciones para escribir un algoritmo completo en pseudocódigo.

**Problema:** Calcular el promedio de tres notas de exámenes y determinar si el estudiante aprobó (promedio ≥ 13).

**Pseudocódigo:**

```
ALGORITMO: CalcularPromedioNotas

ENTRADA:
  - nota1: primera nota del examen (0-20)
  - nota2: segunda nota del examen (0-20)
  - nota3: tercera nota del examen (0-20)

PROCESO:
  1. Leer nota1
  2. Leer nota2
  3. Leer nota3
  4. promedio = (nota1 + nota2 + nota3) / 3
  5. SI promedio >= 13 ENTONCES
       Mostrar "APROBADO con promedio: " + promedio
     SINO
       Mostrar "REPROBADO con promedio: " + promedio
     FIN SI

SALIDA:
  - mensaje indicando si aprobó o reprobó
  - el valor del promedio calculado
```

### Análisis del Pseudocódigo

Observa cómo este pseudocódigo:
- **Es claro:** Cualquiera puede seguir la lógica sin conocer Python
- **Es estructurado:** Sigue el patrón Entrada → Proceso → Salida
- **Es preciso:** Cada paso indica exactamente qué hacer
- **Es traducible:** Este pseudocódigo puede convertirse fácilmente a código Python, Java, C++, o cualquier otro lenguaje

> **📝 Nota:**
> Diferentes programadores escriben pseudocódigo con ligeras variaciones (algunos usan "leer" en lugar de "ingresar", "imprimir" en lugar de "mostrar", etc.). Esto está perfectamente bien. Lo importante es la claridad y la consistencia dentro de tu propio pseudocódigo.

## Caso de Estudio: Del Problema Real al Pseudocódigo

Vamos a resolver un problema completo desde cero, aplicando todo lo que has aprendido hasta ahora. Este es el proceso que seguirás cada vez que te enfrentes a un nuevo desafío de programación.

### El Problema: Sistema de Descuento en Tienda

**Escenario:** Trabajas para una tienda en línea. Tu jefe te pide crear un sistema que calcule el precio final de una compra aplicando descuentos según estas reglas:

- Si el cliente es VIP, obtiene 20% de descuento
- Si la compra es mayor a S/. 500, obtiene 15% de descuento adicional
- Si no es VIP y la compra es menor a S/. 500, no hay descuento

**Tu tarea:** Diseñar el algoritmo que calcule el precio final.

### Paso 1: Identificar Entrada, Proceso, Salida

Antes de escribir cualquier pseudocódigo, hazte estas tres preguntas:

**¿Qué datos necesito? (ENTRADA)**
- Precio original de la compra
- ¿El cliente es VIP? (Sí/No)

**¿Qué pasos debo seguir? (PROCESO)**
- Verificar si es cliente VIP
- Verificar el monto de la compra
- Aplicar descuentos según las reglas
- Calcular precio final

**¿Qué resultado quiero? (SALIDA)**
- El precio final a pagar
- Cuánto se ahorró en descuentos

### Paso 2: Pensar en los Casos Posibles

Antes de escribir el algoritmo, identifica todos los escenarios posibles:

| Cliente VIP | Monto | Descuento Total | Ejemplo |
|-------------|-------|-----------------|---------|
| Sí | > S/. 500 | 20% + 15% = 35% | S/. 600 → paga S/. 390 |
| Sí | ≤ S/. 500 | 20% | S/. 400 → paga S/. 320 |
| No | > S/. 500 | 15% | S/. 600 → paga S/. 510 |
| No | ≤ S/. 500 | 0% | S/. 400 → paga S/. 400 |

> **💡 Consejo:**
> Crear esta tabla de casos es una técnica profesional llamada "análisis de casos de prueba". Te ayuda a asegurarte de que tu algoritmo maneje todas las situaciones posibles antes de escribir una sola línea de código.

### Paso 3: Escribir el Pseudocódigo

Ahora que entendemos completamente el problema, podemos escribir el pseudocódigo:

```
ALGORITMO: CalcularPrecioConDescuento

ENTRADA:
  - precio_original: monto de la compra en soles
  - es_vip: indica si el cliente es VIP (Sí/No)

PROCESO:
  1. Leer precio_original
  2. Leer es_vip
  3. descuento_total = 0
  
  4. SI es_vip = "Sí" ENTONCES
       descuento_total = descuento_total + 20
     FIN SI
  
  5. SI precio_original > 500 ENTONCES
       descuento_total = descuento_total + 15
     FIN SI
  
  6. monto_descuento = precio_original * (descuento_total / 100)
  7. precio_final = precio_original - monto_descuento
  
  8. Mostrar "Descuento aplicado: " + descuento_total + "%"
  9. Mostrar "Ahorro: S/. " + monto_descuento
  10. Mostrar "Total a pagar: S/. " + precio_final

SALIDA:
  - porcentaje de descuento aplicado
  - monto ahorrado
  - precio final a pagar
```

### Paso 4: La "Prueba de Escritorio"

Los programadores no solo "esperan" que funcione. Usamos una **Tabla de Traza** para seguir el valor de las variables paso a paso, como si fuéramos la computadora. Vamos a probar el **Caso 1 (VIP, S/. 600)**:

| Paso del Algoritmo | Variable Afectada | Nuevo Valor | Explicación |
|--------------------|-------------------|-------------|-------------|
| 1. Leer precio | `precio_original` | 600 | Entrada del usuario |
| 2. Leer VIP | `es_vip` | "Sí" | Entrada del usuario |
| 3. Inicializar | `descuento_total` | 0 | Valor inicial |
| 4. Condición VIP | `descuento_total` | 20 | Como es "Sí", sumamos 20 |
| 5. Condición >500 | `descuento_total` | 35 | Como 600 > 500, sumamos 15 (20+15) |
| 6. Calcular monto | `monto_descuento` | 210 | 600 * 0.35 |
| 7. Calcular final | `precio_final` | 390 | 600 - 210 |
| **RESULTADO** | **Salida** | **S/. 390** | **CORRECTO** ✅ |

Perfecto. El algoritmo maneja correctamente todos los casos.

> **⚠️ Solución de Problemas:**
> Si encuentras que tu pseudocódigo no maneja correctamente un caso de prueba, no te frustres. Ese es precisamente el valor de escribir pseudocódigo primero: detectar errores de lógica antes de escribir código real. Ajusta tu pseudocódigo y vuelve a probar.

## Laboratorio 1: Identificación de Algoritmos en la Vida Real

### Objetivo
Entrenar tu cerebro para reconocer la estructura algorítmica (Entrada → Proceso → Salida) en situaciones cotidianas.

### Instrucciones

Para cada una de las siguientes actividades de la vida real, identifica:
1. **ENTRADA:** ¿Qué datos o recursos necesitas?
2. **PROCESO:** ¿Qué pasos específicos sigues?
3. **SALIDA:** ¿Cuál es el resultado final?

### Actividad A: Preparar una Taza de Café

**Escenario:** Quieres preparar una taza de café con leche y azúcar.

**Tu análisis:**
```
ENTRADA:
  - [Completa aquí: café molido, agua, leche, azúcar, taza, cafetera, etc.]

PROCESO:
  - [Lista los pasos en orden: calentar agua, agregar café, etc.]

SALIDA:
  - [¿Qué obtienes al final?]
```

### Actividad B: Decidir Qué Ropa Ponerte

**Escenario:** Es la mañana. Necesitas decidir qué ropa usar hoy.

**Tu análisis:**
```
ENTRADA:
  - [¿Qué información consideras? Clima, planes del día, ropa limpia disponible...]

PROCESO:
  - [¿Qué pasos sigues para decidir?]

SALIDA:
  - [¿Cuál es el resultado de esta decisión?]
```

### Actividad C: Encontrar un Video Específico en YouTube

**Escenario:** Quieres encontrar un video de una receta de brownies que viste hace una semana.

**Tu análisis:**
```
ENTRADA:
  - [¿Qué necesitas para empezar la búsqueda?]

PROCESO:
  - [¿Qué pasos sigues?]

SALIDA:
  - [¿Qué obtienes cuando terminas?]
```

### Criterio de Éxito

Habrás completado este laboratorio exitosamente cuando:
1. Puedas identificar claramente las tres partes (Entrada, Proceso, Salida) en cada actividad
2. Tus pasos de PROCESO estén en orden lógico
3. Cada paso sea lo suficientemente específico que otra persona podría seguirlo

> **💡 Consejo:**
> No hay una única respuesta "correcta". Dos personas pueden describir el mismo algoritmo de formas ligeramente diferentes. Lo importante es que sea claro, completo y ordenado.

## Laboratorio 2: Tu Primer Pseudocódigo Original

### Objetivo
Escribir un algoritmo completo en pseudocódigo para resolver un problema real de tu vida.

### Instrucciones

Elige **una** de las siguientes situaciones (o inventa la tuya propia) y escribe el pseudocódigo completo siguiendo la estructura que aprendiste.

#### Opción A: Algoritmo para Decidir Si Salir a Correr

**Problema:** Cada mañana necesitas decidir si sales a correr o no, basándote en el clima y cómo te sientes.

**Reglas de decisión:**
- Si está lloviendo, no salir
- Si te sientes cansado, no salir
- Si hace mucho frío (menos de 15°C) y estás cansado, no salir
- En todos los demás casos, salir a correr

**Tu pseudocódigo:**
```
ALGORITMO: DecibirSiSalirACorrer

ENTRADA:
  - [Completa: ¿qué datos necesitas?]

PROCESO:
  - [Escribe los pasos de decisión usando SI-ENTONCES-SINO]

SALIDA:
  - [¿Qué decides al final?]
```

#### Opción B: Calculadora de Tiempo de Estudio Necesario

**Problema:** Tienes un examen en X días y necesitas calcular cuántas horas por día debes estudiar.

**Reglas de cálculo:**
- Estimar cuántas horas totales de estudio necesitas
- Dividir entre los días disponibles
- Si el resultado es más de 4 horas por día, es demasiado y necesitas empezar antes o ajustar expectativas

**Tu pseudocódigo:**
```
[Escribe aquí el algoritmo completo]
```

#### Opción C: Sistema de Priorización de Tareas

**Problema:** Tienes múltiples tareas pendientes y necesitas decidir cuál hacer primero.

**Criterios de priorización:**
- Tareas con fecha de entrega mañana tienen máxima prioridad
- Entre tareas urgentes, hacer primero las más difíciles
- Tareas sin fecha límite van al final

**Tu pseudocódigo:**
```
[Escribe aquí el algoritmo completo]
```

#### Opción D: Tu Propio Problema

Piensa en alguna decisión o cálculo que haces regularmente en tu vida. Puede ser:
- Cómo decides qué comer
- Cómo calculas si te alcanza el dinero para algo
- Cómo decides qué estudiar primero
- Cómo eliges qué serie ver en Netflix

**Ejemplo de un estudiante anterior:**
```
ALGORITMO: PriorizarTareasEscolares

PROBLEMA:
  Cuando tengo mucho trabajo, necesito decidir por dónde empezar 
  para ser eficiente y no estresarme.

ENTRADA:
  - Lista de todas las tareas pendientes
  - Fecha de entrega de cada trabajo
  - Dificultad estimada de cada trabajo (fácil, media, difícil)

PROCESO:
  1. Escribir todas las tareas en una lista
  2. Para cada tarea, anotar su fecha de entrega
  3. Marcar las tareas que vencen mañana
  4. SI hay tareas que vencen mañana ENTONCES
       - Hacer primero las difíciles (necesitan más tiempo)
       - Luego las medias
       - Finalmente las fáciles
     SINO
       - Repetir el paso anterior con las tareas de pasado mañana
     FIN SI
  5. Tomar la primera tarea de la lista ordenada y empezar

SALIDA:
  - La primera tarea que debo hacer ahora, 
    priorizada por urgencia y dificultad
```

### Criterio de Éxito

Tu algoritmo funciona si:
1. Resuelve el problema que identificaste
2. Es específico y no ambiguo
3. Otro estudiante podría usarlo para resolver el mismo problema

## Laboratorio 3: Depuración Mental

### Objetivo
Practicar identificar y corregir errores en algoritmos (esto se llama "debugging" o depuración).

### Instrucciones

A continuación encontrarás 3 algoritmos que contienen errores. Tu trabajo es:
1. Leer cada algoritmo
2. Identificar qué está mal
3. Escribir la versión corregida

### Caso 1: Algoritmo Defectuoso para Sacar al Perro

```
ALGORITMO: SacarPerroAPasear

ENTRADA:
  - un perro
  - una correa

PROCESO:
  1. Tomar la correa
  2. Abrir la puerta
  3. Salir de la casa con el perro
  4. Caminar 15 minutos
  5. Regresar a casa

SALIDA:
  - perro paseado
```

**Pregunta:** ¿Qué paso crucial falta que podría causar un problema?

> **💡 Pista:**
> Piensa en la seguridad del perro durante el paseo. ¿Qué conecta al perro contigo?

**Tu versión corregida:**
```
[Escribe aquí el algoritmo corregido]
```

### Caso 2: Algoritmo Ambiguo para Hacer Limonada

```
ALGORITMO: HacerLimonada

ENTRADA:
  - limones
  - azúcar
  - agua
  - una jarra

PROCESO:
  1. Exprimir los limones
  2. Poner el jugo en la jarra
  3. Agregar agua
  4. Agregar azúcar
  5. Revolver

SALIDA:
  - limonada
```

**Pregunta:** ¿Qué información falta que hace este algoritmo imposible de seguir con precisión?

> **💡 Pista:**
> ¿Cuántos limones? ¿Cuánta agua? ¿Cuánta azúcar? Las cantidades específicas importan.

**Tu versión corregida:**
```
[Escribe aquí el algoritmo corregido]
```

### Caso 3: Algoritmo con Pasos Desordenados

```
ALGORITMO: PlantarUnaSemilla

ENTRADA:
  - una semilla
  - tierra
  - agua
  - una maceta

PROCESO:
  1. Poner la semilla en la tierra
  2. Regar la tierra con agua
  3. Llenar la maceta con tierra
  4. Colocar la maceta en un lugar con luz solar

SALIDA:
  - semilla plantada lista para crecer
```

**Pregunta:** ¿En qué orden deberían estar realmente estos pasos?

> **💡 Pista:**
> Piensa en el orden lógico: primero preparas el contenedor, luego plantas, luego cuidas.

**Tu versión corregida:**
```
[Escribe aquí el algoritmo corregido]
```

### Criterio de Éxito

Habrás completado este laboratorio exitosamente cuando:
1. Identifiques el error en cada algoritmo
2. Escribas una versión corregida que sea precisa, completa y en el orden correcto
3. Puedas explicar por qué tu versión es mejor

> **⚠️ Solución de Problemas:**
> Si no estás seguro de qué está mal en un algoritmo, intenta "ejecutarlo" mentalmente paso a paso, como si fueras una computadora siguiendo instrucciones literalmente. El punto donde te confundes o algo no tiene sentido es donde está el error.

## Desafío Extra: El Sombrero Seleccionador

¿Te crees un experto en algoritmos? Intenta diseñar la lógica para algo mágico.

**El Problema:**
Diseña el algoritmo para un "Sombrero Seleccionador" que asigne a un estudiante a una de las 4 casas de una escuela de magia basándose en sus rasgos.

**Reglas:**
1.  **Entrada:** El estudiante debe elegir dos cualidades de una lista: Valor, Astucia, Lealtad, Inteligencia.
2.  **Proceso:**
    * Si tiene **Valor**, va a *Gryffindor*.
    * Si tiene **Astucia** (y no Valor), va a *Slytherin*.
    * Si tiene **Inteligencia** (y ni Valor ni Astucia), va a *Ravenclaw*.
    * Si tiene **Lealtad**, va a *Hufflepuff*.
    * *Complicación:* ¿Qué pasa si tiene Valor Y Astucia? (Debes definir una regla de desempate o dejar que el usuario elija).
3.  **Salida:** El nombre de la casa asignada.

**Tu Misión:** Escribe el pseudocódigo completo usando `SI - SINO SI - SINO` anidados. ¡Usa una Tabla de Traza para probarlo!

## Preguntas de Reflexión

Tómate un momento para pensar profundamente sobre estas preguntas. No hay respuestas "correctas" o "incorrectas", el objetivo es conectar lo que aprendiste con tu propia experiencia.

1. **Piensa en una decisión que tomas todos los días (como qué ropa ponerte o qué desayunar):** ¿Sigues un algoritmo mental para esa decisión? Si es así, ¿cuáles son los pasos? ¿Hay entradas que consideras (como el clima o lo que comiste ayer)?

2. **Reflexiona sobre un momento en que seguiste instrucciones que no funcionaron:** ¿Qué estuvo mal con esas instrucciones? ¿Eran ambiguas, estaban desordenadas, o les faltaba información? ¿Cómo las hubieras mejorado?

3. **Imagina que tienes que enseñarle a un robot a hacer tu actividad favorita:** El robot es totalmente literal y solo puede seguir instrucciones precisas. ¿Qué tan difícil sería escribir esas instrucciones? ¿Qué te dice eso sobre cómo las computadoras "piensan"?

4. **Piensa en alguna app o servicio que uses frecuentemente:** ¿Puedes identificar su patrón Entrada → Proceso → Salida? ¿Qué datos le das? ¿Qué hace con esos datos? ¿Qué resultado te devuelve?

5. **Reflexiona sobre tu proceso de aprendizaje en este capítulo:** ¿Qué concepto fue más difícil de entender? ¿Qué técnica te ayudó a comprenderlo mejor? ¿Cómo podrías aplicar esa misma técnica para aprender otros temas?

## Para Recordar

- **Un algoritmo es una secuencia finita de instrucciones bien definidas** para resolver un problema. No es exclusivo de las computadoras; existen en recetas, direcciones y procesos cotidianos.

- **Todo algoritmo sigue el patrón Entrada → Proceso → Salida.** Identificar estas tres partes es el primer paso para resolver cualquier problema computacional.

- **Las cinco características de un buen algoritmo:** Preciso (sin ambigüedad), Ordenado (pasos en secuencia correcta), Finito (termina eventualmente), Efectivo (pasos realizables), y Orientado a objetivos (resuelve un problema específico).

- **El pseudocódigo es tu herramienta de planificación.** Te permite diseñar la lógica de tu programa antes de preocuparte por la sintaxis de un lenguaje de programación específico.

- **Pensar algorítmicamente es una habilidad transferible.** No solo te ayuda a programar, sino a descomponer cualquier problema complejo en pasos manejables.

- **Los errores en pseudocódigo son más fáciles de arreglar que en código real.** Por eso siempre planificas primero y codificas después.

- **Los algoritmos están en todas partes.** Desde cómo TikTok elige tus videos hasta cómo Google Maps encuentra rutas, el mundo digital funciona con algoritmos que siguen el mismo patrón fundamental que acabas de aprender.

## Conectando con el Siguiente Capítulo

Ahora que entiendes qué es un algoritmo y puedes escribir lógica en pseudocódigo, estás listo para el siguiente nivel: **visualizar esa lógica**.

En el **Capítulo 1**, aprenderás sobre **diagramas de flujo**, una forma de dibujar algoritmos usando símbolos y flechas. Los diagramas de flujo te ayudarán a ver el camino que toman tus datos, cómo se toman decisiones, y dónde se repiten pasos. Es como crear un mapa de tu algoritmo.

Pero aquí está la parte interesante: no usaremos software de diagramas sofisticado. Usaremos representaciones en texto ASCII para que puedas crear diagramas de flujo en cualquier lugar, con cualquier herramienta de texto. Es la forma más pura de visualizar lógica, y es exactamente cómo los programadores profesionales bocetan ideas rápidamente.

¿Listo para ver tus algoritmos cobrar vida? Pasemos al Capítulo 1.