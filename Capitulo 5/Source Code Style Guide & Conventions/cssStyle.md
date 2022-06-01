 # CSS Style Rules

### Class Naming

Al usar nombres funcionales o genéricos reduce la probabilidad de 

cambios innecesarios en el documento o la plantilla.

Ejemplo: 

NO RECOMENDADO:   
yee-1801{}

boton-verde{}.claro{}


RECOMENDADO:

galeria{} 

iniciar sesión{}

video{}


### Class Name Style

Se utilizan nombres de clase que sean lo más cortos posible pero tan 

largos sean necesarios.

Ejemplos:

NO RECOMENDADO: 

navegación{} . clt{}

RECOMENDADO: 

navegación{}.cliente{}


### Class Name Delimiters

Separar las palabras en los nombres de las clases con un guion 

Ejemplos: 

NO RECOMENDADO: 

error_estado{}

demoinage{}

RECOMENDADO: 

video-id{}

ads-sample{}

### Type Selector: 

Evitar calificar nombres de clase con selectores de tipo

Ejemplo: 

NO RECOMENDADO: 

ul.example{}

div-error{}

RECOMENDADO: 

.example{}

.error{}

### ID SELECTOR:

Los atributos ID son únicos en toda la página, lo que es dificil 

garantizar cuando una página tiene muchos componentes en los que 

trabajaron muchos ingenieros diferentes. 

Ejemplo: 

NO RECOMENDADO: 

#example {}

RECOMENDADO: 

.example{}

### Declarations importans

Evitar el uso de "!important" delcaraciones. Estas declaraciones 

rompen la cascada natural de CSS y dificulta el razonamiento y la

 composicion de estilos.

Ejemplo: 

NO RECOMENDADO: 

.example{

font - weight: bold !important;

}

RECOMENDADO:

.example{

font-weight: bold;  

}

### Declarations Order

Se recomienda ordenar de manera alfabeticamente. Reordenar las 

declaraciones constantemente dentro del proyecto. De esta forma, se 

hace más sencilla de aprender, recordar y mantener el código.

### Declaraciones Stops

Finalizar cada declaración con un punto y coma por motivos de 

coherencia.

Ejemplo: 

NO RECOMENDADO: 

.test{

displaay: block;

height : 100 px

}

RECOMENDADO: 

.test{

displaay: block;

height : 100 px;

}

### CSS Quotation Marks

Utilice comillas simples ( ' ' ) en lugar de dobles ( ) para los

selectores de atributos y valores de propiedad ""

No utilice comillas en los valores de URI ( url()).

Ejemplo:

NO RECOMENDADO: 

@import url ( "https://www.google.com/css/maia.css" ); 

html { familia de 

  fuentes : "open sans " , arial , sans - serif ; }

RECOMENDADO: 

@importar url ( https : //www.google.com/css/maia.css); 

html { familia de 

  fuentes : ' open sans' , arial , sans - serif ; }

 ### Section Coments

Agrupe secciones por un comentario de sección (opcional).

Si es posible, agrupe las secciones de la hoja de estilo usando 

comentarios. Secciones separadas con nuevas líneas.

Ejemplos: 

Encabezado : . adw - encabezado {}

Pie de página: . adw - pie de página {}

Galería: . adw - galería {} 

