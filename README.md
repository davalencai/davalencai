# Diego Valencia

Soy Diego, ingeniero informático de Apartadó. Trabajo como auxiliar de sistemas y la
mayor parte del tiempo la paso construyendo herramientas para que la gente de la
empresa deje de hacer a mano lo que puede hacer un programa.

Casi todo mi código está en repositorios privados de la empresa, por eso aquí se ve
poco. Esto es lo que he hecho:

**El Liquidador.** Una aplicación web que genera las liquidaciones de los
productores: el informe de lo que la exportadora les va a pagar por la fruta. Con
ese informe cada productor emite su factura electrónica a la empresa. Antes esto se
hacía con varios archivos de Excel: unas macros traían parte de la información, otra
persona la completaba a mano, y sacar todas las liquidaciones tomaba entre 5 y 6
horas. Ahora se generan y se envían por correo desde el mismo sistema en minutos.
También genera los reportes para la DIAN, que pasaron de una o dos horas a un par de
minutos. Fue mi trabajo de grado, así que quedó documentado de principio a fin:
objetivos, requisitos, historias de usuario, manual de despliegue entre otras.
Hecha con Vue, Node.js, Express y MySQL.

**Revisión de calidad con IA.** Un sistema de visión artificial que corre en una
Raspberry Pi dentro de la empacadora, con acceso remoto. Funciona en tres pasos, cada
uno con su propio modelo:
1. Detecta cuándo la bandeja está completa y en buena posición, y toma la foto.
2. Segmenta cada clúster de banano en la imagen y lo recorta por separado.
3. Revisa cada recorte para detectar posibles defectos en la fruta. Este último
   todavía está en desarrollo.

**Básculas.** Las básculas de racimo y de bandeja de las fincas dependen de la
plataforma de un proveedor. Para no depender de eso, estamos migrando. Primero me
conecté al gateway de las básculas: un servicio que corre en otro computador de la
misma red consulta los endpoints cada cierto tiempo y sube la información a nuestra
base de datos. Sobre esos datos hice una aplicación web donde cada usuario ve solo
la información de las fincas que tiene asignadas. La comunicación también va en el
otro sentido: desde la aplicación se crean los tipos de embarque, que aparecen en la
báscula para que el pesaje se haga con el embarque correcto.

El siguiente paso es tener una báscula propia: ya tengo pensado el montaje con una
celda de carga, un amplificador HX711, una Raspberry Pi y batería, y pedí los
componentes para armarla, programarla y conectarla a la aplicación. La idea es tener
control total sobre la información, sin intermediarios.

**El punto de venta de mi familia.** Lo hice dos veces. La primera en Java, de
escritorio. La segunda en web y luego la pasé a Android para usarla en una tablet.

Contacto: [diegoalejandrovalencialopera@gmail.com](mailto:diegoalejandrovalencialopera@gmail.com)
