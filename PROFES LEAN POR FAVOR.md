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