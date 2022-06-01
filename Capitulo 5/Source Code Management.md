Para nuestro proyecto se decidió aplicar el control de sistema de Git en Github para poder almacenar nuestros repositorios y llevar el control respectivo de nuestras versiones y cambios dentro de nuestra plataforma.

La primera rama master que solo incluye releases o versiones mayores, la segunda develop en el cual se encontrarán próximas versiones en progreso y finalmente múltiples ramas de features, por ejemplo, “Feature/landing”. De esta manera podremos separar de manera más organizada las versiones de nuestros proyectos.

Para el raleases, se optó por Semantic Versioning 2.0.0, el cual indica cada uno de los números en la versión correspondientemente. En la que se emplea la etiqueta VMAHOR.MINOR. PATCH. 

### Donde: 

- vMAHOR: Es actualizado según el impacto del cambio ya este grande o incompatible con su versión anterior
- MINOR:  Son cambios menores, el cual se le agrega funcionalidades compatibles con la versión anterior
- PATCH: Refiere a los parches, el cual se refiere a los pequeños cambios que se realizan dentro de la aplicación.

    Por ejemplo, v1.3.2, esta indica que es la primera versión con 3 nuevas funcionalidades y con 2 parches de corrección de errores.


### Por último, la sintaxis para nuestro conventional commints:

    <type> [optional scope]: <description>

    [optional body]

    [optional footer(s)]

### Donde:

- Scope: Son datos que nos ayuda a indicar sobre que se está haciendo cambio.

- Body: Una descripción más larga, la cual puede incluir contextos sobre cómo se hizo el cambio y los detalles que se considere necesario. 

- Footer: Esta parte indicada a indicar el o los que issues estas cerrando o indicar que este cambio rompe la compatibilidad de software respecto a versiones anteriores.


![imagen](/Capitulo%205/images/cincounodos.png)
