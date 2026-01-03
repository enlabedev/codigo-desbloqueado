# CÓDIGO DESBLOQUEADO
## Piensa, Diseña y Programa con Python

**Por ENLABE (Enrique Lazo Bello)**

---

## DEDICATORIA

*A mi sobrino Alejandro:*

*Por tu forma de aprender y cómo solucionas las cosas. Te dejo este libro como una herramienta más para que tus ideas cobren vida.*

---

## AGRADECIMIENTOS

Gracias a **Marco, Ronald, Robert y Manuel**, por la paciencia infinita en las revisiones a mi código y por ayudarme a aprender más cada día sobre Python.

Gracias a **Mila**, por ser mi editora de confianza y dar luz verde a todas mis locuras. Gracias por ayudarme a encontrar la voz correcta para este libro; sin ti, muchas cosas no hubieran sido posibles.


---

## ACERCA DEL AUTOR

Hola, soy **ENLABE**.

Llevo más de **14 años** construyendo el "cerebro" detrás de muchas aplicaciones que usan a diario. He creado sistemas complejos para entidades financieras, he diseñado plataformas de comercio electrónico y he liderado equipos técnicos internacionales.

Actualmente, soy cofundador de **XOFI.AI**, una plataforma tecnológica con una misión clara: **modernizar las cooperativas de ahorro y crédito en Perú y América Latina**.

A lo largo de mi carrera he trabajado con herramientas potentes como Python, Django y la Nube (AWS), pero **la tecnología no sirve de nada si no resuelve un problema humano real**.

Pero no empecé siendo un experto. Empecé exactamente donde estás tú: mirando una pantalla en blanco, muchas veces copiando y pegando código que no entendía, siguiendo el flujo que se generaba y preguntándome cómo convertir una idea en realidad.

Escribí **"Código Desbloqueado"** basado en el concepto de PlayStation y Xbox (sí, también soy jugador amateur de videojuegos: *¡logro desbloqueado!*) porque quiero enseñarte no solo a escribir líneas de código, sino a pensar como un **Ingeniero**: a diseñar soluciones que no se rompan, a entender el impacto de lo que construyes y a tener la confianza para crear tus propios proyectos.

En este libro no te hablo como un catedrático, sino como un mentor que se sienta a tu lado para explicarte cómo funcionan las cosas en el mundo real.

Mi objetivo es simple: darte las herramientas para que tú también pases de ser un usuario de tecnología a ser un **creador de soluciones**.

---

## PREFACIO: POR QUÉ ESTE LIBRO ES DIFERENTE

Vivimos rodeados de millones de algoritmos.

Sacas tu móvil, tocas una aplicación y aparece comida en tu puerta. Hablas al aire y una máquina en la esquina de tu habitación pone tu canción favorita. Escribes un mensaje y llega al otro lado del mundo en milisegundos.

Para la mayoría de las personas, esto parece magia o algo muy difícil. Para los programadores, es simplemente **lógica**.

La mayoría de los libros de programación cometen un error fatal: te enseñan el diccionario antes de enseñarte a hablar. Te obligan a memorizar definiciones de variables, bucles y funciones sin explicarte *para qué sirven* o *qué problema resuelven*. Es como intentar aprender carpintería memorizando los nombres de todas las sierras sin haber tocado nunca un trozo de madera.

**"Código Desbloqueado"** es diferente.

Aquí no empezamos por el código. Empezamos por el **pensamiento**.

1.  **Primero pensamos:** Descomponemos el problema.
2.  **Luego diseñamos:** Dibujamos la solución (sin código).
3.  **Finalmente programamos:** Traducimos esa solución a Python.

Este enfoque es lo que separa a los "coders" (que copian y pegan sin entender) de los **desarrolladores de software** (que crean soluciones robustas).

No te voy a mentir: aprender a pensar de esta manera requiere esfuerzo. Tu cerebro tendrá que estirarse en direcciones nuevas. Habrá momentos de frustración. Habrá bugs que te parecerán imposibles de resolver.

Pero te prometo algo: al otro lado de esa frustración hay un superpoder real. La capacidad de crear cosas de la nada usando solo tu mente y un teclado.

Bienvenido al mundo de los programadores.

---

## CÓMO LEER ESTE LIBRO

Este no es un libro para leer en el sofá. Es un libro para leer con las manos en el papel, en una pizarra o en el teclado. Para sacarle el máximo provecho, necesitas entender las reglas del juego.

### 1. La Regla de "Cero Imágenes"
Notarás algo extraño: este libro no tiene capturas de pantalla. No verás fotos de menús, ni ventanas de instalación.

Esto es intencional.

Las interfaces cambian. Los menús se mueven. Si aprendes a buscar "el botón azul en la esquina", te perderás cuando el botón sea verde. En cambio, usaremos **visualización guiada**, **diagramas en texto (ASCII)** y descripciones precisas. Quiero que construyas los modelos mentales en tu cabeza, no que dependas de una foto.

### 2. Tu Laboratorio: Google Colab
Usaremos **Google Colab**. Es un entorno de programación profesional que vive en tu navegador. Si tienes internet, tienes tu laboratorio listo. En el Capítulo 3 te enseñaré a usarlo.

### 3. El Sistema de Navegación Visual
A lo largo del libro, no verás imágenes, pero sí encontrarás **bloques de texto resaltados** con iconos específicos. Estos son tus señales de tráfico:

*   **💡 La Bombilla (Ideas y Consejos):**
    Aquí encontrarás los **Objetivos del Capítulo**, la **Perspectiva del Programador** (cómo piensan los expertos) y **Consejos** prácticos para escribir mejor código. Cuando veas luz, detente: es información que ilumina el camino.

*   **⚠️ El Triángulo de Alerta (Peligros y Errores):**
    Esta es la zona de seguridad. Marca **Advertencias Críticas**, **Errores Comunes** y **Solución de Problemas**. Si te saltas estos bloques, es probable que tu código falle más adelante. Léelos con atención.

*   **📝 El Bloc de Notas (Contexto):**
    Información adicional, aclaraciones o matices importantes que no son urgentes, pero que te ayudarán a entender el contexto completo de lo que estás aprendiendo.

*   **🔍 La Lupa (Análisis Profundo):**
    Aparece cuando necesitamos detenernos a mirar "bajo el capó" de una tecnología o concepto teórico complejo. Es para los curiosos que quieren saber exactamente cómo funciona el engranaje.

### 4. La Metodología de Estudio
No intentes leer todo el libro en un fin de semana. La programación es una habilidad, como tocar la guitarra.
*   **Lee el concepto.**
*   **Escribe el código** (no copies y pegues; teclea).
*   **Rompe el código:** Cambia valores, borra líneas, mira qué pasa.
*   **Haz los laboratorios:** Son el examen real.

Si te atascas (y te atascarás), no te rindas. Lee el mensaje de error. Respira. Esa lucha es el aprendizaje ocurriendo en tiempo real.

---


# 📑 TABLA DE CONTENIDO

## MATERIA FRONTAL
*   **Dedicatoria**
*   **Agradecimientos**
*   **Acerca del Autor**
*   **Prefacio:** Por qué este libro es diferente
*   **Cómo leer este libro:** Reglas, herramientas y metodología

---

## 🧠 BLOQUE I: PENSAR COMO PROGRAMADOR (LA MENTALIDAD)

### **Capítulo 0: El Mundo Secreto de los Algoritmos**
*   **Introducción:** El Pensamiento Computacional No Es Solo para Programadores.
*   **Definiendo los Algoritmos:** ¿Qué es realmente? Analogías de recetas y direcciones.
*   **Pensamiento Algorítmico en Acción:** TikTok, Google Maps, IA de videojuegos y Netflix.
*   **La Anatomía de un Algoritmo:** El patrón universal Entrada → Proceso → Salida.
*   **Introducción al Pseudocódigo:** Tu primer lenguaje de programación agnóstico.
*   **Caso de Estudio:** Del problema real al pseudocódigo (Sistema de Descuentos).
*   **Laboratorios:** Identificación en vida real, pseudocódigo original y depuración mental.

### **Capítulo 1: Diagramas de Flujo — Visualiza la Lógica Antes de Codificar**
*   **Introducción:** Mapas para tu código.
*   **Símbolos Fundamentales:** Terminal, Proceso, Entrada/Salida, Decisión, Conector.
*   **Tu Primer Diagrama:** Calculadora de Propina.
*   **Bucles en Diagramas:** Representando la repetición y evitando bucles infinitos.
*   **Caso de Estudio Completo:** Sistema de Cajero Automático Simplificado.
*   **Errores Comunes:** Condiciones ambiguas y bucles sin salida.
*   **De Diagramas a Código:** El puente hacia Python.

---

## 🐍 BLOQUE II: EL LENGUAJE DE LA MÁQUINA (LA SINTAXIS)

### **Capítulo 2: Activando tu Superpoder: El Ritual del 'Hola Mundo'**
*   **Python:** El lenguaje que habla como humano.
*   **Perspectiva del Programador:** Los lenguajes como traductores universales.
*   **Tu Primer Programa:** `print()` y la anatomía del código.
*   **Conversando con Python:** La función `input()` y variables básicas.
*   **Trabajando con Números:** El problema de texto vs. números y la conversión con `int()`.
*   **El REPL:** Tu laboratorio de experimentos interactivo.

### **Capítulo 3: Tu Laboratorio en la Nube — Google Colab, Variables y el Lenguaje de los Datos**
*   **Configuración:** Creando tu cuenta y primer Notebook en Google Colab.
*   **Anatomía de un Notebook:** Celdas de código vs. celdas de texto.
*   **Variables:** Las cajas mágicas de la memoria y la asignación (`=`).
*   **El Lenguaje de los Tipos:** Enteros (`int`), Flotantes (`float`), Textos (`str`), Booleanos (`bool`).
*   **Conversión entre Tipos:** El arte de la transformación de datos.
*   **Laboratorios:** Calculadora de propinas, perfil de estudiante y conversor universal.

---

## ⚙️ BLOQUE III: CONSTRUYENDO LÓGICA (LAS HERRAMIENTAS)

### **Capítulo 4: El Cerebro Digital — Tomando Decisiones con Condicionales**
*   **Operadores de Comparación:** Haciendo preguntas binarias (`==`, `!=`, `>`, `<`).
*   **Operadores Lógicos:** Construyendo preguntas complejas (`and`, `or`, `not`).
*   **La Estructura IF:** El punto de bifurcación.
*   **Estructuras IF-ELSE y IF-ELIF-ELSE:** Planes B y múltiples caminos.
*   **Condicionales Anidadas:** Decisiones dentro de decisiones.
*   **Laboratorios:** Validador de contraseñas, calculadora de descuentos y sistema de admisión.

### **Capítulo 5: El Poder del Bucle Infinito (y Cómo Controlarlo)**
*   **El Patrón Fundamental:** La repetición con propósito.
*   **El Bucle FOR:** Tu iterador de confianza para colecciones y rangos.
*   **El Patrón del Acumulador:** Sumando y contando datos.
*   **El Bucle WHILE:** Iteración basada en condiciones dinámicas.
*   **Control Avanzado:** `break` (salida de emergencia) y `continue` (saltar iteración).
*   **Bucles Anidados:** Iteración dentro de iteración (tablas y combinaciones).

### **Capítulo 6: Cajas Mágicas y Estanterías Ordenadas — Listas, Tuplas y Diccionarios**
*   **Las Listas:** Tu inventario digital flexible (índices, `append`, `pop`, slicing).
*   **Las Tuplas:** Datos inmutables para seguridad y eficiencia.
*   **Los Diccionarios:** Organizando con etiquetas descriptivas (clave-valor).
*   **Estructuras Anidadas:** Listas de diccionarios y modelos de datos complejos.
*   **Laboratorios:** Gestor de playlist, traductor de coordenadas y base de datos de contactos.

### **Capítulo 7: Divide y Vencerás — Creando tus Propias Herramientas con Funciones**
*   **Concepto:** La magia de no repetirse (DRY).
*   **Anatomía de una Función:** `def`, parámetros y cuerpo.
*   **Parámetros y Argumentos:** Posicionales, por nombre y valores por defecto.
*   **El Return:** La salida de tus funciones y retornos múltiples.
*   **Alcance (Scope):** Variables locales vs. globales.
*   **Documentación:** Docstrings profesionales.
*   **Composición:** Construyendo sistemas complejos con bloques simples.

---

## 💼 BLOQUE IV: DE CÓDIGO A REALIDAD (LAS APLICACIONES)

### **Capítulo 8: Arquitectura de Soluciones — Pensar Antes de Programar**
*   **El Método de las Cuatro Fases:** Entender, Diseñar, Implementar, Validar.
*   **Fase 1 - Entender:** La técnica de los "Cinco Por Qué".
*   **Fase 2 - Diseñar:** Identificando componentes, estructuras y flujos sin código.
*   **Fase 3 - Implementar:** Desarrollo incremental y refactoring.
*   **Fase 4 - Validar:** Estrategia de casos de prueba y "romper tu código".
*   **Laboratorios:** Planificación de sistemas y refactoring de código existente.

### **Capítulo 9: El Mundo Real en tu Código — Archivos, CSV y Datos Externos**
*   **Anatomía de un Archivo:** Modos de operación (`r`, `w`, `a`).
*   **Escritura y Lectura:** El gestor de contexto `with`.
*   **Archivos CSV:** El formato universal (`csv.reader`, `csv.writer`, `DictReader`).
*   **Manejo de Errores:** Programación defensiva con `try-except` y `os.path`.
*   **Proyecto Integrador:** Sistema de Inventario Persistente (Niveles 1, 2 y 3).

### **Capítulo 10: Ver para Creer — Visualización de Datos para Contar Historias**
*   **El Poder de lo Visual:** Por qué importa la visualización.
*   **Matplotlib:** Tu aliada gráfica.
*   **Tipos de Gráficos:** Líneas (tiempo), Barras (comparación), Dispersión (relación), Circular (proporción).
*   **Personalización:** Títulos, etiquetas, colores y leyendas.
*   **Subplots:** Múltiples historias en un panel.
*   **Integración:** De CSV a insights visuales.

### **Capítulo 11: El Código del Héroe — Programación Ética y Responsable**
*   **Privacidad:** Consentimiento informado, minimización y anonimización.
*   **Sesgo Algorítmico:** La ilusión de objetividad y tipos de sesgo (muestreo, confirmación, proxy).
*   **Transparencia:** Explicabilidad y cajas negras.
*   **Accesibilidad:** Diseño inclusivo para todos los usuarios.
*   **Sostenibilidad:** Código legible es código mantenible.
*   **Checklist:** El manual del programador ético.

### **Capítulo 12: Proyecto Final — Tu Panel de Control Personalizado**
*   **Fase 1 - Definición:** Eligiendo un proyecto viable y creando especificaciones.
*   **Fase 2 - Arquitectura:** Descomposición en componentes y diseño de funciones.
*   **Fase 3 - Implementación Incremental:**
    *   Nivel 1: Producto Mínimo Viable (MVP).
    *   Nivel 2: Sistema Completo y Robusto.
    *   Nivel 3: Características Avanzadas (Alertas, Optimización).
*   **Fase 4 - Debugging Avanzado:** El método de las cinco preguntas.
*   **Cierre:** El umbral de lo profesional y próximos pasos.

---

---

*¿Estás listo para dejar de ser un usuario y empezar a ser un creador?*

*Pasa la página. Empecemos.*