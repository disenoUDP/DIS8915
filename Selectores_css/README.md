# DIS8915_selectores_css

Guía para entender cómo se pueden seleccionar elementos.

En CSS, puedes seleccionar elementos por medio del mismo elemento, clases e identificadores utilizando diferentes selectores. Aquí tienes una breve descripción de cada uno:

1. **Elementos**: Los selectores de elementos se utilizan para seleccionar todos los elementos de un tipo específico en un documento HTML. Por ejemplo, si deseas aplicar un estilo a todos los elementos `<p>` (párrafos) en tu página, puedes utilizar el siguiente selector:

   ```css
   p {
     /* Estilos para párrafos */
   }
   ```

2. **Clases**: Las clases se utilizan para aplicar estilos a elementos HTML específicos que tienen una clase determinada. Las clases se usan para una selección menos global que los elementos.  
   Para seleccionar elementos por clase, utiliza un punto (`.`) seguido del nombre de la clase. Por ejemplo, si deseas aplicar un estilo a todos los elementos con la clase `titulo` o `parrafo`, puedes usar el siguiente selector:

   ```html
   <!-- En html se agrega la clase dentro de la primera etiqueta <h1> y se escribe class="nombre-clase" con doble comillas y si el nombre de la clase tiene más de una palabra se una un guión-->
   <body>
     <h1 class="titulo">Título de la Página</h1>
     <p class="parrafo">Este es un párrafo de ejemplo.</p>
     <p class="parrafo">Otro párrafo con la misma clase.</p>
   </body>
   ```

   ```css
   .titulo {
        /* Estilos para elementos con la clase 'titulo' */
        color: #007bff; /* Color azul */
        font-size: 24px; /* Tamaño de fuente */
        font-weight: bold; /* Negrita */
   }

   .parrafo {
        /* Estilos para elementos con la clase 'parrafo' */
        color: #333; /* Color gris oscuro */
        font-size: 16px; /* Tamaño de fuente */
        line-height: 1.5; /* Altura de línea */
   }
   ```

3. **ID**: Los identificadores (IDs) se utilizan para aplicar estilos a un elemento HTML específico que tiene un identificador único. Para seleccionar un elemento por su ID, utiliza un símbolo de almohadilla (`#`) seguido del nombre del ID. Por ejemplo, si deseas aplicar un estilo a un elemento con el ID `encabezado`, puedes usar el siguiente selector:

   ```html
   <body>
     <h1 id="titulo">Título de la Página</h1>
     <p id="parrafo1">Este es un párrafo de ejemplo.</p>
     <p id="parrafo2">Otro párrafo con el mismo ID.</p>
   </body>
   ```

   ```css
   /* Estilos para el ID 'titulo' */
   #titulo {
        color: #007bff; /* Color azul */
        font-size: 24px; /* Tamaño de fuente */
        font-weight: bold; /* Negrita */
   }

   /* Estilos para el ID 'parrafo1' */
   #parrafo1 {
        color: #333; /* Color gris oscuro */
        font-size: 16px; /* Tamaño de fuente */
        line-height: 1.5; /* Altura de línea */
   }

   /* Estilos para el ID 'parrafo2' */
   #parrafo2 {
        font-style: italic; /* Cursiva */
   }
   ```

Estos son algunos de los selectores más comunes en CSS. Puedes combinar selectores para seleccionar elementos de manera más específica y aplicar estilos de manera más granular según tus necesidades.
