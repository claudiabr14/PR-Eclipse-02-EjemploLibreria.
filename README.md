# PR-Eclipse-02-EjemploLibreria.
Reflexión final
Lee el siguiente apartado, dónde se explica la diferencia entre añadir una librería del mismo proyecto o una externa y contesta a las siguientes preguntas:

¿Qué pasaría si exporto el proyecto a un .zip y se lo paso a un amigo o me lo llevo al ordenador de casa? ¿Funcionaría? Razona la respuesta.
Funciona en el caso que haya puesto el .jar en la carpeta /lib usando ADD JARs.

¿Qué pasaría si eliminas el archivo .jar de la carpeta lib? (puedes moverla a otro directorio para probarlo) ¿Qué ha pasado y por qué?
No funciona porque no encuentra la clase.

Y si agrego la librería con Add External JARs.... ¿Observas alguna diferencia en la configuración del Build Path? ¿Crees que si lo exporto a .zip y se lo paso a un compañero le funcionaría?
La ruta del .jar pasa de tener una ruta relativa a una absoluta, si lo comparto no podra encontratlo mi compañero porque no exista la ruta en su ordenador.

¿Por qué no es recomendable usar Add External JARs… en proyectos que vas a compartir?
Porque utilizan una ruta absoluta y solo funcionaría en mi ordenador.
