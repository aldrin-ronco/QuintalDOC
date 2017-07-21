======================================
Registro Análisis Productos en Proceso
======================================

Ubicación
=========

:Módulo:
 Real Q

:Grupo:
 Materia Prima

:Descripción:
	Registro Análisis Productos en Proceso

Introducción
============

	Realice el registro de análisis, en cualquier momento, para los diferentes procedimientos que se llevan a cabo en la creación de un producto. 

	**Por ejemplo:** Registre los resultados del análisis del SubProceso 'Secador' en el Proceso "Molienda", para la creación de Dióxido de Manganeso Natural.

	Para el registro correcto de los análisis, debe tener en cuenta la correcta configuración del producto y de sus procesos.

	En los procesos determinan las propiedades (Encabezados) de un conjunto de análisis combinados. Un proceso puede asociarse a un producto en la pestaña "Otros" para que sea el Análisis final. 

	Un proceso tiene varios subprocesos, los sub-procesos van ligados a un análisis (creado anteriormente) en la Administración de perfiles por Tipo de Análisis en el apartado de Parámetros.

Registrar un análisis
=====================

	- Ejecute la opción "Registro Análisis Productos en Proceso"
	- En la lista "Almacén" seleccione el sitio donde se lleva a cabo el análisis del producto en proceso
	- En la lista "Seleccione producto" elija aquel producto en proceso al cual quiere registrarle un análisis
	- Aparecerá una nueva lista "Seleccione análisis" - Seleccione un proceso (contiene varios subprocesos, ligados cada uno a un análisis)
	- Si el proceso es la Solución en Cubas, vea: `Solución en Cubas`_
	- haga click en |wznew.bmp| *Nuevo*
	-Se desplegará una nueva ventana conformada por un Encabezado (Variables configuradas según el proceso: Operario, Estado de Planta, etc) y un panel más abajo con los Análisis correspondientes a los subprocesos: Alimentación, secador, humedad, etc... divididos en pestañas.
	- Una vez haya completado los campos del encabezado y las variables de los análisis, presione |save.bmp| *Guardar*
	- Inserte una observación acorde al registro, y presione F2 o haga click en |btn_ok.bmp| *Aceptar*

	**Cada análisis tiene un indicador de 'aprobado' o 'Rechazado' individual.**

Solución en Cubas
================= 

	- Siga los pasos en `Registrar un análisis`_ hasta que presione |wznew.bmp| *Nuevo*
	- La ventana para el registro de los análisis por Cubas, le permite registrar Cuba por Cuba los valores obtenidos de: Vol. EDTA, Vol NaOH, y Hierro.
	- Seleccione los terceros apropiados en la lista "Operario" y la lista "Analista"
	- Digite una fecha, y luego una hora para el ingreso
	**Registrar una Cuba**
	1- En el cuadro de texto "Búsqueda de cubas" ubique el cursor haciendo click sobre él y luego presione enter. "Elija una Cuba de la lista"
	2- Aparecerá el código y nombre de la Cuba. A continuación puede llenar los campos: Vol. EDTA, Vol NaOH, y Hierro y presionar el botón |plus.bmp|
	3- Se agregará la Cuba a la lista
	4- Regrese al paso 1 hasta que haya completado todas las Cubas

	- Presione |save.bmp| *Guardar*

















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