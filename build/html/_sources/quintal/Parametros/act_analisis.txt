===================================
Administración de tipos de Análisis
===================================

Ubicación
---------

:Módulo:
 Real Q

:Grupo:
 Parámetros

:Descripción:
  Administración de tipos de Análisis

Introducción
============
	
	Use está interfaz para definir los tipos de análisis que estarán disponibles para los productos/procesos. Agrupe de manera funcional los análisis, ejemplo: puede agrupar todos los análisis hechos sobre las bolsas de empaque en una carpeta llamada 'Empaque'. También, describa características importantes sobre ellos, como: Unidad de medida, traducción al ingles y número de decimales.

	La administración de análisis por tipo, es el primer paso para la administración general de los análisis en este sistema. Sea cuidadoso de elegir los análisis correctos para cada tipo de proceso o producto, para luego ubicarlos correctamente en la administración de los perfiles.

	Todas las agrupaciones que decide crear en esta interfaz, son reflejadas también en la administración de perfiles. 

	Arbol:

	- Tipo de Análisis
		- Análisis

			.. figure:: images/analisis/0.jpg
 						:align: center

Crear un tipo de Análisis
-------------------------

	- Ejecute la opción *Administración de tipos de análisis*
	- En cualquier lugar vacío de la ventana desplegada haga click derecho. 
	- Haga click en |wznew.bmp| *Nuevo tipo de análisis*
			.. figure:: images/analisis/1.jpg
 						:align: center
	- Verá crearse un nuevo folder en la lista donde podrá introducir el nombre del tipo. Ejemplo: Materia Prima (aquí se agruparán todos los análisis necesarios para certificar la materia prima)

Cambiar Nombre a un tipo de Análisis
------------------------------------

	- Ejecute la opción *Administración de tipos de análisis*
	- Haga click derecho en el tipo de análisis cuyo nombre desea modificar
	- Escoja la opción |wzedit.bmp| *Cambiar nombre a [nombre de tipo]*
			.. figure:: images/analisis/2.jpg
 						:align: center
	- Digite el nuevo nombre y presione Enter

Eliminar un tipo de Análisis
----------------------------

	- Ejecute la opción *Administración de tipos de análisis*
	- Haga click derecho en el tipo de análisis que desea eliminar
	- Elija la opción |delete.bmp| *Eliminar tipo Análisis [Nombre de tipo]*
			.. figure:: images/analisis/3.jpg
 						:align: center
	- En la ventana de confirmación pulse 'sí'

Agregar un análisis a un tipo 
-----------------------------

	- Ejecute la opción *Administración de tipos de análisis*
	- Haga click derecho sobre el tipo al que agregará un análisis
	- Elija la opción |wznew.bmp| *Nuevo análisis en [Nombre de tipo]*
			.. figure:: images/analisis/4.jpg
 						:align: center
	- Se agregarà un nuevo Análisis bajo el ícono del Tipo, digite el nombre del Análisis y presione Enter

Modificar propiedades del Análisis
----------------------------------
	
	- Ejecute la opción *Administración de tipos de análisis*
	- Haga click derecho en el análisis cuyas propiedades va a establecer
	- Escoja la opción |wzedit.bmp| *Modificar propiedades Análisis [nombre de Análisis]*
			.. figure:: images/analisis/5.jpg
 						:align: center
	- A continuación podrá digitar las siguientes propiedades:
		- Nombre del Análisis
		- Método de realización, ejemplo: Medición
		- Nombre del Análisis [En], nombre en ingles
		- Método de realización [En], Método en ingles
		- Unidad del Análisis, ejemplo: m (metros), kg (kilogramos), % (porcentaje)...
		- Decimales a mostrar en reportes - Establezca el nñumero de decimales a mostrar en el reporte, ejemplo: Decimales: 2 = "1,54"
			- Líquido
			- Sólido
		- En la parte inferior encuentra una opción de reemplazo para suplantar en los reportes los valores menores a 1 en los análisis a Sólidos o Líquidos por "<1".
	- Pusle |save.bmp| *Guardar*


Cambiar Nombre de Análisis
--------------------------

	- Ejecute la opción *Administración de tipos de análisis*
	- Haga click derecho en el análisis cuyo nombre desea modificar
	- Escoja la opción |wzedit.bmp| *Cambiar nombre Análisis [nombre de Análisis]*
			.. figure:: images/analisis/6.jpg
 						:align: center
	- Digite el nuevo nombre y presione Enter

Eliminar un Análisis
--------------------

	- Ejecute la opción *Administración de tipos de análisis*
	- Haga click derecho en el análisis que desea eliminar
	- Elija la opción |delete.bmp| *Eliminar Análisis [Nombre de Análisis]*
			.. figure:: images/analisis/7.jpg
 						:align: center
	- En la ventana de confirmación pulse 'sí'

	--------------------------------------------


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