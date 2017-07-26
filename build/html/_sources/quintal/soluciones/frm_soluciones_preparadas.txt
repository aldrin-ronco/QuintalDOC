============================================
Registro y consulta de Soluciones preparadas
============================================

Ubicación
---------

:Módulo:
 Real Q

:Grupo:
 Soluciones

:Descripción:
	Registro de resultados en soluciones preparadas


Introducción
------------

	En esta interfaz podrá registrar los resultados obtenidos durante la preparación de las soluciones. Consulte los resultados usando los filtros necesarios.

	Realice la consulta tomando en cuenta:
		- Almacén
		- Analista
		- Solución
		- Período

	En el registro podrá guardar los resultados de un muestreo y obtener automáticamente datos como la variación y el promedio.

Consultar una Solución
----------------------
	
	- Ejecute la opción *Registro de resultados en soluciones preparadas*
	- Seleccione en la lista 'Consulta por almacén' el lugar del cual provienen los datos suministrados
	- Escoja en la lista 'Consulta por analista' al analista encargado de preparar la solución
	- Escoja en la lista 'Seleccione Solución' la Solución muestreada.
	- En la parte superior puede seleccionar el periodo, o la opción 'actual' para consultar solo el día de hoy.
	- Haga click en |btn_ok.bmp| para consultar los registros.

Registrar una Solución
----------------------

	- Ejecute la opción "Registro de resultados en soluciones preparadas"
	- Escoja en la lista 'Seleccione Solución' la Solución a la que se le hará registro de muestras
	- Haga click en el botón |wznew.bmp| *Nuevo*
	- En la nueva interfaz seleccione el 'Almacén' del que provienen las muestras
	- Ingrese la fecha del muestreo
	- Si la solución está Estandarizada
		- Ingrese el volumen
		- En el campo 'Muestras' digite el número de muestras en mano
		- En la grilla 'Concentración' ingrese la concentración para cada una de las muestras
	- Si la solución NO está estandarizada
		- Ingrese el volumen
	- Haga click en |save.bmp| *Guardar*
	
	.. NOTE:

		Una solución es estandarizada cuando existe un proceso de escrito desde la definición de su protocolo en la pestaña de 'estandarización', vea: `Estandarización <../soluciones/frm_protocolo_solucion_list.html#estandarizacion>`_



Imprimir/Modificar/Anular una solución
--------------------------------------

	- Ejecute la opción "Registro de resultados en soluciones preparadas"
	- Realice la consulta necesaria para encontrar la solución que busca `Consultar una Solución`_
	- En la grilla de resultados de la búsqueda, haga click en el botón |export1.gif| al final de la fila de la solución
	- Allí podrá escoger entre: Modificar, anular o imprimir la solución
		- Modificar: Si escoje esta opción, verá una ventana similar a la de `Registrar una Solución`_, puede modificar los campos que considere necesarios
		- Anular: La anulación no es una eliminación completa, deja un registro de quién y porqué. Introduzca en la ventana una fecha de anulación y presione |btn_ok.bmp|. Aparecerá un cuadro de texto donde podrá indicar los motivos de la anulación.
		- Imprimir: Se creará un documento imprimible, con los datos del registro de solución.

Exportar a Excel el resultado de una consulta
---------------------------------------------

	- Ejecute la opción "Registro de resultados en soluciones preparadas"
	- Realice la consulta necesaria para encontrar la solución que busca `Consultar una Solución`_
	- Haga click en el botón |excel.bmp| para crear y abrir un documento en excel con los resultados de la búsqueda, detallando información interna de las soluciones.

	






.. |export1.gif| image:: ../../../_images/generales/export1.gif
.. |pdf_logo.gif| image:: ../../../_images/generales/pdf_logo.gif
.. |excel.bmp| image:: ../../../_images/generales/excel.bmp
.. |codbar.png| image:: ../../../_images/generales/codbar.png
.. |printer_q.bmp| image:: ../../../_images/generales/printer_q.bmp
.. |calendaricon.gif| image:: ../../../_images/generales/calendaricon.gif
.. |gear.bmp| image:: ../../../_images/generales/gear.bmp
.. |openfolder.bmp| image:: ../../../_images/generales/openfold.bmp
.. |library_listview.png| image:: ../../../_images/generales/library_listview.png
.. |plus.bmp| image:: ../../../_images/generales/plus.bmp
.. |wzedit.bmp| image:: ../../../_images/generales/wzedit.bmp
.. |find.bmp| image::../../../_images/generales/find.bmp
.. |delete.bmp| image:: ../../../_images/generales/delete.bmp
.. |btn_ok.bmp| image:: ../../../_images/generales/btn_ok.bmp
.. |refresh.bmp| image:: ../../../_images/generales/refresh.bmp
.. |descartar.bmp| image:: ../../../_images/generales/descartar.bmp
.. |save.bmp| image:: ../../../_images/generales/save.bmp
.. |wznew.bmp| image:: ../../../_images/generales/wznew.bmp
.. |find.bmp| image:: ../../../_images/generales/find.bmp