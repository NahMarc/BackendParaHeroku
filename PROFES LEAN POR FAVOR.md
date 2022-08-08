Hola no llego a tiempo con la entrega por culpa de un error en el deploy de heroku.
El error es este:
BUILD FAILURE
remote:        [INFO] ------------------------------------------------------------------------
remote:        [INFO] Total time:  9.281 s
remote:        [INFO] Finished at: 2022-08-01T02:32:53Z
remote:        [INFO] ------------------------------------------------------------------------
remote:        [ERROR] Failed to execute goal org.apache.maven.plugins:maven-compiler-plugin:3.8.1:compile (default-compile) on project argprog: Fatal error compiling: invalid flag: --release -> [Help 1]

Intenté comentar la version de java en el pom, tambien intente pasar de herokuCLI a conectar a github, pero al hacer el deploy con github decia que no encontraba lenguaje, 
le agregue un paquete de deploy para java y ahí dijo que no encontraba archivo pom.xml (que como veran en este repositorio, sí existe)

Espero que lean esto y si no apruebo por favor me digan que falló, voy a seguir intentando mañana encontrar el error.
Si encuentro solución voy a actualizar este mismo repositorio con la misma.
El deploy de frontend funciona, y la base de datos en clever cloud también.
Solo esto me ha dado problemas.

Espero que puedan ayudarme mi correo es: ncarrasanperez@gmail.com

PD: El backend me ejecuta y compila perfecto desde el ide apache netbeans.

PD2: Gracias a la orientación del profe Leandro Giménez a cargo de mi grupo del foro de Extension pude deployar mi backend este es el link:
https://deployargprog-nahuel.herokuapp.com/
La conexión como la base de datos de clevercloud está vacía el front no trae ningún dato, supongo que de eso se encargan uds. o díganme cómo hacerlo bien (por algo nos pidieron el script sql cargado en alguno de los repositorios, el mío está en el enlace del repo frontend)

PD 3: A día 7 de agosto puedo decir que ya pude cargar los datos a mi base de datos y solucioné todos los inconvenientes graves y dejé mi página funcionando tal como planeaba presentarla el 31 de Julio, no sé si voy a recursar al final pero desde ya gracias a todos los que trabajan en ArgProg y en especial al profesor Leandro por todo su apoyo.

