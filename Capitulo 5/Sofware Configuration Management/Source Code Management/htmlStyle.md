# HTML Style Rules

### HTML Validity: 

El uso de HTML válido es un atributo de calidad de referencia medible

 que contribuye a conocer los requisitos y las restricciones técnicas 
 
 y que garantiza el uso adecuado de HTML

 Ejemplo: 

 NO RECOMENDADO: 

< title >Prueba</ title >< article >Esto es solo una prueba. 

 RECOMENDADO: 

< !DOCTYPE html > < meta charset = "utf-8" > < title> Prueba < /

title> < article> Esto es solo una prueba. </ artículo>

### Semantics: 

El uso de HTML de acuerdo con su propósito es importante por razones

 de accesibilidad, reutilización y eficiencia del código.

 Ejemplos: 

 NO RECOMENDADO: 

 < div onclick = " goToRecommendations (); " > Todas las recomendaciones </ div>

RECOMENDADO: 

< a href = "recomendaciones/" > Todas las recomendaciones </ a>

### Multimedia Fallback: 

Para multimedia, como imágenes, videos, objetos animados a través 

canvas de , asegúrese de ofrecer un acceso alternativo. Para imágenes,

 eso significa el uso de texto alternativo significativo ( alt) y 
 
 para transcripciones y subtítulos de video y audio, si están 
 
 disponibles.

 Ejemplo: 

 NO RECOMENDADO:

 < img src = "hoja de cálculo.png" >

RECOMENDADO: 

< img src = "hoja de cálculo.png" alt = "Captura de pantalla de la 

hoja de cálculo". >

### Entities References: 

No es necesario utilizar referencias a entidades como & mdash;, & 

rdquo;o &#x263a ;, suponiendo que se utilice la misma codificación 

(UTF-8) para archivos y editores,las únicas excepciones se aplican a 

los caracteres con un significado especial en HTML (como < y &), así

 como a los caracteres de control o "invisibles"

 Ejemplo:

 NO RECOMENDADO: 

 El símbolo de moneda del euro es “& eur;”.

 RECOMENDADO: 

 El símbolo de moneda del euro es “—.

 ### type Atributes: 

 Omita typeatributos para hojas de estilo y scripts.

No use typeatributos para hojas de estilo (a menos que no use CSS) y 

scripts (a menos que no use JavaScript).

Ejemplo: 

NO RECOMENDADO: 

< link rel = "hoja de estilo" href = "https://www.google.com/css/maia.css" type = "text/css" >

RECOMENDADO: 

< link rel="stylesheet" href="https://www.google.com/css/maia.css">

### id Atributes: 

idEvite los atributos innecesarios .

Prefiera classlos atributos para el estilo y datalos atributos para 

las secuencias de comandos.

Ejemplo: 

NO RECOMENDADO: 

`window.userProfile` se resolverá para hacer referencia al nodo 

< div> --> < div id = "userProfile" >< /div>

RECOMENDADO: 

el atributo `id` es obligatorio y su valor incluye un guión -->

 < div aria-describedby = "perfil-de-usuario" > 

… < div id = "perfil-de-usuario" >< /div> 

… < /div>
 

