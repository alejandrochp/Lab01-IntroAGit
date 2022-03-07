# Investigación GIT 
## ¿Qué es?

Git es el sistema de control de versiones moderno más utilizando en el mundo. Es un proyecto de código abierto con mantenimiento activo desarrollado originalmente por Linus Torvalds, el famoso creador del kernel de Linux. Existe un gran número de proyectos de software que dependenden de Git para el control de versiones, incluidos proyectos comerciales y de código abierto. 

Git es un ejemplo de DVCS (sistema de control de versiones distribuido por sus siglas en inglés). En lugar de tener un único espacio para todo el historial de versiones, como suele suceder en otros sistemas de control, Git almacena la copia de trabajo del código de cada desarrollador para tener un historial completo ordenado de todos los cambios. 

### Rendimiento

Las características básicas de git son bastante sólidas comparadas con otras alternativas. La confirmación de nuevos cambios, la estructura de ramificación, fusión de cambios y comparación de versiones anteriores, hacen que el funcionamiento de Git sea el adecuado para los distintos proyectos de software que se desarrollan. A diferencia de algunos programas de software de control de versiones, Git no se deja engañar por los nombres de los archivos a la hora de determinar cuál debería ser el almacenamiento y el historial de versiones del árbol de archivos; en lugar de ello, se centra en el contenido del propio archivo. 

### Seguridad

Git se ha diseñado con la principal prioridad de conservar la integridad del código fuente gestionado. El contenido de los arvhicos y las relaciones entre estos con los directorios, versiones, etiquetas, etc. Están protegidos por un algoritmo de hash criptográficamente seguro llamado **SHA1**. De este modo se protege el código y el historial de cambios frente a las modificaciones accidentales y maliciosas, garanzitando un historial completamente trazable. 

Algunos otros sistemas de control de versiones carecen de protección contra las modificaciones ocultas realizadas con posterioridad, algo que puede suponer una grave vulnerabilidad de seguridad de la información para cualquier organización que se base en el desarrollo de software.

### Flexibilidad

Uno de los objetivos clave de Git en cuanto a diseño es la flexibilidad. Esto lo resalta en varios aspectos como: 
- Su capacidad para varios tipos de flujo de trabajo de desarrollo no lineal
- Eficiencia en proyecto grandes como pequeños
- Compatibilidad con numerosos sistemas y protocolos

Git se ha ideado para posibilitar la ramificación y etiquetado como procesos de primera importancia. No toods los sistemas de control de versiones ofrecen este nivel de seguimiento. 

## Diferentcia entre git y GitHub

GitHub facilita la colaboración con git. Es una plataforma que puede mantener repositorios de código en almacenamiento basado en la nube para que varios desarrolladores puedan trabajar en un solo proyecto y ver las ediciones de cada uno en tiempo real. 

También incluye funcionas de organización y gestión de proyectos. Puede asignar tareas a individuos o grupos, establecer permisos y roles para los colaboradores y usar la moderación de comentarios para mantener a todos en la tarea. 

Los repositorioas de GitHub están disponibles públicamente con lo que los desarrolladores de todo el mundo pueden interactuar y contribuir al código de los demás para modificarlo o mejorarlo, lo que se conoce como **codificación social**. 

Hay tres principales acciones que se pueden realizar cuando se trata de interactuar con el código en GitHub: 
1. **Bifurcación**: El proceso de copiar el código de otra persona del repositorio para modificarlo
2. **Pull**: Cuando haya terminado de hacer cambios en el código de otra persona, puede compartirlos con el propietario original a través de una *solicitud pull* 
3. **Fusión**: Los propietarios pueden añadir nuevos cambios a sus proyectos a través de una fusión, y dar crédito a los contribuyentes que los han sugerido.

Especialmente para los nuevos desarrolladores que están tratando de construir sus currículums, esta puede ser una gran oportunidad para ganar algo de experiencia. GitHub le permite compartir proyectos en su perfil y mantiene una línea de tiempo de todos aquellos en los que has contribuido.

Se pueden identificar principales diferencias entre git y GitHub:

- git es un software de VCS local que permite a los desarrolladores guardar instantáneas de sus proyectos a lo largo del tiempo. Generalmente es mejor para uso individual.
- GitHub es una plataforma basada en la web que incorpora las características de control de versiones de git para que puedan ser utilizadas de forma colaborativa. También incluye características de gestión de proyectos y equipos, así como oportunidades para la creación de redes y la codificación social.

## ¿Cómo crear un repositorio en GitHub?

1. Se debe hacer es crear una cuenta de usuario en https://github.com/
2. Configurar las variables globales de git en local, como nombre de usuario.
  - $ git config --global user.name "tu_usuario"
  - $ git config --global user.email @email.com
3. Desde la barra de navegación hacer click en enlace “New repository”

![image](https://user-images.githubusercontent.com/99599847/156967195-93b07754-4367-4fdf-9bc9-0bbeff9f9668.png)

4. Se abrirá una venta para especificar los detalles del proyecto. Es recomendable incluir el archivo readme.md desde un principio para colocar allí las instruciones de instalación y/o uso de la información allí contenida. También se puede colocar información de licencia y sugerencias adicionales. 

![image](https://user-images.githubusercontent.com/99599847/156967347-c27b5317-5eb8-4af3-ba8c-0af1407a1ff3.png)



