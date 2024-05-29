# practica_evaluable

Este es mi repositorio remoto llamado practica_evaluable de la asignatura Entornos de desarrollo del modulo DAM 1
Este repositorio es creado en la practica de la segunda evaluación, donde debo desarrollar un ejercicio en el que se solicita una serie de pasos a realizar mediante comandos git utilizados en la terminal del entorno "Git Bash".

Comandos git usados:
cd repositorio: Este comando cambia el directorio actual al directorio llamado “repositorio”.

- git init: Este comando inicializa un nuevo repositorio Git en el directorio actual.

- echo "mi documento" > documento.txt: Este comando crea un archivo llamado “documento.txt” y escribe “mi documento” en él.

- echo "mi segunda linea de documento" >> documento.txt: Este comando añade “mi segunda linea de documento” al final del archivo “documento.txt”.

- git add: Este comando añade los cambios en el directorio de trabajo al área de preparación (staging area) para el próximo commit. Debes especificar qué archivos quieres añadir después de este comando, por ejemplo, git add documento.txt.

- git commit -m "mi texto": Este comando crea un nuevo commit con los cambios que has añadido al área de preparación. “mi texto” es el mensaje del commit.

- git commit -am "mi texto": Este comando añade todos los archivos modificados al área de preparación y crea un nuevo commit con ellos. “mi texto” es el mensaje del commit.

- git push origin main: Este comando sube los cambios al repositorio remoto en la rama “main”.

- git reset --hard HEAD^: Este comando deshace el último commit y todos los cambios en el directorio de trabajo.

- git revert HEAD: Este comando crea un nuevo commit que deshace los cambios del último commit.

- git remote add origin [enlace repositorio]: Este comando añade un nuevo repositorio remoto llamado “origin” con la URL especificada.

- cat documento.txt: Este comando muestra el contenido del archivo “documento.txt”.

- touch documento2.txt: Este comando crea un nuevo archivo vacío llamado “documento2.txt”.

- git merge: Este comando fusiona los cambios de otra rama en la rama actual. Debes especificar qué rama quieres fusionar después de este comando, por ejemplo, git merge feature.

- git fetch origin: Este comando descarga los cambios del repositorio remoto “origin” pero no los fusiona en tu rama actual.

- git checkout: Este comando cambia a otra rama. Debes especificar a qué rama quieres cambiar después de este comando, por ejemplo, git checkout feature.

- git checkout -b: Este comando crea una nueva rama y cambia a ella. Debes especificar el nombre de la nueva rama después de este comando, por ejemplo, git checkout -b feature.

- git log: Este comando muestra el historial de commits.

- git branch: Este comando muestra las ramas locales.

- git branch -d mirama: Este comando elimina la rama local
- “mirama”.

- git push origin --delete mirama: Este comando elimina la rama “mirama” del repositorio remoto “origin”.

- git branch -a: Este comando muestra todas las ramas locales y remotas.

- git tag V1: Este comando crea una nueva etiqueta llamada “V1” en el commit actual.

@author: Identifica al autor del código o de la documentación.

@version: Indica la versión del código o del método/documento.

@param: Describe un parámetro de un método, especificando su nombre

y su propósito.

@return: Documenta el valor de retorno de un método.
@throws: Describe las excepciones que un método puede lanzar.

@see: Crea un enlace a otra clase, método o paquete relacionado.

@since: Indica la versión en la que se introdujo un método o clase.

@serial: Controla la serialización de un objeto.

@deprecated: Marca un método o clase como obsoleto, indicando que se

desaconseja su uso en futuras versiones del código.

@serialData: Se utiliza para documentar el formato de datos serializados

en un objeto.

@serialField: Se utiliza para documentar campos en una clase
serializable.

