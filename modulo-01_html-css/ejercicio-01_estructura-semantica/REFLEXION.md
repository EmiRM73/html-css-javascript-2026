# REFLEXION — Ejercicio 1.1: Estructura Semántica HTML

> **Instrucciones:** Completá este archivo DESPUÉS de terminar tu solución. Escribí con tus propias palabras. Respuestas copiadas de internet o generadas por IA sin elaboración propia no son válidas.
>
> Tiempo esperado para completar esta reflexión: 20–30 minutos.

---

## Sección 1 — Explicación de mi solución

*Describí en 150–250 palabras qué hace tu archivo HTML y cuáles fueron las decisiones de estructura que tomaste. No copies el código, explicá el razonamiento.*

> ✏️ **Tu respuesta aquí:**
>
> mi codigo html hace una pagina muy basica la cual cumple con la estructura de html basica para que el navegador la lea de forma correcta, evitando el uso de "div" y usando las etiquetas correspondientes, a su vez  se utiliza las imagenes con su correspondiente "alt" para que el programador en caso de que no tenga la imagen, sepa de que trate para colocarla y por ultimo en cuanto a las decisiones de estructura que tome, segui un "camino" basico donde esta un titulo y la informacion correspondiente, en un caso con una imagen que acompaña el texto.

---

## Sección 2 — Preguntas conceptuales

Respondé cada pregunta. Las respuestas deben ser tuyas. Podés investigar, pero explicá con tus palabras.

### 2.1 — ¿Cuál es la diferencia entre `<section>` y `<article>`? ¿Cuándo usarías cada uno?

> ✏️ **Tu respuesta:*segun lo que entendi, section sirve para agrupar las partes de un tema en la pagina y article es independiente de la pagina sino del tema que trata*

---

### 2.2 — ¿Por qué es importante el atributo `datetime` en la etiqueta `<time>`? ¿Quién lo usa?

> ✏️ **Tu respuesta:*se usa el data time para que lo traduzca a la maquina, esto lo utilizan diferentes navegadores como google*

---

### 2.3 — Tu página tiene `<header>` en dos lugares: uno para la página y uno dentro del `<article>`. ¿Eso es válido? ¿Por qué?

> ✏️ **Tu respuesta:*Es valido porque el header no es exclusivo de la pagina sino, es la cabecera del contenedor mas cercano  porque da contexto de los contenedores no de la pagina*

---

### 2.4 — Un motor de búsqueda como Google lee tu HTML. ¿Qué ventaja le da usar etiquetas semánticas versus usar solo `<div>` con clases?

> ✏️ **Tu respuesta:*es mejor usar etiquetas semanticas para que los navegadores analisen tu html y vea que cumple con un patron que hace que la recomiende mas, por ejemplo si usas un popurri de h1 tu pagina es menos recomendada porque google detecta que abuzaste de los h1 para recomendar mas tu pagina. ya que los h1 son los que lee google para posicionarte mejor y en tu sector. en resumen las etiquetas semanticas funcionan como un mapa para el navegador *

---

### 2.5 — Encontrá **un error semántico** en el siguiente fragmento y explicá cómo lo corregirías:

```html
<div class="navigation">
  <div class="nav-item"><a href="/home">Inicio</a></div>
  <div class="nav-item"><a href="/about">Nosotros</a></div>
</div>

<div class="main-content">
  <div class="post-title">Mi primer artículo</div>
  <div class="post-body">
    <p>Contenido del artículo...</p>
  </div>
</div>
```

> ✏️ **Tu respuesta:**

--- es un conjunto de div sin sentido, la navegacion deberia ser un nav y los link estar en una lista ordenada  de ul y li. despues el contenido deberia estar en la etiqueta main y el titulo en un h1  y ya de por si el articulo en una etiqueta article

## Sección 3 — Decisiones técnicas

### 3.1 — ¿Qué etiqueta usaste para el logo y por qué? ¿Hay alternativas?

> ✏️ **Tu respuesta:*para el logo use img con su scr para poner la direccion de la imagen y un alt con la explicacion de la imagen y no conozco otra alternativa*

---

### 3.2 — ¿Elegiste `<ul>` u `<ol>` para tu lista? ¿Por qué esa y no la otra?

> ✏️ **Tu respuesta:* use ambas, con ol marca una lista ordenada con numeros y ul para una lista ordenada con puntos sin numeros*

---

### 3.3 — Si alguien accede a tu página solo con un lector de pantalla (sin ver el HTML), ¿podría navegar y entender el contenido? ¿Qué cambiarías para mejorar la experiencia?

> ✏️ **Tu respuesta:*creo yo que podria entender perfectamente mi pagina y el contenido aunque para mejorar la experiecnia mejoraria la interfaz con css y que cuando pasas el mouse por arriba de las imagenes salga un cartelito q las describa pero no se como hacerlo*

---

## Sección 4 — Declaración de uso de IA

Marcá con una `x` lo que corresponda:

```
[ ] Resolví el ejercicio completamente sin ayuda de IA
[x] Usé IA para entender algún concepto, pero escribí el código yo
[ ] Usé IA para generar un borrador que luego modifiqué y entendí
[ ] Usé IA extensamente y completé la reflexión para entender lo que hice
```

*Si usaste IA, describí brevemente cómo:*

> ✏️ **Tu respuesta (opcional si no usaste IA):**
use la ia para entender algunas etiquetas que no conocia y para saber como cambiar el tamaño de las imagenes desde html sin falta de css como estaba acostumbrado.
---

## Sección 5 — Autoevaluación

En una escala del 1 al 5, ¿cuánto entendés ahora el concepto de HTML semántico?

```
[ ] 1 — Muy poco, necesito repasar
[ ] 2 — Entiendo lo básico
[x] 3 — Lo entiendo bien
[ ] 4 — Lo entiendo bien y puedo explicárselo a otro
[ ] 5 — Podría dar una clase sobre esto
```

*¿Qué parte te resultó más difícil?*

> ✏️ **Tu respuesta:* la parte que me resulto mas dificil fue el aprender las nuevas etiquetas y para que servia cada una, ya que venia de haber visto html en la materia electiva TyGweb donde solo usabamos div con clases o id, y aprender cuales y cuando usar etiquetas nuevas se me hizo lo mas complejo*
