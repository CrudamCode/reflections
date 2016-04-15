# lección 2

*   _¿Qué sucede cuando se inicializa el repositorio?,¿Porque se necesita hacer
esto ?_

Se crean algunos archivos para contener los datos que nos permiten hacer uso de
git, es necesario porque es la manera de indicar que el directorio de va ha
hacer uso de git.

*   _¿Como es el  "staging area" diferente a el "working directory" y el
"repository" ?,¿Qué posibilidades cree que esto le ofrece?_

Es un área de intercambio en la cual después de  añadir un  archivo no se pueden
hacer modificaciones a esté y no está guardado en el historial como estaría
después de hacer un commit.
permite tener más control sobre los commits permitiendo mantener en el
directorio varios archivos modificados y ir haciendo commits de archivos por
lógica u otras diferentes formas de organizar sus commits.

*   _¿Cómo puedes asegurarte con "staging area"  de hace un commit por cada
cambio de lógica?_

puedo puedo hacer varios commits después de editar en varios archivos y hacer
commit por cada cambio de lógica añadiendo solo los que presenten el mismo
cambio de logica.

*   _¿Cuales pueden ser las situaciones en que sea útil utilizar las branch?,
¿Cómo podrían ayudarte las branch?_

En las que necesitemos mantener una version de el codigo estable, en las que
necesitemos realizar pruebas con el código, crear nuevas características o
arreglar un bug.
ayudan a mantener un orden, permiten trabajar por varios caminos al tiempo.

*   _¿Cómo pueden los diagramas ayudarte a visualizar la estructura de las
ramas?_

me permiten observar los puntos en los cuales se producen la creaciones de la
ramas y cuando estas convergen

*   _¿Cuál es el resultado de fusionar dos ramas?,¿Porque lo representamos de
esa manera en el diagrama?_

es una que la rama que recibe el merge se añaden las características o el
trabajo realizado en la otra rama de esta manera permite unificar el trabajo,
lo representan de esa manera porque permiten ver el proceso que con lleva hacer
la fusión como es que a la rama se le añaden los log.

*   _¿Cuáles son los pros y  contras entre la función automática que ofrece git
 versus la manual?_

| Pros                              | Contras                        |
| --------------------------------- | ------------------------------ |
| mas rapida                        | puede producir incongruencias  |
| necesita poco del desarrollador   | necesario saber funcionamiento |
