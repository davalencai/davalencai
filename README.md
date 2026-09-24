# Diego Valencia

Soy Diego, ingeniero informático de Apartadó. Trabajo como auxiliar de sistemas y la
mayor parte del tiempo la paso construyendo herramientas para que la gente de la
empresa deje de hacer a mano lo que puede hacer un programa.

Casi todo mi código está en repositorios privados de la empresa, por eso aquí se ve
poco. Esto es lo que he hecho:

**El Liquidador.** Una aplicación web para calcular y enviar los pagos a los
productores. Antes funcionaba con varios archivos de Excel: unas macros traían parte
de la información, otra persona la completaba a mano, y así cada liquidación tomaba
más de 5 horas. Ahora todo sale del mismo sistema en minutos. También genera los
reportes para la DIAN, que pasaron de una o dos horas a un par de minutos.
Hecha con Vue, Node.js, Express y MySQL.

**Revisión de calidad con IA.** Un sistema de visión artificial que corre en una
Raspberry Pi dentro de la empacadora, con acceso remoto. Funciona en tres pasos, cada
uno con su propio modelo:
1. Detecta cuándo la bandeja está completa y en buena posición, y toma la foto.
2. Segmenta cada clúster de banano en la imagen y lo recorta por separado.
3. Revisa cada recorte para detectar posibles defectos en la fruta. Este último
   todavía está en desarrollo.

**Básculas.** Las básculas de racimo y de bandeja de la planta dependen de la
plataforma de un proveedor. Para no depender de eso, estamos migrando: ya me conecté
al gateway de las básculas y saqué la información con los endpoints que exponen, y
ahora estoy diseñando el hardware de una báscula propia que envíe los datos directo a
nuestra aplicación. La idea es tener control total sobre la información, sin
intermediarios.

**El punto de venta de mi familia.** Lo hice dos veces. La primera en Java, de
escritorio. La segunda en web y luego la pasé a Android para usarla en una tablet.
La impresora de tickets no funcionaba, así que me tocó hacer un plugin propio.
Fue lo que más me costó.

Contacto: diegoalejandrovalencialopera@gmail.com
