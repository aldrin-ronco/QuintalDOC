=========================
Ingreso Análisis Líquidos
=========================					

Ubicación
---------

:Módulo:
 Real Q

:Grupo:
 Producto Terminado

:Descripción:
  Ingreso Análisis Líquidos


Introducción
------------

	El ingreso de Análisis líquidos está relacionado con las configuraciones de los parámetros relacionados con los perfiles de análisis. Las variables que usted decida dentro de los análisis para un producto terminado, aquí serán visualizadas.

	Vea `Administración de perfiles <../parametros/act_perfil_x_analisis.html>`_

	Los Análisis líquidos solo se pueden llevar a cabo en el Almacén establecido como "Laboratorio". De igual forma usted tiene habilitada una lista de almacenes para posibles cambios a futuro.

	A diferencia de otras interfaces en este mismo módulo, aquí deberá elegir en la interfaz primera externa el almacén, el producto y el cliente antes de crear un nuevo análisis.

Crear un nuevo Ingreso de Análisis Líquido
-------------------------------------------

	- Ejecute la opción "Ingreso Análisis Líquidos"
	- Elija el almacén "Laboratorio"
	- Escoja el cliente en la lista "seleccione cliente"
	- Haga click en |wznew.bmp|
	- En la ventana emergente verá como título el producto escogido. Introduzca los siguientes datos de registro:
		- Fecha
		- Hora
		- Operario: Debe haber sido creado con antelación
		- Cliente: Aunque viene seleccionado el que usted eligió en el paso 3
	- Los análisis a ingresar se dividen en 2: de Carga Inicial y de Carga final. Puede cambiar de análisis en las pestañas "Análisis carga inicial" y "Análisis carga final"
	- Ambos son configurados en la `Administración de perfiles (de un producto terminado) <../parametros/act_perfil_x_analisis.html>`_
	- El análisis de concentración es importante para el cálculo final del peso del producto. Por esa razón, la solución debe encontrarse entre los parametros correctos de concentración para poder continuar.
	- Despues de ingresar los datos correspondientes a cada análisis, haga click en |save.bmp| *Guardar*
	- Puede guardar una observación referente al análisis en la ventana emergente. Haga click en |btn_ok.bmp| *Aceptar* u oprima F2. Verá el documento relacionado al análisis

Buscar un ingreso de análisis
-----------------------------

	- Ejecute la opción "Ingreso Análisis Líquidos"
	- En la lista "Seleccionar almacén" escoja el almacén donde se encuentran los lotes remitidos
	- En la lista "Seleccione cliente" escoja el cliente al cual realiza el despacho
	- Puede filtrar por periodo de tiempo: Elija Actuales para ver los últimos lotes remitidos; elija Por periodos para poder ingresar una fecha inicio y una fin
	- Seleccione el producto a analisar en la lista
	- En el campo "Filtro por análisis" puede escribir la referencia del análisis, ejemplo: 2170325, para ir directamente al resultado que busca
	- Oprima |btn_ok.bmp| y los análisis cargarán en la grilla

Asociar un análisis a un vehículo
---------------------------------

	- Ejecute la opción "Ingreso Análisis Líquidos"
	- Encuentre el Análisis a agregar al vehículo siguiendo los pasos de: `Buscar un ingreso de análisis`_
	- Una vez localizado el análisis en la grilla de resultados, vaya al final de la fila y haga click en |export1.gif|
	- Seleccione la opción "Asociar vehículo con análisis ####"
	- Verá una ventana emergente con un listado de vehículos/conductores ya asignados previamente; puede buscar el vehículo requerido por la fecha de creación del peso de entrada, por el peso y por el nombre del conductor
	- Haga check en la casilla al final de la fila del vehículo 
	- Presione |save.bmp| *Guardar*

	.. NOTE:

		Puede cambiar el vehículo cuando quiera repitiendo los mismos pasos.









.. |export1.gif| image:: ../../../_images/generales/export1.gif
.. |pdf_logo.gif| image:: ../../../_images/generales/pdf_logo.gif
.. |excel.bmp| image:: ../../../_images/generales/excel.bmp
.. |codbar.png| image:: ../../../_images/generales/codbar.png
.. |printer_q.bmp| image:: ../../../_images/generales/printer_q.bmp
.. |calendaricon.gif| image:: ../../../_images/generales/calendaricon.gif
.. |gear.bmp| image:: ../../../_images/generales/gear.bmp
.. |openfolder.bmp| image:: ../../../_images/generales/openfold.bmp
.. |library_listview.bmp| image:: ../../../_images/generales/library_listview.png
.. |plus.bmp| image:: ../../../_images/generales/plus.bmp
.. |wzedit.bmp| image:: ../../../_images/generales/wzedit.bmp
.. |buscar.bmp| image::../../../_images/generales/buscar.bmp
.. |delete.bmp| image:: ../../../_images/generales/delete.bmp
.. |btn_ok.bmp| image:: ../../../_images/generales/btn_ok.bmp
.. |refresh.bmp| image:: ../../../_images/generales/refresh.bmp
.. |descartar.bmp| image:: ../../../_images/generales/descartar.bmp
.. |save.bmp| image:: ../../../_images/generales/save.bmp
.. |wznew.bmp| image:: ../../../_images/generales/wznew.bmp

	