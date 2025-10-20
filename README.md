# Informe
Explorando Git y GitHub
<h1>TERMINOS PRINCIPALES DE GIT</h1>
<hr>
<h3>Git</h3>
<p>Sistema de control de versiones en donde podemos tener un seguimiento a sus diferentes versiones y los momentos exactos en donde pudo surgir un error.</p>
<br>
<h3>Repositorio</h3>
<p>Un proyecto que se está trabajando bajo las características de Git.</p>
<br>
<h3>Commit</h3>
<p>Son los cambios y documentación que cada participante le ha hecho al proyecto como un historial.</p>
<br>
<h3>Ramas</h3>
<p>Es como trabajar una parte (rama Dev) del proyecto, pero por aparte (brunch) para no correr el riesgo de perjudicar el funcionamiento del proyecto principal con el fin de que, al terminar y verificar su aporte, se debe añadir (Merge) a la rama principal llamada “Master”.</p>
<br>
<h3>Clon</h3>
<p>Es descargar una copia del proyecto para que tu trabajes en el por separado.</p>
<br>
<h3>Fork</h3>
<p>Es hacer un clone del proyecto de un compañero, pero trabajas desde tu espacio (puede ser desde un repositorio en la nube como GitHub). Una vez terminado tu aporte puedes proponer que lo integren mediante un “pull request”.</p>
<br>
<h3>Stagin Area</h3>
<p>Como si fuera una zona de preparación donde se añaden los archivos que ya modificaste y quieres añadir en el próximo Commit. Sirve como si fuera un filtro para confirmar los cambios antes de hacer un envío oficial.</p>
<br>
<h3>RollBack</h3>
<p>Si hemos introducido un error en una versión, podemos clonar la versión anterior o la que se necesite y trabajar nuevamente partiendo de esa nueva base.</p>
<br>
<h3>Distribuido</h3>
<p>Es decir, es una forma de trabajar de manera segura y en equipo. </p>
<br>
<h3>Detalle de la Implementacion</h3>
<p>	Almacena las diferentes versiones/ramas/commit de nuestro código</p>
<img width="806" height="403" alt="image" src="https://github.com/user-attachments/assets/07bbea7e-9d08-4205-a41e-f12a1ec9399d" />
<hr>
<h1>HERRAMIENTAS DE TRABAJO EN GIT</h1>
<hr>
<h3>Terminal</h3>
<P>La terminal es el lugar en donde se escriben los comandos u instrucciones.</P>
<br>
<h3>Clientes Gráficos</h3>
<P>Como Gitkraken, Sourcetree o GitHub desktop.</P>
<br>
<h3>Repositorios en la nube</h3>
<P>Como GutHub, Bitbucket o Gitlab.</P>
<br>
<h3>Editores de Código</h3>
<P>Como Visual Studio Code, Intellij Idea o Atom.</P>
<hr>
<h1>PRINCIPALES COMANDOS DE GIT</h1>
<hr>
<h3>Git Init</h3>
<p>Inicia un nuevo proyecto y convirtiéndolo en un repositorio.</p>
<br>
<h3>Git Clone</h3>
<p>Es descargar una copia exacta del proyecto para comenzar a trabajar de manera local.</p>
<br>
<h3>Git Add</h3>
<p>Es seleccionar los archivos que quieres guardar en el próximo registro, yéndose al staging area. 
•	Nombre del archivo “archivo1.txt”
•	Agrega todos los archivos con esa extensión *.txt
•	Agrega TODOS los archivos (Mala practica)  “.” 
</p>
<br>
<h3>Git Commit</h3>
<p>El guardado oficial de cada aporte dado.</p>
<br>
<h3>Ls</h3>
<p>Listado de archivos y carpetas según el directorio en el que nos encontremos. Pero no muestra los archivos ocultos.</p>
<br>
<h3>Pdw</h3>
<p>Nos muestra en que directorio nos encontramos.</p>
<br>
<h3>Cd</h3>
<p>Para movernos entre directorios como en node.js “change directory”</p>
<br>
<h3>Cd ..</h3>
<p>Para retroceder de directorio.</p>
<br>
<h3>Mkdir</h3>
<p>Para crear un nuevo directorio.</p>
<br>
<h3>Ls -a</h3>
<p>Muestra todos los archivos incluyendo los que se encuentren vacíos.</p>
<br>
<h3>Git Status</h3>
<p>Muestra el estado actual del repositorio.</p>
<img width="886" height="334" alt="image" src="https://github.com/user-attachments/assets/11d2652c-304d-4b4b-bd6f-9801cf973734"/>
<br>
<h3>Rm</h3>
<p>Elimina un directorio.</p>
<img width="806" height="355" alt="image" src="https://github.com/user-attachments/assets/9fec11a0-c07f-4afc-b9b6-625afc29c0c1" />
<br>
<h3>Git restore –staged</h3>
<p>Sacar algún cambio que hayamos pasado a la etapa de stage.</p>
<img width="816" height="363" alt="image" src="https://github.com/user-attachments/assets/705fd5af-fca2-46d2-838e-cee5c6fa27c5" />
<br>
<h3>Gir restore</h3>
<p>Recuperar un archivo.</p>
<img width="681" height="323" alt="image" src="https://github.com/user-attachments/assets/32cca567-dcb0-4fcb-b034-5737732993fa" />
<br>
<h3>Mv</h3>
<p>Cambiar de nombre al archivo.</p>
<img width="675" height="230" alt="image" src="https://github.com/user-attachments/assets/c534d802-3227-441e-a117-90ff16297cce" />
<img width="677" height="317" alt="image" src="https://github.com/user-attachments/assets/716b164f-70d4-4813-ac9e-c65f67450763" />
<br>
<h3>Git status -s</h3>
<p>Nos muestra la información más condensada, especifica.</p>
<img width="670" height="120" alt="image" src="https://github.com/user-attachments/assets/254accb9-414b-4a33-bf38-7eb53ad9e824" />
<br>
<h3>Git diff</h3>
<p>Muestra la información más grafica.</p>
<img width="659" height="372" alt="image" src="https://github.com/user-attachments/assets/bd14b178-962d-4858-9547-e0ba88736b36" />
<br>
<h3>Git diff –staged</h3>
<p>Muestra los cambios que se encuentran en la etapa de stage.</p>
<img width="673" height="384" alt="image" src="https://github.com/user-attachments/assets/b37277e8-7432-49be-b89f-ff618b25aac7" />
<br>
<h3>Git log</h3>
<p>Muestra quien a que hora realizo un cambio.</p>
<img width="716" height="1028" alt="image" src="https://github.com/user-attachments/assets/d9eb28c1-e3ff-48dd-a0ed-c84511b03f6b" />
<br>
<h3>Git log –oneline</h3>
<p>Condensa la información, muestra un número que identifica los commit.</p>
<img width="689" height="288" alt="image" src="https://github.com/user-attachments/assets/d4d05919-1195-44d4-9860-8ec40e8d896c" />
<br>
