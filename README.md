# Diccionario Interactivo de Acordes, Escalas y Melodías

## Descripción breve

Una herramienta musical interactiva para **explorar acordes y escalas, construir progresiones, crear melodías y exportar resultados en formato MIDI**. El proyecto nació como un diccionario de acordes, pero fue creciendo hasta transformarse en un espacio de experimentación musical donde las notas no solamente se consultan: también se pueden escuchar, ordenar, combinar, reproducir de forma aleatoria y convertir en material utilizable en programas como Ableton Live.

---

## ¿Cómo nació este proyecto?

La idea inicial era crear un diccionario de acordes sencillo y visual que permitiera entender mejor cómo se forman los acordes y qué notas contiene cada uno. El objetivo no era hacer una lista estática como muchas de las que existen en internet, sino una herramienta que ayudara a **aprender música probando, escuchando y modificando directamente las notas**.

Mientras el proyecto avanzaba, comenzó a aparecer una necesidad más grande: no bastaba con ver un acorde aislado. También era necesario poder explorar escalas, comparar sus notas, construir progresiones y utilizar ese material para crear música real.

A partir de ahí, el diccionario comenzó a transformarse en una herramienta mucho más amplia.

---

## Evolución del proyecto

### 1. Diccionario de acordes

La primera etapa consistió en organizar acordes a partir de una nota raíz. La persona puede seleccionar una nota —por ejemplo, C— y acceder a distintas variantes como:

- C mayor
- C menor
- C7
- Cmaj7
- Acordes aumentados
- Acordes disminuidos
- Otras extensiones y variaciones

La intención fue que la relación entre la raíz, la tercera, la quinta y las demás notas pudiera verse y escucharse con claridad.

### 2. Incorporación de escalas

Después se agregó la posibilidad de trabajar con escalas, ya que los acordes no existen de manera aislada: están relacionados con grupos de notas, tonalidades, modos y diferentes sistemas musicales.

El proyecto permite explorar escalas completas y también utilizar solamente algunas de sus notas. Esto sirve tanto para estudiar teoría musical como para crear melodías con un carácter determinado.

### 3. Constructor de progresiones

El siguiente paso fue permitir que varios acordes o escalas pudieran colocarse en una secuencia. De esta forma, la herramienta dejó de ser solamente un diccionario y comenzó a funcionar también como un **constructor musical**.

La persona puede experimentar con diferentes combinaciones, escuchar el resultado y modificar el orden de los elementos hasta encontrar una progresión interesante.

### 4. Reproducción de notas y melodías

El proyecto incorporó reproducción de audio para poder escuchar acordes, escalas y secuencias directamente desde la aplicación.

Esto permite comprobar inmediatamente cómo suena una idea sin tener que copiar todas las notas manualmente en otro programa.

### 5. Exportación MIDI

Una de las funciones más importantes fue la posibilidad de descargar las secuencias creadas como archivos `.mid`.

Gracias a esto, una melodía o progresión creada dentro de la herramienta puede abrirse posteriormente en:

- Ableton Live
- FL Studio
- Logic Pro
- Reaper
- Bitwig
- Otros secuenciadores y estaciones de trabajo de audio

El proyecto funciona así como un puente entre el aprendizaje de teoría musical y la producción musical real.

### 6. Reproducción aleatoria

También se agregó un sistema de reproducción aleatoria. En lugar de repetir siempre la misma secuencia, la herramienta puede elegir notas y generar variaciones.

Esta función permite utilizar el diccionario como una pequeña herramienta de composición generativa.

### 7. Probabilidad de aparición

Cada nota puede tener un porcentaje de probabilidad de aparecer durante la reproducción.

Por ejemplo:

- Una nota con 100 % aparecerá siempre.
- Una nota con 50 % aparecerá aproximadamente la mitad de las veces.
- Una nota con 10 % aparecerá solamente de manera ocasional.

Esto ayuda a crear melodías que conservan una estructura general, pero que cambian cada vez que se reproducen.

### 8. Silencios

La reproducción aleatoria también puede incluir silencios.

Los silencios son importantes porque evitan que todas las posiciones de una secuencia estén ocupadas por notas y permiten crear ritmo, respiración y contraste.

### 9. Uso parcial de una escala

No es obligatorio utilizar todas las notas de una escala. Se puede seleccionar solamente un grupo específico de notas y construir una secuencia a partir de ellas.

Esto permite controlar mejor el resultado y evitar que el sistema aleatorio utilice notas que no interesan para una composición determinada.

### 10. Orden y prioridad de las notas

Una de las ideas de desarrollo es permitir que las notas de una escala tengan funciones o prioridades diferentes.

Por ejemplo, se podría definir:

- Qué nota debe aparecer primero.
- Qué nota puede aparecer en segundo lugar.
- Qué notas tienen mayor o menor probabilidad.
- Qué grados de la escala funcionan como puntos de reposo.
- Qué notas deben utilizarse solamente como transición.
- Qué nota debe cerrar una secuencia.

Esto permitiría generar melodías aleatorias que no fueran completamente caóticas, sino que respetaran una lógica musical definida por la persona.

### 11. Importación de archivos MIDI

La exportación MIDI ya forma parte central del proyecto. La importación de archivos MIDI es una función proyectada para una etapa posterior.

La idea es que una persona pueda cargar un archivo MIDI, visualizar sus notas dentro de la herramienta, analizarlo, modificarlo y volver a exportarlo.

---

## Funciones actuales

- Exploración de acordes por nota raíz.
- Visualización de las notas que forman cada acorde.
- Exploración de escalas.
- Selección parcial de notas dentro de una escala.
- Construcción de secuencias y progresiones.
- Reproducción de acordes, escalas y melodías.
- Generación aleatoria de notas.
- Control de probabilidad de aparición.
- Inclusión de silencios.
- Creación de variaciones melódicas.
- Exportación de las secuencias como archivos MIDI.
- Uso de los archivos exportados en programas de producción musical.

> Algunas funciones pueden encontrarse todavía en desarrollo o perfeccionamiento.

---

## Funciones previstas

- Importación y lectura de archivos MIDI.
- Edición visual de MIDI dentro de la aplicación.
- Prioridad de notas según su grado dentro de una escala.
- Reglas para definir la primera y la última nota.
- Control independiente de probabilidad para cada grado.
- Generación de melodías con dirección ascendente o descendente.
- Patrones rítmicos más avanzados.
- Guardado de progresiones y melodías favoritas.
- Compartir configuraciones mediante archivos o enlaces.
- Más opciones de duración, velocidad y articulación.
- Análisis de las notas de una melodía cargada.

---

## Filosofía del proyecto

Este proyecto busca unir tres cosas que normalmente aparecen separadas:

1. **Teoría musical**, para comprender acordes, escalas, intervalos y grados.
2. **Experimentación**, para escuchar inmediatamente lo que ocurre al cambiar una nota.
3. **Producción musical**, para exportar el resultado y continuarlo en un DAW.

No pretende ser solamente una enciclopedia musical. La intención es que funcione como una herramienta para aprender haciendo, encontrar combinaciones inesperadas y transformar una idea teórica en una melodía real.

---

## ¿A quién puede servirle?

- Personas que están comenzando a estudiar teoría musical.
- Productores de música electrónica.
- Músicos que buscan nuevas progresiones.
- Personas que quieren experimentar con escalas poco comunes.
- Usuarios de Ableton Live y otros DAW.
- Compositores interesados en sistemas generativos.
- Personas que aprenden mejor escuchando y modificando que leyendo definiciones.

---

## Estado del proyecto

El proyecto se encuentra en desarrollo activo. Algunas funciones ya están operativas y otras forman parte de la hoja de ruta.

La intención es seguir mejorando la interfaz, ampliar el diccionario, agregar herramientas de composición y convertirlo progresivamente en un sistema completo de exploración musical.

---

## Descripción para la sección “About” de GitHub

Diccionario musical interactivo para explorar acordes y escalas, construir progresiones, generar melodías con probabilidad y silencios, reproducirlas y exportarlas como archivos MIDI para Ableton Live y otros DAW.

---

## Párrafo de presentación

Este proyecto comenzó como un diccionario visual de acordes pensado para entender de manera sencilla qué notas forman cada acorde. Con el tiempo evolucionó hasta convertirse en una herramienta interactiva de teoría, composición y experimentación musical. Actualmente permite explorar acordes y escalas, seleccionar notas, construir progresiones, reproducir melodías, generar variaciones aleatorias, controlar la probabilidad de aparición de cada elemento, incluir silencios y exportar los resultados como archivos MIDI para continuar trabajándolos en Ableton Live u otros programas de producción. La meta es que la aplicación no solamente muestre información musical, sino que permita jugar con ella, escucharla y transformarla en ideas musicales reales.

---

## Capturas de pantalla

Puedes agregar aquí imágenes del proyecto:

```markdown
![Pantalla principal](ruta/de/la/imagen.png)
![Constructor de progresiones](ruta/de/la/imagen2.png)
![Generador de melodías](ruta/de/la/imagen3.png)
```

---

## Demo

La versión pública del proyecto estará disponible en:

https://fersloc.github.io/diccionario-musical/

> El enlace funcionará después de activar GitHub Pages desde `Settings → Pages`.

---

## Dedicatoria

Hecho con mucho amor para **Gigi Marrazzo**, por su cariño, compañía e inspiración. Parte de la energía que hizo crecer este proyecto también viene de ella. 💛

---

## Autoría

Proyecto creado por **Fersloc** como una herramienta independiente para el aprendizaje, la exploración y la composición musical.

