=====================================================
Ingreso de producción / Orden de revisión de calidad
=====================================================

Ubicación
---------

:Módulo:
 Real Q

:Grupo:
 Producto Terminado

:Descripción:
 	Ingreso de producción empacada temporal


Introducción
------------

	Registre el ingreso de todos los productos terminados que NO vengan detallados en Lotes. Los productos que no son detallados en lotes, tienen la opción "detallado en lotes" desmarcada en la configuración avanzada de producto.

	Los productos ingresados en este apartado son despachados como producto sólido. 

	La configuración de 'Calidad' y 'Presentaciones' del producto en su configuración avanzada es sumamente importante para el correcto proceder de los análisis; un producto puede tener diferentes análisis según su presentación, el cliente y su calidad. Por defecto el cliente seleccionado es 'Cuantias Menores'. 

	Puede ingresar varias presentaciones de producto. Al guardar, verá las presnetaciones divididas en ingresos diferentes con el mismo código de referencia. Al momento de proceder a resgistrar el análisis selecciona la calidad.

Realizar un ingreso/orden
=========================

	- Ejecute la opción *Ingreso de producción empacada temporal*
	- Haga click en |wznew.bmp| 
	- Seleccione el Almacén
	- Digite la fecha de ingreso
	- Escoja un cliente de la lista
	- Haga clic en el campo de texto "Búsqueda de productos" y presione Enter. Verá la lista de productos desplegada. Haga click sobre el producto a ingresar y presione Enter
	- El cursor se sitúa en "Cant. Saco". Digite la cantidad entrante y presione Enter
	- En la lista "Presentación" escoja la forma de ingreso del producto
	- Haga click en |plus.bmp|. EL producto se agrega a la grilla
	- El cursor se sitúa de nuevo en "Búsqueda de productos", repita el procedimiento si hay más productos o presentaciones en este ingreso
	- Cuando haya acabado de ingresar productos o presnetaciones, puede ingresar una observación oportuna en el campo de texto inferior
	- Haga click en |save.bmp| *Guardar*
	- Pulse "Sí" en la ventana de confirmación

Buscar un ingreso/orden
=========================

	- Ejecute la opción *Ingreso de producción empacada temporal*
	- Seleccione el Almacén
	- La casilla de verificación "Orden vigente" y "Por periodos" permite que la búsqueda muestre solo aquellos ingresos sin un registro de análisis. 
	- Seleccione un cliente de la lista
	- Presione |btn_ok.bmp| para ejecutar la búsqueda

Ejecutar/Registrar un análisis para una orden
=============================================
	
	- `Buscar un ingreso/orden`_
	- En los resultados de la grilla, escoja el ingreso al que le hará el análisis. Al final del registro, haga click en |export1.gif|
	- En el menú desplegado haga clic en "Ejecutar análisis ######"
	- Vera una ventana con la presentación ya seleccionada y donde puede elegir la "Calidad". Presione *Continuar*
	- Vera la pantalla de registro de análisis. Digite la fecha 
	- Los análisis a ingresar se dividen en 2: de Carga Inicial y de Carga final. Puede cambiar de análisis en las pestañas "Análisis previo" y "Análisis de final"
	- Ambos son configurados en la `Administración de perfiles (de un producto terminado) <../parametros/act_perfil_x_analisis.html>`_
	- El análisis de concentración es importante para el cálculo final del peso del producto. Por esa razón, la solución debe encontrarse entre los parametros correctos de concentración para poder continuar.
	- Despues de ingresar los datos correspondientes a cada análisis, haga click en |save.bmp| *Guardar*
	- Escriba una Observación en la pantalla emergente y presione F2, o haga click en |btn_ok.bmp| *Aceptar*
