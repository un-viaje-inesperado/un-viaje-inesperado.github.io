:title: Más alla del dosmil
:date: 2016-07-14 10:00
:category: tutorial
:tags: exploración, guias
:author: Piloto X
:excerpt: Más alla del dosmil
:disqus_identifier: Mas alla del dosmil

Nadie que haya sido fanático de *Una ventana hacia el futuro* (Beyond 2000,
transmitido por un canal de Chile que veíamos por cable en la Argentina de los
'90) puede dar vueltas por los sistemas de New Eden sin dedicarse a la
exploración, que consiste en identificar sitios con tesoros ocultos.

La tarea se inicia mirando si existen anomalías señaladas como *Cosmic
Anomalies* en el Probe Scanner. El paso siguiente es identificar su tipo (si es
de reliquias, de datos o si lo que emite señales cósmicas es un wormhole) y
determinar con exactitud su posición, tareas para las que se liberan ocho sondas
que se comandan desde una ventana especial desde nuestra nave. Posicionar las
sondas en el sistema planetario requiere destreza para determinar con precisión
(y rapidez) la ubicación de estos débiles rastros cósmicos. Dentro de los sitios
de datos y reliquias esperan tesoros resguardados por un sistema de seguridad.
El último paso es realizar un hackeo que nos dará acceso al loot. La anomalía
desaparecerá y posiblemente se regenerará en el futuro, en otro punto del
sistema.

Me voy a saltear la descripción detallada porque hay muchos sitios donde leer el
protocolo de exploración. Sólo me refiero a algunos elementos que no me
resultaban claros cuando empecé:

- Se puede explorar en null-sec con fragatas T1. Las cuatro fragatas funcionan,
  aunque predominan los que recomiendan la Heron (Caldari) porque provee la
  mayor cantidad de mid-slots, donde se ubican módulos imprescindibles o
  importantes para exploración. La Heron posee 5 y le sigue la Imicus (Gallente)
  con 4. La desventaja de la Imicus contra la Heron desaparece al comparar las
  fragatas T2 de Caldari y Gallente: tanto la Buzzard como la Helios poseen 5
  mid-slots (la diferencia está en la distribución de high/lows: 3/2 para la
  Heron y 2/3 para la Helios).

  Esta es una configuración estándar para la fragata Caldari::

      [Heron, T1 Explo Heron]

      Prototype Cloaking Device I
      Core Probe Launcher I, Core Scanner Probe I
      Salvager I

      5MN Quad LiF Restrained Microwarpdrive
      Relic Analyzer I
      Data Analyzer I
      Scan Rangefinding Array I
      Scan Acquisition Array I

      Nanofiber Internal Structure I
      Nanofiber Internal Structure I

      Small Gravity Capacitor Upgrade I
      Small Gravity Capacitor Upgrade I
      [Empty Rig slot]


  Esta es una configuración estándar para la fragata Gallente::

      [Imicus, T1 Explo Imicus]

      Prototype Cloaking Device I
      Core Probe Launcher I, Core Scanner Probe I
      Salvager I

      5MN Y-T8 Compact Microwarpdrive
      Data Analyzer I
      Relic Analyzer I
      Cargo Scanner I

      Nanofiber Internal Structure I
      Nanofiber Internal Structure I
      Nanofiber Internal Structure I

      Small Gravity Capacitor Upgrade I
      Small Gravity Capacitor Upgrade I
      [Empty Rig slot]

- Secuencia de mejoras: el *Core Probe Launcher I* (30k) lleva 8 sondas: *Core
  Scanner Probe I* (8x 7k = 56k). Al ganar confianza cambiarlas las sondas a 8x
  *Sisters Core Scanner Probes* (8x 360k = 2.88m) y más adelante el lanzador a
  *Sisters Core Probe Launcher* (29m). Luego se podría considerar el
  entrenamiento de Astrometrics V para poder usar *Core Probe Launcher II* (2m).

- No se puede estar clokeado (invisible) para lanzar probes ni para hackear un
  sitio. Sin embargo sí se puede escanear para determinar qué clase de Cosmic
  Signature hay en el sistema y también se pueden recuperar las probes durante
  la invisibilidad.

- El escaneo conviene hacerlo cloakeado desde un lugar seguro (`safe spot`_).

  .. _safe spot: http://wiki.eveuniversity.org/Safe_Spot

- Si estamos cloakeados en un sitio y aparece un elemento a menos de 2000m o
  2500m (por ejemplo otra nave que acudió al mismo relic-site en busca de
  tesoros o de fragatas frágiles) perderemos la invisibilidad.

- No hay que preocuparse por ratas en los sitios de exploración. O mejor sí
  preocuparse un poco. En el primer sitio de datos al que fui aparecieron NPCs
  (creo que eran drones) mientras trataba de completar un hackeo, y me mataron
  en 3 segundos. Debe haber sido un Ghost Site. La pobre fragata resiste muy
  poco daño, hay que estar atentos al local, al overview y al escaner
  direccional, siempre listos para huir.

- Como los exploradores viajan entre sistemas para buscar anomalías y luego
  tienen que regresar a casa, se enfrentan a gate-camps y burbujas. Hay que
  aprender el truco del microwarpdrive (MWD) y cloak, o usar fragatas covops
  para poder evadirlas sanos y salvos. El tiempo en que se puede activar el MWD
  después del cloak puede llegar a varios segundos (creo que son 5). En este
  tiempo se pueden activar módulos que no sean agresivos (no sólo el MWD). No es
  necesario desactivar el MWD luego de su primer ciclo ya que se desactiva solo.
  La idea es que al inactivar el cloak estemos cerca de la velocidad de inicio
  de warp. Con este propósito se usa el MWD, para neutralizar la penalización de
  velocidad del cloak. Básicamente el truco consiste en:

  + Llegar saltando desde un sistema y descubrir una flota campeando la gate. 
  + Maldecir a todos los dioses de New Heaven y buscar tranquilidad, tendremos
    un minuto de inmunidad siendo invisibles.
  + Elegir un destino.
  + Alinear en esa dirección (con lo cual perdemos la invisibilidad) e
    inmediatamente activar el cloak (conviene ubicarlo en F1).
  + Activar el MWD (ubicarlo en Alt-F1 o en F2)
  + Spamear el botón de Warp (al alinear debería haber quedado seleccionado el
    objetivo).
  + Cuando el ciclo del MWD esté por completarse, descloakear. Automáticamente
    tendrá prevalencia el warpeo que estuvimos spameando, nadie podrá
    targetearnos.

  Si había burbuja anti-warpeo es poco probable superarla, pero creo que nada
  impide que salgamos de ella cloakeados con la suficiente paciencia y los
  nervios de acero para atravesarla al 10% de la velocidad máxima que tiene
  nuestra nave.

- La nave puede moverse con el cloak puesto (sin warp), aunque sufre una
  penalización en la velocidad, por lo que se mueve al 10% de su máximo. Aún
  así, creo que conviene tirarse el cloak manteniendo el movimiento, ya que si
  por algún motivo nos vieron al colocarnos la manta de invisibilidad, van a
  tener menos chances de dar con nosotros si nos alejamos del lugar, aunque sea
  despacio (calculo que igual podrían encontrarnos, pero tratamos de reducir
  chances). Además, vale el truco de usar el primer ciclo del MWD inmediatamente
  después de activar el cloak). Hay que apuntar en dirección a un lugar vacío.

- La secuencia puede ser:

  + Warp a 100km de algún planeta o cinturón de asteroides.
  + Apuntar en una dirección vacía.
  + Liberar las sondas
  + Activar cloak.
  + Activar el MWD.

- Si estamos esperando que termine el período refractario del cloak podemos
  warpear a distintos lugares para que el tiempo se consuma. No importa dónde
  liberamos las sondas.

- Desde una fragata covops se puede activar el cloak incluso en el medio de un
  warp.

- Se puede recentrar el sistema en el mapa manteniendo el botón derecho del
  mouse presionado y moviendo el puntero.
