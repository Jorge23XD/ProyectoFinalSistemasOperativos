bplist00�_WebMainResource�	
^WebResourceURL_WebResourceFrameName_WebResourceData_WebResourceMIMEType_WebResourceTextEncodingName_file:///index.htmlPO��<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta http-equiv="Content-Style-Type" content="text/css">
  <title></title>
  <meta name="Generator" content="Cocoa HTML Writer">
  <meta name="CocoaVersion" content="1894.6">
  <style type="text/css">
    p.p1 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica}
    p.p2 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica; min-height: 14.0px}
    span.Apple-tab-span {white-space:pre}
  </style>
</head>
<body>
<p class="p1"># Examen Final</p>
<p class="p2"><br></p>
<p class="p1">## Sistemas Operativos</p>
<p class="p1">## Jorge David Blanco Contreras</p>
<p class="p1">## 2 de noviembre del 2022</p>
<p class="p1">## 12077</p>
<p class="p2"><br></p>
<p class="p1">## Sistema operativo</p>
<p class="p1">&gt; El sistema operativo es el software que coordina y dirige todos los servicios y aplicaciones que utiliza el usuario en una computadora, por eso es el más importante y fundamental. Se trata de programas que permiten y regulan los aspectos más básicos del sistema. Los sistemas operativos más utilizados son Windows, Linux, OS/2 y DOS</p>
<p class="p2"><br></p>
<p class="p1">![Tux, the Linux mascot](/assets/prueba/OpenSource.png)<span class="Apple-converted-space"> </span></p>
<p class="p1">## Open Source</p>
<p class="p1">&gt; Es un modelo de desarrollo de software basado en la colaboración abierta. Se enfoca en los beneficios prácticos (acceso al código fuente) y en cuestiones éticas o de libertad que tanto se destacan en el software libre.</p>
<p class="p2"><br></p>
<p class="p1">## Proceso</p>
<p class="p1">&gt; Un proceso no es más que un programa en ejecución, e incluye los valores actuales del contador de programa, los registros y las variables. Conceptualmente cada unos de estos procesos tiene su propia CPU virtual. Desde luego, en la realidad la verdadera CPU conmuta de un proceso a otro.</p>
<p class="p1">Un proceso es un concepto manejado por el sistema operativo que consiste en el conjunto formado por:</p>
<p class="p1">1- Las instrucciones de un programa destinadas a ser ejecutadas por el microprocesador.</p>
<p class="p1">2- Su estado de ejecución en un momento dado, esto es, los valores de los registros de la CPU para dicho programa.</p>
<p class="p1">3- Su memoria de trabajo, es decir, la memoria que ha reservado y sus contenidos.</p>
<p class="p1">4- Otra información que permite al sistema operativo su planificación.</p>
<p class="p1">Los procesos existen en jerarquías de padre-hijo. Un proceso iniciado por un programa o mandato es un proceso padre; un proceso hijo es el producto del proceso padre. Un proceso padre puede tener varios procesos hijo, pero un proceso hijo sólo puede tener un padre.</p>
<p class="p1">El sistema asigna un número de identificación de proceso (número PID) a cada proceso cuando se inicia. Si inicia el mismo programa varias veces, tendrá un número PID distinto cada vez.</p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p1">- SJF: sjfAcrónimo de Shortest Job First (trabajo más corto primero) y algoritmo no apropiativo que supone que los tiempos de ejecución se conocen de antemano. Cuando hay varios trabajos de igual importancia esperando a ser iniciados en la cola de entrada, el planificador selecciona el trabajo más corto primero</p>
<p class="p2"><br></p>
<p class="p1">- SRTN: Shortest Remaining Time Next (menor tiempo restante a continuación). Algoritmo apropiativo donde el planificador siempre selecciona el proceso cuyo tiempo restante de ejecución sea el más corto. De nuevo, se debe conocer el tiempo de ejecución de antemano. Cuando llega un nuevo trabajo, su tiempo total se compara con el tiempo restante del proceso actual. Si el nuevo trabajo necesita menos tiempo para terminar que el proceso actual, éste se suspende y el nuevo trabajo se inicia. Ese esquema permite que los trabajos cortos nuevos obtengan un buen servicio.</p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p1"># Jerarquía de memoria</p>
<p class="p1">&gt; <span class="Apple-converted-space">  </span>Es la organización piramidal de la memoria en niveles que tienen las computadoras.</p>
<p class="p2"><br></p>
<p class="p1">## Los niveles</p>
<p class="p1">- Nivel 0: Registro (Es una memoria de alta velocidad y poca capacidad, integrada en el microprocesador, que permite guardar transitoriamente y acceder a valores muy usados, generalmente en operaciones matemáticas.).</p>
<p class="p1">- Nivel 1: Memoria caché (Es un componente de hardware o software que guarda datos para que las solicitudes futuras de esos datos se puedan atender con mayor rapidez; los datos almacenados en una caché pueden ser el resultado de un cálculo anterior o el duplicado de datos almacenados en otro lugar, generalmente, da velocidad de acceso más rápido.).</p>
<p class="p1">- Nivel 2: Memoria primaria (Es la memoria de la computadora donde se almacenan temporalmente tanto los datos como los programas que la unidad central de procesamiento "CPU" está procesando o va a procesar en un determinado momento.).</p>
<p class="p1">- Nivel 3: Disco duro (Es un dispositivo de almacenamiento de datos que emplea un sistema de grabación magnética para almacenar y recuperar archivos digitales.).</p>
<p class="p1">- Nivel 4: Cintas magnéticas (Son un tipo de medio o soporte de almacenamiento de datos que se graba en pistas sobre una banda plástica con un material magnetizado, generalmente óxido de hierro o algún cromato. El tipo de información que se puede almacenar en las cintas magnéticas es variado, como vídeo, audio y datos.).</p>
<p class="p2"><br></p>
<p class="p1">## Virtualización de CPU<span class="Apple-converted-space"> </span></p>
<p class="p1">```sh</p>
<p class="p1">#include &lt;stdio.h&gt;</p>
<p class="p1">#include &lt;stdlib.h&gt;</p>
<p class="p1">#include "common.h"</p>
<p class="p2"><br></p>
<p class="p1">int main(int argc, char *argv[])</p>
<p class="p1">{</p>
<p class="p1"><span class="Apple-converted-space">    </span>if (argc != 2) {</p>
<p class="p1"><span class="Apple-converted-space">        </span>fprintf(stderr, "usage: cpu &lt;string&gt;\n");</p>
<p class="p1"><span class="Apple-converted-space">        </span>exit(1);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>char *str = argv[1];</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>while (1) {</p>
<p class="p1"><span class="Apple-converted-space">        </span>printf("%s\n", str);</p>
<p class="p1"><span class="Apple-converted-space">        </span>Spin(1);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>return 0;</p>
<p class="p1">}</p>
<p class="p1">```</p>
<p class="p2"><br></p>
<p class="p1">## Virtualización de Memoria</p>
<p class="p1">```sh</p>
<p class="p1">#include &lt;unistd.h&gt;</p>
<p class="p1">#include &lt;stdio.h&gt;</p>
<p class="p1">#include &lt;stdlib.h&gt;</p>
<p class="p1">#include "common.h"</p>
<p class="p2"><br></p>
<p class="p1">int main(int argc, char *argv[]) {</p>
<p class="p1"><span class="Apple-converted-space">    </span>if (argc != 2) {<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">        </span>fprintf(stderr, "usage: mem &lt;value&gt;\n");<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">        </span>exit(1);<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>}<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>int *p;<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>p = malloc(sizeof(int));<span class="Apple-converted-space">                                      </span>//a1</p>
<p class="p1"><span class="Apple-converted-space">    </span>assert(p != NULL);</p>
<p class="p1"><span class="Apple-converted-space">    </span>printf("(%d) addr pointed to by p: %p\n", (int) getpid(), p); //a2</p>
<p class="p1"><span class="Apple-converted-space">    </span>*p = atoi(argv[1]); // assign value to addr stored in p.<span class="Apple-converted-space">      </span>//a3</p>
<p class="p1"><span class="Apple-converted-space">    </span>while (1) {</p>
<p class="p1"><span class="Apple-converted-space">        </span>Spin(1);<span class="Apple-converted-space">                                                  </span>//a4</p>
<p class="p1"><span class="Apple-converted-space">            </span>*p = *p + 1;</p>
<p class="p1"><span class="Apple-converted-space">            </span>printf("(%d) value of p: %d\n", getpid(), *p);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>return 0;</p>
<p class="p1">}</p>
<p class="p1">```</p>
<p class="p2"><br></p>
<p class="p1">## Concurrencia</p>
<p class="p1">```sh</p>
<p class="p1">#include &lt;stdio.h&gt;</p>
<p class="p1">#include &lt;stdlib.h&gt;</p>
<p class="p1">#include "common.h"</p>
<p class="p1">#include "common_threads.h"</p>
<p class="p2"><br></p>
<p class="p1">volatile int counter = 0;<span class="Apple-converted-space"> </span></p>
<p class="p1">int loops;</p>
<p class="p2"><br></p>
<p class="p1">void *worker(void *arg) {</p>
<p class="p1"><span class="Apple-converted-space">    </span>int i;</p>
<p class="p1"><span class="Apple-converted-space">    </span>for (i = 0; i &lt; loops; i++) {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-converted-space">    </span>counter++;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>return NULL;</p>
<p class="p1">}</p>
<p class="p2"><br></p>
<p class="p1">int main(int argc, char *argv[]) {</p>
<p class="p1"><span class="Apple-converted-space">    </span>if (argc != 2) {<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">        </span>fprintf(stderr, "usage: threads &lt;loops&gt;\n");<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">        </span>exit(1);<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>}<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>loops = atoi(argv[1]);</p>
<p class="p1"><span class="Apple-converted-space">    </span>pthread_t p1, p2;</p>
<p class="p1"><span class="Apple-converted-space">    </span>printf("Initial value : %d\n", counter);</p>
<p class="p1"><span class="Apple-converted-space">    </span>Pthread_create(&amp;p1, NULL, worker, NULL);<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>Pthread_create(&amp;p2, NULL, worker, NULL);</p>
<p class="p1"><span class="Apple-converted-space">    </span>Pthread_join(p1, NULL);</p>
<p class="p1"><span class="Apple-converted-space">    </span>Pthread_join(p2, NULL);</p>
<p class="p1"><span class="Apple-converted-space">    </span>printf("Final value <span class="Apple-converted-space">  </span>: %d\n", counter);</p>
<p class="p1"><span class="Apple-converted-space">    </span>return 0;</p>
<p class="p1">}</p>
<p class="p1">```</p>
<p class="p2"><br></p>
<p class="p1">## Persistencia<span class="Apple-converted-space"> </span></p>
<p class="p1">```sh</p>
<p class="p1">#include &lt;stdio.h&gt;</p>
<p class="p1">#include &lt;unistd.h&gt;</p>
<p class="p1">#include &lt;assert.h&gt;</p>
<p class="p1">#include &lt;fcntl.h&gt;</p>
<p class="p1">#include &lt;sys/stat.h&gt;</p>
<p class="p1">#include &lt;sys/types.h&gt;</p>
<p class="p1">#include &lt;string.h&gt;</p>
<p class="p2"><br></p>
<p class="p1">int main(int argc, char *argv[]) {</p>
<p class="p1"><span class="Apple-converted-space">    </span>int fd = open("/tmp/file", O_WRONLY | O_CREAT | O_TRUNC, S_IRUSR | S_IWUSR);</p>
<p class="p1"><span class="Apple-converted-space">    </span>assert(fd &gt;= 0);</p>
<p class="p1"><span class="Apple-converted-space">    </span>char buffer[20];</p>
<p class="p1"><span class="Apple-converted-space">    </span>sprintf(buffer, "hello world\n");</p>
<p class="p1"><span class="Apple-converted-space">    </span>int rc = write(fd, buffer, strlen(buffer));</p>
<p class="p1"><span class="Apple-converted-space">    </span>assert(rc == (strlen(buffer)));</p>
<p class="p1"><span class="Apple-converted-space">    </span>fsync(fd);</p>
<p class="p1"><span class="Apple-converted-space">    </span>close(fd);</p>
<p class="p1"><span class="Apple-converted-space">    </span>return 0;</p>
<p class="p1">}</p>
<p class="p1">```</p>
<p class="p1"><span class="Apple-converted-space"> </span># Almacenamiento</p>
<p class="p1"><span class="Apple-converted-space"> </span>&gt; Usualmente, el almacenamiento se da en forma de una unidad de estado sólido o un disco duro. El almacenamiento le permite acceder y almacenar sus aplicaciones, sistema operativo y archivos por un tiempo indefinido.</p>
<p class="p2"><br></p>
<p class="p1"># Dispositivos de entrada y salida</p>
<p class="p1"><span class="Apple-converted-space"> </span>&gt; Los dispositivos de entrada y salida o unidades de entrada/salida son los equipos físicos conectados a la computadora. Estos dispositivos permiten comunicar información entre el usuario y la computadora o manejar un soporte de información.</p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p1">## Dispositivos de entrada</p>
<p class="p2"><br></p>
<p class="p1">&gt; Los dispositivos de entrada son aquellos equipos encargados de introducir datos en la memoria central de la computadora para su tratamiento. A través de ellos se transforma la información de entrada en señales eléctricas.</p>
<p class="p2"><br></p>
<p class="p1">- Teclado: permite la comunicación entre el usuario y la computadora. Dispone de un conjunto de teclas agrupadas en cuatro bloques denominados alfabético, numérico, de control y teclas de función.</p>
<p class="p2"><br></p>
<p class="p1">- Ratón o mouse de computadora: es una unidad de entrada constituida por una pequeña cajetilla con controles que se adapta a la mano y permite el movimiento del cursor en la pantalla. Existen ratones mecánicos, ópticos y opto-mecánicos.</p>
<p class="p1">-<span class="Apple-converted-space">  </span>Micrófono: son dispositivos que reciben las señales de audio y las transforman en señales eléctricas que son procesadas por el computador.</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space"> </span>- Cámara fotográfica digital: dispositivo que se puede utilizar para introducir imágenes sin necesidad de revelado.</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space"> </span>- Cámara digital de video o WebCam: es una cámara que transmite imágenes en tiempo real a una computadora.</p>
<p class="p2"><br></p>
<p class="p1"># Dispositivos de salida</p>
<p class="p1">&gt; Los dispositivos de salida son los equipos que presentan la información al usuario de forma comprensible, ya sea a través de imágenes, texto, sonidos o táctil. Estos realizan la función de extraer datos de la memoria central hacia el exterior.</p>
<p class="p2"><br></p>
<p class="p1">-<span class="Apple-converted-space">  </span>Pantalla o display: consiste en un sistema de representación mediante configuraciones de puntos luminosos denominados píxeles. La resolución de pantalla es el número de píxeles que posee. En las computadoras de escritorio o desktop se le conoce como monitor.</p>
<p class="p2"><br></p>
<p class="p1">-<span class="Apple-converted-space">  </span>Impresoras: son unidades de salida de datos soportados en papel. Existen diversos tipos de impresoras, entre ellas las impresoras térmicas, electrostáticas, de tinta y láser.</p>
<p class="p2"><br></p>
<p class="p1">-<span class="Apple-converted-space">  </span>Altavoz: son dispositivos que transforman las señales eléctricas en señales de audio.</p>
<p class="p2"><br></p>
<p class="p1">-<span class="Apple-converted-space">  </span>Trazadores gráficos o plotters: son dispositivos capaces de imprimir un gráfico o dibujo.</p>
<p class="p2"><br></p>
<p class="p1">-<span class="Apple-converted-space">  </span>Robots: son unidades de salida que poseen un complemento mecánico capaz de realizar movimientos ordenados desde la computadora.</p>
<p class="p2"><br></p>
<p class="p1"># Dispositivos mixtos</p>
<p class="p1">&gt; Los<span class="Apple-converted-space">  </span>dispositivos mixtos permiten la introducción y extracción de datos en la memoria central.</p>
<p class="p2"><br></p>
<p class="p1">- Pantalla táctil: es una pantalla que incluye un dispositivo que reconoce la zona de la misma donde se ha realizado un pequeño contacto con el dedo.</p>
<p class="p2"><br></p>
<p class="p1">- Impresoras multifunción: son equipos con la capacidad de realizar varias funciones, como imprimir, escanear y fotocopiar.</p>
<p class="p2"><br></p>
<p class="p1">- Teclado MIDI (Musical Instrument Digital Interface): son teclados musicales parecidos a pianos electrónicos que permiten la interconexión de distintos instrumentos musicales y accesorios electrónicos. Pueden recibir tanto las señales de instrumentos musicales como generar sonidos.</p>
<p class="p2"><br></p>
<p class="p1">- Terminales punto de venta: son unidades de entrada/salida especiales para aplicaciones de tipo comercial. Estos dispositivos han sustituido las cajas registradoras antiguas.</p>
<p class="p2"><br></p>
<p class="p1">- Terminales para operaciones financieras: mejor conocidos como cajeros automáticos, son unidades conectadas a una computadora central de una entidad financiera para la realización de operaciones de los clientes de dicha entidad.</p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p1">## Comandos basicos de Linux</p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p1">| Comando | Uso |</p>
<p class="p1">| ------ | ------ |</p>
<p class="p1">| <span class="Apple-converted-space">  </span>pwd | Usa el comando pwd para encontrar la ruta del directorio (carpeta) de trabajo actual en el que te encuentras. El comando devolverá una ruta absoluta (completa), que es básicamente una ruta de todos los directorios que comienzan con una barra diagonal (/) Un ejemplo de una ruta absoluta es /home/nombredeusuario.|</p>
<p class="p1">|<span class="Apple-converted-space">  </span>cd | Para navegar por los archivos y directorios de Linux, usa el comando cd. Te pedirá la ruta completa o el nombre del directorio, dependiendo del directorio de trabajo actual en el que te encuentres. |</p>
<p class="p1">| ls | El comando ls se usa para ver el contenido de un directorio. Por defecto, este comando mostrará el contenido de tu directorio de trabajo actual. |</p>
<p class="p1">| cat| Se utiliza para listar el contenido de un archivo en la salida estándar (sdout). Para ejecutar este comando, escribe cat seguido del nombre del archivo y su extensión. Por ejemplo: cat archivo.txt. |</p>
<p class="p1">|cp |Usa el comando cp para copiar archivos del directorio actual a un directorio diferente. Por ejemplo, el comando cp escenario.jpg /home/nombredeusuario/Imagenes crearía una copia de escenario.jpg (desde tu directorio actual) en el directorio de Imagenes. |</p>
<p class="p1">| mv| El uso principal del comando mv es mover archivos, aunque también se puede usar para cambiar el nombre de los archivos.Los argumentos en mv son similares al comando cp. Debes escribir mv, el nombre del archivo y el directorio destino. Por ejemplo: mv archivo.txt /home/nombredeusuario/Documentos.<span class="Apple-converted-space">  </span>|</p>
<p class="p1">|mkdir |<span class="Apple-converted-space">  </span>Usa el comando mkdir para crear un nuevo directorio: si escribes mkdir Musica, creará un directorio llamado Musica.|</p>
<p class="p1">| rmdir | Si necesitas eliminar un directorio, usa el comando rmdir. Sin embargo, rmdir solo te permite eliminar directorios vacíos.|</p>
<p class="p1">|rm | El comando rm se usa para eliminar directorios y el contenido dentro de ellos. Si solo deseas eliminar el directorio, como alternativa a rmdir, usa rm -r. |</p>
<p class="p1">| touch |<span class="Apple-converted-space">  </span>El comando touch te permite crear un nuevo archivo en blanco a través de la línea de comando de Linux. Como ejemplo, ingresa touch /home/nombredeusuario/Documentos/Web.html para crear un archivo HTML titulado Web en el directorio Documentos.|</p>
<p class="p1">| locate | Puedes usar este comando para localizar un archivo, al igual que el comando de búsqueda en Windows. Además, el uso del argumento -i junto con este comando hará que no distinga entre mayúsculas y minúsculas, por lo que puedes buscar un archivo incluso si no recuerdas su nombre exacto.|</p>
<p class="p1">| find |<span class="Apple-converted-space">  </span>Similar al comando locate, usando find también buscas archivos y directorios. La diferencia es que usas el comando find para ubicar archivos dentro de un directorio dado. Como ejemplo, el comando find /home/ -name notas.txt buscará un archivo llamado notas.txt dentro del directorio de inicio y sus subdirectorios.|</p>
<p class="p1">|grep | Te permite buscar a través de todo el texto en un archivo dado. Para ilustrar, grep azul notepad.txt buscará la palabra azul en el archivo del bloc de notas. Las líneas que contienen la palabra buscada se mostrarán. |</p>
<p class="p1">|sudo | Te permite realizar tareas que requieren permisos administrativos o raíz. Sin embargo, no es aconsejable usar este comando para el uso diario, ya que podría ser fácil que ocurra un error si haces algo mal.|</p>
<p class="p1">| df | Usa el comando df para obtener un informe sobre el uso del espacio en disco del sistema, que se muestra en porcentaje y KB. Si deseas ver el informe en megabytes, escribe df -m. |</p>
<p class="p1">| du | Verifica cuánto espacio ocupa un archivo o un directorio. Sin embargo, el resumen de uso del disco mostrará números de bloque de disco en lugar del formato de tamaño habitual. Si deseas verlo en bytes, kilobytes y megabytes, agrega el argumento -h a la línea de comando. |</p>
<p class="p1">|head | Se usa para ver las primeras líneas de cualquier archivo de texto. De manera predeterminada, mostrará las primeras diez líneas, pero puedes cambiar este número a tu gusto. Por ejemplo, si solo deseas mostrar las primeras cinco líneas, escribe head -n 5 nombredearchivo.ext.|</p>
<p class="p1">|tail | Este tiene una función similar al comando head, pero en lugar de mostrar las primeras líneas, el comando tail mostrará las últimas diez líneas de un archivo de texto. Por ejemplo, tail -n nombredearchivo.ext. |</p>
<p class="p1">|diff |<span class="Apple-converted-space">  </span>Compara el contenido de dos archivos línea por línea. Después de analizar los archivos, genera las líneas que no coinciden. Los programadores a menudo usan este comando cuando necesitan hacer modificaciones al programa en lugar de reescribir todo el código fuente. La forma más simple de usar este comando es diff archivo1.ext archivo2.ext|</p>
<p class="p1">| tar |El comando tar es el comando más utilizado para guardar múltiples archivos en un tarball, un formato de archivo de Linux común que es similar al formato zip, con compresión opcional. Este comando es bastante complejo con una larga lista de funciones, como agregar nuevos archivos a un archivo existente, enumerar el contenido de un archivo, extraer el contenido de un archivo y muchos más. |</p>
<p class="p1">| chmod |<span class="Apple-converted-space">  </span>Es utilizado para cambiar los permisos de lectura, escritura y ejecución de archivos y directorios. |</p>
<p class="p1">|chown |Te permite cambiar o transferir la propiedad de un archivo al nombre de usuario especificado. Por ejemplo, chown usuariolinux2 archivo.ext hará que usuariolinux2 sea el propietario del archivo.ext.<span class="Apple-converted-space">  </span>|</p>
<p class="p1">|jobs | Mostrará todos los trabajos actuales junto con sus estados. Un trabajo es básicamente un proceso iniciado por el shell. |</p>
<p class="p1">|kill | Si tienes un programa que no responde, puedes cerrarlo manualmente utilizando este comando. Enviará una cierta señal al programa que se está ejecutando mal y le indica a la aplicación que finalice.|</p>
<p class="p1">|ping |Usa el comando ping para verificar tu estado de conectividad a un servidor. Por ejemplo, simplemente ingresando ping google.com, el comando verificará si puedes conectarte a Google y también medirá el tiempo de respuesta. |</p>
<p class="p1">|<span class="Apple-converted-space">  </span>ping| Se usa para verificar tu estado de conectividad a un servidor. Por ejemplo, simplemente ingresando ping google.com, el comando verificará si puedes conectarte a Google y también medirá el tiempo de respuesta.|</p>
<p class="p1">| uname| Imprimirá información detallada sobre tu sistema Linux, como el nombre de la máquina, el sistema operativo, el núcleo, etc.|</p>
<p class="p1">| top| Mostrará una lista de los procesos en ejecución y la cantidad de CPU que utiliza cada proceso. Es muy útil monitorear el uso de los recursos del sistema, especialmente para saber qué proceso debe terminarse porque consume demasiados recursos.|</p>
<p class="p1">| wget|Se usa para descargar archivos de Internet con la ayuda del comando wget. Para hacerlo, simplemente escribe wget seguido del enlace de descarga. |</p>
<p class="p1">|history |Se usa si deseas revisar los comandos que ingresaste anteriormente. |</p>
<p class="p1">| man |Sirve para que puedas aprender fácilmente cómo usar los comandos de Linux directamente desde el shell de Linux mediante el comando man. Por ejemplo, al ingresar man tail se mostrarán las instrucciones manuales del comando tail. |</p>
<p class="p1">| echo|Este comando se usa para mover algunos datos a un archivo. Por ejemplo, si deseas agregar el texto «Hola, mi nombre es John» en un archivo llamado nombre.txt, debes escribir echo Hola, mi nombre es John &gt;&gt; nombre.txt |</p>
<p class="p1">| zip, unzip |Usa el comando zip para comprimir tus archivos en un archivo zip y use el comando unzip para extraer los archivos comprimidos de un archivo zip. |</p>
<p class="p1">|hostname | Se utiliza si deseas conocer el nombre de tu host/red, simplemente escribe hostname. Agregar un -I al final mostrará la dirección IP de tu red. |</p>
<p class="p1">| useradd, userdel| Dado que Linux es un sistema multiusuario, esto significa que más de una persona puede interactuar con el mismo sistema al mismo tiempo. useradd se usa para crear un nuevo usuario, mientras que passwd agrega una contraseña a la cuenta de ese usuario. Para agregar una nueva persona llamada John, escribe useradd John y luego para agregar su contraseña, escribe passwd 123456789. Eliminar un usuario es muy similar a agregar un nuevo usuario. Para eliminar la cuenta de usuario, escribe userdel NombredeUsuario|</p>
<p class="p2"><br></p>
<p class="p1">## Personajes importantes para los sistemas operativos<span class="Apple-converted-space"> </span></p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p1">| Personaje | Hechos |</p>
<p class="p1">| ------ | ------ |</p>
<p class="p1">|<span class="Apple-converted-space">  </span>Ada Lovelace |Ada Lovelace tradujo del francés al inglés el manual de la famosa máquina analítica de Charles Babbage, y agregó unas notas en las que planteaba la idea de una máquina universal programable (en un tiempo que no existían los lenguajes de programación).En sus notas escribió algoritmos, definiendo las subrutinas, las condicionales y los bucles recursivos para calcular los números de Bernoulli, todo en papel. La máquina analítica nunca se construyó, por lo que los algoritmos de Ada Lovelace se quedaron plasmados en papel. Pero más adelante se construyó, y funcionaban. Por su influencia en el mundo de la informática, el primer lenguaje de programación utilizado por las fuerzas militares de EE.UU fue llamado "ADA" en su honor. |</p>
<p class="p1">| Grace Hoppe| Grace Hopper escribió el primer libro de programación: un manual de instrucciones para programar el Mark I. |</p>
<p class="p1">| <span class="Apple-converted-space">  </span>Guido Van Rossum<span class="Apple-converted-space">  </span>| En diciembre del 89, Guido Van Rossum estaba buscando un "hobby” de programación que lo distrajese durante Navidad. Fue entonces cuando comenzó escribir un nuevo lenguaje de programación, al que llamaría Python Como Van Rossum creó este lenguaje sin ánimos de lucro, lo liberó a la comunidad. Python ha crecido tanto que se utiliza en el data science, Inteligencia artificial y en el desarrollo de aplicaciones de todo tipo, incluyendo algunas famosas como: Pinterest, Dropbox, Instagram, Netflix, Spotify, Instagram, Uber, y hasta Windows 10.|</p>
<p class="p1">|<span class="Apple-converted-space">  </span>Tim Berners-Lee | En el año 1984, Berners-Lee estaba frustrado mientras trabajaba como investigador en el CERN (Organización Europea para la Investigación Nuclear), porque los métodos para compartir información eran demasiado engorrosos: Había que intercambiar correos electrónicos, o aún peor, iniciar y cerrar sesión en diferentes ordenadores para acceder a la información. Aquí fue cuando a él se le ocurrió la idea de que los documentos se conectasen unos con otros. A esa conexión le llamó hipervínculo o hipertexto, el famoso “link”, la base de toda la web. Pero faltaba algo, un elemento necesario para crear documentos que contuvieran enlaces. Así creó un lenguaje de marcado, al que llamó HTML (HyperText Markup Language). Hoy, HTML es el lenguaje con el que se construye toda la web, y puedes aprenderlo aquí en EDteam con el mejor curso de HTML en español. |</p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p1">## ¿Qué necesito para instalar Linux en mi Mac?</p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p1">Lo primero que necesitas es un Mac, lo segundo un sistema Linux, y lo tercero, pero no por ello menos importante, un pendrive USB.</p>
<p class="p2"><br></p>
<p class="p1">Los primeros pasos son los que más cuestan, pero una vez que se pone todo en orden, verás como será mas sencillo.</p>
<p class="p2"><br></p>
<p class="p1">Hay que no todas las máquinas es posible instalarlo sin problemas, en algunos modelos más modernos con las últimas versiones de Windows el arranque de estas máquinas puede dar algún que otro quebradero de cabeza.</p>
<p class="p2"><br></p>
<p class="p1">Si este es tu caso, vas a tener que investigar un poco más en los foros de soporte, pero nada que no pueda ser salvable seguramente.</p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p1">Primeros pasos: Crear un USB de instalación con Ubuntu:</p>
<p class="p2"><br></p>
<p class="p1">```sh</p>
<p class="p1"><span class="Apple-converted-space"> </span>Para llevar a cabo la instalación de Ubuntu necesitamos un USB con<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space"> </span>el instalador (valga la rebuznancia).</p>
<p class="p2"><br></p>
<p class="p1">El proceso es bien sencillo, desde la web de uNetbootin nos descargamos el software para crear nuestro USB maestro.</p>
<p class="p2"><br></p>
<p class="p1">Una vez descargado e instalado en nuestra máquina, tendremos que escoger una distribución de la lista, en nuestro caso dijimos que iba a ser Ubuntu 14.04 LTS, para 32 o 64 bit según la máquina que tengamos (i386 para 32bit y amd64 para 64bit).</p>
<p class="p2"><br></p>
<p class="p1">Enchufamos nuestro pendrive al ordenata, lo formateamos con un sistema de archivos FAT32 (esto es importante) y le damos a crear nuestro USB maestro con uNetbootin.</p>
<p class="p2"><br></p>
<p class="p1">Despues de unos minutos, tendremos el pendrive listo.</p>
<p class="p1">```</p>
<p class="p2"><br></p>
<p class="p1">Segundo paso: El USB esta creado :</p>
<p class="p2"><br></p>
<p class="p1">```sh</p>
<p class="p1">Solo debes enchufar el pendrive en el puerto correspondiente, reiniciar y pulsar la tecla Alt mientras se inicia.</p>
<p class="p2"><br></p>
<p class="p1">Si tienes la suerte de que tu modelo es compatible con Ubuntu, aparecerá un icono con tu disco duro principal y al lado un disco USB, que será tu instalador de Ubuntu.</p>
<p class="p2"><br></p>
<p class="p1">Pero espera, estás yendo muy rápido.</p>
<p class="p2"><br></p>
<p class="p1">Si vas a instalar Ubuntu en tu Mac, lo más seguro es que quieras conservar tu sistema principal.</p>
<p class="p2"><br></p>
<p class="p1">A no ser que te hayas cabreado con OS X, pero no veo por qué debieras hacerlo ya que funciona bien.<span class="Apple-converted-space"> </span></p>
<p class="p2"><br></p>
<p class="p1">No obstante, el caso es que quieres probar Linux en tu Mac, y para eso vas a tener que dar un paso intermedio.</p>
<p class="p2"><br></p>
<p class="p1">Ese paso intermedio se llama BootCamp, es una herramienta nativa de Mac que te permite instalar otro sistema operativo junto a OS X. .</p>
<p class="p2"><br></p>
<p class="p1">Se usa para instalar Windows, pero también te pide instalar Ubuntu.</p>
<p class="p2"><br></p>
<p class="p1">El proceso es sencillo, lo buscas entre las aplicaciones de OS X, lo abres y sigues las instrucciones.</p>
<p class="p2"><br></p>
<p class="p1">Tan solo deberás de asignar el espacio que quieres usar para cada sistema (asígnale una cantidad decente a Linux, no te quedes pelado con 10 Gb) y el asistente redimensionará la partición de OS X y creará la nueva de Windows.</p>
<p class="p2"><br></p>
<p class="p1">Una vez creada, entonces es cuando podrás instalar Ubuntu junto a OS X, y no antes.</p>
<p class="p1">```</p>
<p class="p2"><br></p>
<p class="p1">Tercer paso: Instalando Ubuntu en tu disco duro:</p>
<p class="p1">&gt; Por seguridad,<span class="Apple-converted-space">  </span>antes de hacer la partición BootCam, te recomendaría que hicieras una copia de seguridad de tus datos en un disco externo.<span class="Apple-converted-space"> </span></p>
<p class="p1">Como segunda recomendación, se deberia probar el nuevo sistema en modo “Live”, esto es, sin instalarlo.</p>
<p class="p1">Esto se debe en muchos casos Linux y el hardware de tu máquina no siempre funcionan a la perfección, así que mejor probar que la gráfica, tu adaptador WiFi o tu tarjeta de sonido funcionan perfectamente y no pasar el trabajo de instalarlo para tener una mala experiencia.<span class="Apple-converted-space"> </span></p>
<p class="p1">Una vez comprobado, es tan sencillo como ejecutar el instalador y empezar con la configuración.</p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p1">```sh</p>
<p class="p1">Realmente no hay mucho que configurar instalando Ubuntu, eso es lo bueno de este sistema.</p>
<p class="p2"><br></p>
<p class="p1">Está pensado para el usuario medio, y al margen de la configuración de la BIOS y tal, es más que sencillo.</p>
<p class="p2"><br></p>
<p class="p1">Lo primero que nos pedirá será el idioma de la instalación, aquí puedes usar el que más rabia te dé.</p>
<p class="p2"><br></p>
<p class="p1">Eso sí, no hagas como cuando le regalamos un móvil a mi abuela y por accidente cambió el idioma al vasco, vaya odisea volver a configurarlo…</p>
<p class="p2"><br></p>
<p class="p1">Después nos pedirá comprobar que las condiciones para instalar Ubuntu son las adecuadas, esto es:</p>
<p class="p2"><br></p>
<p class="p1">que en tu disco duro tengas más de 6,7 Gb libres</p>
<p class="p1">comprobar que estés conectado a la toma de corriente</p>
<p class="p1">y preferiblemente que tengas una conexión a internet</p>
<p class="p1">Además de esto podremos escoger si queremos descargar actualizaciones mientras se instala y bajar unos complementos para manejar ficheros .mp3</p>
<p class="p2"><br></p>
<p class="p1">Una vez lo tengamos listo, se pedirá como se quiere instalar Ubuntu en el disco, si elegimos junto a Windows nos dará opción para escoger el espacio que asignaremos a cada sistema.</p>
<p class="p2"><br></p>
<p class="p1">(IMPORTANTE: A la hora de escoger el disco de instalación, asegurence que sea el que fue asignado con BootCamp, sino se sobreescribirá OSX y se perdera sistema principal.)</p>
<p class="p1">```</p>
<p class="p1">Instalando</p>
<p class="p2"><br></p>
<p class="p1">```sh</p>
<p class="p1">A medida que se vaya instalando nos irá mostrando unas diapositivas para familiarizarnos y nos pedirá más configuraciones como nuestra zona horaria, el idioma del teclado y nos pedirá que creemos un nombre de usuario y una contraseña para iniciar sesión.</p>
<p class="p2"><br></p>
<p class="p1">Este último paso es importante, pues si olvidas la contraseña puedes tener problemas a la hora de actualizar, instalar software o realizar determinadas acciones que sean importantes como cambiar la configuración del sistema o cosas por el estilo.</p>
<p class="p2"><br></p>
<p class="p1">Y una vez configurado todo esto, tu sistema se reiniciará y que<span class="Apple-converted-space">  </span>se debe pulsar Alt al inicio como cuando arrancamos la instalación, una vez te aparezcan los iconos de los discos, escoges en el que hayas instalado Linux y ya aparecerá.</p>
<p class="p1">```</p>
<p class="p2"><br></p>
<p class="p1">## Historia de MacOS</p>
<p class="p2"><br></p>
<p class="p1">```sh</p>
<p class="p1">La primera vez que se habla del SO de Apple se hace referencia a los primeros años de la empresa, allá por 1984. En esa época se desarrolló la primera versión de Mac OS. Este sistema operativo fue en el que se basaron los ordenadores Apple durante más de dos décadas.</p>
<p class="p2"><br></p>
<p class="p1">La marcha de Steve Jobs tras ser despedido por su propia compañía en 1985 es uno de los hechos que más se recuerdan en la historia de Apple. El cofundador de Apple no se resignó, y se decidió a armar con un socio una compañía llamada NeXT. Aunque en sus inicios vendían hardware muy avanzado para la época, lo importante de esta empresa es lo que significó, décadas más tarde, para el desarrollo del sistema operativo de escritorio de Apple.</p>
<p class="p2"><br></p>
<p class="p1">Mac OS X Server 1.0, nombre en código de esta versión fue Hera, se lanzó oficialmente el 16 de marzo de 1999 y su última actualización fue presentada poco antes del siguiente lanzamiento, el 27 de octubre del 2000 (Fue la 1.2v3). Esta versión solamente fue utilizada internamente por Apple, para testar precisamente el gran cambio que se dio desde Mac OS 9. Hay que esperar a la siguiente actualización para que el público tenga acceso a ella.</p>
<p class="p1">OPENSTEP pasó a ser la base de la plataforma MAC OS X, lanzada en 2001 para el público. Tanto es así que todavía hoy en día se pueden ver algunas de esas claves en el sistema operativo más actual de Apple. ¿Un ejemplo? El comando defaults de Mac OS X está declarado oficialmente por la marca como componente inicial de NeXTStep.</p>
<p class="p1">En 2007, surgio Mac OS X 10.5 Leopard, Apple la definió como la mayor de la historia de Mac OS X (Recordemos que la más grande fue el salto de Mac OS 9 a Mac OS X). Se incorporaron en total unas 300 nuevas funciones. Hay que tener en cuenta que ésta sería la última versión de Apple en dar soporte a PowerPC. Al mismo tiempo, fue también la primera en abandonar el Entorno Classic. Obtuvo la certificación de Intel y fue el primer SO basado en BSD que recibió certificado UNIX 03.</p>
<p class="p2"><br></p>
<p class="p1">En 2009 salio Mac OS 10.6 Snow Leopard, que a diferencia de las versiones anteriores, que se centraron en cambios estéticos y funcionales que el usuario veía a simple vista, en este caso<span class="Apple-converted-space">  </span>las diferencias se notan en el interior. Hubo cambios importantes en la arquitectura que permitieron mejorar notablemente el rendimiento, la estabilidad y la eficiencia del sistema operativo.</p>
<p class="p2"><br></p>
<p class="p1">En 2012, la versión Mac OS X 10.8 Mountain Lion fue con la que llegó, por primera vez, la integración de iOS. Sería el primer paso para ver cómo iPhone e iPad trabajaban conjuntamente con Mac. Otra de las cosas que aparecieron por primera vez fue la potenciación del uso de la nube. iCloud tenía mucho más sentido al integrar la suite ofimática de iWork.</p>
<p class="p2"><br></p>
<p class="p1">En 2015, con Mac OS X 10.11 El Capitan Apple, optó por centrarse en cambios en el rendimiento y mejoras en la interfaz de usuario. Muchos fueron los que se sorprendieron con el nombre, porque tras Mavericks, se esperaba que Yosemite supusiese una nueva rutina Apple y comenzase a llamar a las siguientes versiones con nombres de parques naturales. No fue así.</p>
<p class="p1">```</p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p1">## Historia de Windows</p>
<p class="p2"><br></p>
<p class="p1">```sh</p>
<p class="p1">En 1975 Bill Gates y Paul Allen fundaron la compañía Microsoft en Estados Unidos, con el objetivo de desarrollar y comercializar programas para ejecutar el Altair 8800, un microordenador diseñado en 1974. Gates y Allen desarrollaron el primer lenguaje de programación para el Altair Basic.</p>
<p class="p2"><br></p>
<p class="p1">En 1979 Microsoft lanzó al público el primer sistema operativo llamado Xenix, que resulta obsoleto en la actualidad. En 1981 creó un nuevo sistema operativo que le permitió alcanzar el éxito, el DOS (de la sigla en inglés Disk Operative System que significa Sistema operativo de disco).</p>
<p class="p2"><br></p>
<p class="p1">En 1985 se lanzó la primera versión del actualmente conocido sistema operativo Windows. Tiempo más tarde, en 1989, apareció otro producto que también continúa vigente en la actualidad y que funciona junto con la interfaz de Windows: el paquete informático Microsoft Office, que consiste en un conjunto de aplicaciones integradas, como el Microsoft Word o el Microsoft Excel.</p>
<p class="p2"><br></p>
<p class="p1">En 1990 Microsoft lanzó Windows 3.0, una nueva versión del sistema operativo. A medida que desarrolló versiones mejoradas, modificó el correspondiente número del nombre. Sin embargo, en 1995 lanzó el Windows 95 que ofrecía una interfaz completamente nueva con un explorador de archivos mejorado, un menú de inicio de acceso rápido y una mejor compatibilidad de hardware, entre otras ventajas.</p>
<p class="p2"><br></p>
<p class="p1">A partir de 2012 se lanzó el sistema operativo Windows 8 con un nuevo diseño de imagen que resultó más interactivo y que permitió ser ejecutado a través de las pantallas táctiles. Fue una versión del software pensada para ser ejecutada desde otros dispositivos, como los teléfonos móviles o tabletas, y para convivir con el auge de Internet y las redes sociales.</p>
<p class="p1">```</p>
<p class="p2"><br></p>
<p class="p1">## Historia de Ubuntu</p>
<p class="p2"><br></p>
<p class="p1">```sh</p>
<p class="p1">El 8 de julio de 2004, Mark Shuttleworth y la empresa Canonical Ltd. anunciaron la creación de la distribución Ubuntu. Ésta tuvo una financiación inicial de 10 millones de dólares (US$). El proyecto nació por iniciativa de algunos programadores de los proyectos Debian, Gnome porque se encontraban decepcionados con la manera de operar del proyecto Debian, la distribución Linux sin ánimo de lucro más popular del mundo.</p>
<p class="p2"><br></p>
<p class="p1">De acuerdo con sus fundadores, Debian era un proyecto demasiado burocrático donde no existían responsabilidades definidas y donde cualquier propuesta interesante se ahogaba en un mar de discusiones. Asimismo, Debian no ponía énfasis en estabilizar el desarrollo de sus versiones de prueba y sólo proporcionaba auditorías de seguridad a su versión estable, la cual era utilizada sólo por una minoría debido a la poca o nula vigencia que poseía en términos de la tecnología Linux actual.</p>
<p class="p2"><br></p>
<p class="p1">Tras formar un grupo multidisciplinario, los programadores decidieron buscar el apoyo económico de Mark Shuttleworth, un emprendedor sudafricano que vendió la empresa Thawte a VeriSign, cuatro años después de fundarla en el garaje de su domicilio, por 575 millones de dólares estadounidenses.</p>
<p class="p2"><br></p>
<p class="p1">Shuttleworth vio con simpatía el proyecto y decidió convertirlo en una iniciativa auto sostenible, combinando su experiencia en la creación de nuevas empresas con el talento y la experiencia de los programadores de la plataforma Linux. De esta forma nació la empresa Canonical, la cual se encarga de sostener económicamente el proyecto mediante la comercialización de servicios y soporte técnico a otras empresas. Mientras los programadores armaban el sistema, Shuttleworth aprovechó la ocasión para aplicar una pequeña campaña de mercadotecnia para despertar interés en "la distribución-sin-nombre" (en inglés: the no-name-distro).</p>
<p class="p1">Tras varios meses de trabajo y un breve período de pruebas, la primera versión de Ubuntu (Warty Warthog) fue lanzada el 20 de octubre de 2004.</p>
<p class="p2"><br></p>
<p class="p1">Ubuntu es un sistema operativo basado en Linux y que se distribuye como software libre, el cual incluye su propio entorno de escritorio denominado Unity. Su nombre proviene de la ética homónima, en la que se habla de la existencia de uno mismo como cooperación de los demás.</p>
<p class="p2"><br></p>
<p class="p1">Está orientado al usuario novel y promedio, con un fuerte enfoque en la facilidad de uso y en mejorar la experiencia de usuario. Está compuesto de múltiple software normalmente distribuido bajo una licencia libre o de código abierto. Estadísticas web sugieren que la cuota de mercado de Ubuntu dentro de las distribuciones Linux es, aproximadamente, del 49%, y con una tendencia a aumentar como servidor web. Y un importante incremento activo de 20 millones de usuarios para fines del 2011.</p>
<p class="p2"><br></p>
<p class="p1">Cada lanzamiento de Ubuntu posee un nombre en clave, como también un número de versión basado en el año y el mes del lanzamiento. Por ejemplo, la versión 5.04 fue lanzada en abril de 2005. Cada versión de Ubuntu es lanzada con seis meses de diferencia con respecto al último lanzamiento, aunque el lanzamiento de la versión 6.06 se demoró más de seis meses, debido a que Canonical Ltd. quería desarrollar una distribución a la que fuera posible dar soporte técnico durante tres años en el escritorio y cinco años en el servidor.</p>
<p class="p2"><br></p>
<p class="p1">Canonical provee de soporte técnico y actualizaciones de la seguridad para la mayoría de las versiones de Ubuntu durante 18 meses, a partir de la fecha del lanzamiento. Actualmente existen tres versiones de Ubuntu que cuentan con soporte técnico: la versión 6.06 LTS (Long term support), la versión 6.10 y la versión 7.04.</p>
<p class="p2"><br></p>
<p class="p1">La versión reciente es la 7.04, cuyo nombre en clave es "Feisty Fawn". Este lanzamiento incluyó un reemplazo del demonio init llamado Upstart, así como mejoras en el uso de la memoria de softwares como Evolution y Nautilus. Además incluyó GNOME 2.18.1, Mozilla Firefox 2.0.0.3, OpenOffice.org 2.2, Xorg 7.2, GCC 4.1.1, y la versión 2.6.20 del núcleo Linux.</p>
<p class="p2"><br></p>
<p class="p1">Como en los lanzamientos previos, Feisty permite la actualización directa a partir de una versión previa. La actualización desde la versión 6.10 no es realizada de manera automática, por lo que se requiere de un comando especial para activar Update Manager. Otros métodos, como dist-upgrade (una característica de apt-get), no son recomendados; algunos usuarios reportaron serios problemas en el proceso.</p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p1">```</p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p1">**Listo**</p>
</body>
</html>
Ytext/htmlUutf-8    ( 7 N ` v � � �����                           ��