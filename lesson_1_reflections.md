# lección 1

*   none

*   none

*   _¿ Cuáles son los pros y contras que usted le ve a hacer los commit
manualmente diferente de la manera automática como lo hace por ejemplo
google-docs?_

Ventajas                                | Desventajas
-----------------------------------     | ---------------------------------
Permite realizar mejores búsquedas      | Pérdida de datos en algunos casos
Permite hacerlo de manera personalizada  | Mayor responsabilidad
Permite opciones como los mensajes       | Mayor curva de Aprendizaje

*   _¿ Por qué usted cree que algunos controles de versiones como git permiten
guardar multiples archivos en un commut  mientras que otros como google-docs
trata cada archivo por separado ?_

Git es un control de versiones más orientado  a los proyectos y puesto que entre
todos ellos hay atributos en común y  de la mayoría de veces cuando de modifica
un archivo es obligatorio editar algún otro para que este funcione.

Además esto permite separar una versiones del proyecto  creo ques esto es
útil cuando necesitas presentar una parte del proyecto pero seguir
trabajando en la siguiente entrega.

Creo que lo resumiría en que es muy útil tener una vista completa del proyecto
en cada commit.

*   _¿ Cómo puede utilizar los comandos "git log" y "git diff" para ver la
historia de los archivos?_

git log se usa para buscar los commits que deseamos comparar y git diff realiza
la búsqueda de las diferencias entre estos y si repetimos esto varias veces
podemos ver como va avanzando el proyecto de commit en commit.

*   _¿ Cómo podría usar el control de versiones para hacer más seguros los
cambios que podrían crear un error ?_

Situarlos en un solo commit para que estos cambios sean fáciles de encontrar ,
también colocarle un comentario que exprese lo que se realiza en el commit
para estar seguros de que es este el que produce el error.
