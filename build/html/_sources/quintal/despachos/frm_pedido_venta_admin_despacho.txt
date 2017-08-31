========================
Programación de despacho
========================

Ubicación
---------

:Módulo:
 Real Q

:Grupo:
 Despachos

:Descripción:
  Programación de despacho


Introducción
------------

La programación para un despacho es el primer paso a seguir para realizar el despacho de mercancía. 

Pre - requisitos
----------------

	- Tener una orden de compra a la mano (nacional o internacional)
	- Haber creado un Container
	- Tener un almacen del cual saldrá la mercancía

Crear una programación de despacho
----------------------------------

	- Ejecute la opción *Programación de despacho*
	- Haga click en |wznew.bmp| *Nuevo*


      			.. figure:: images/programacion/0.jpg
           			 :align: center

	- En la lista 'Almacén' seleccione el almacen del cual sale la mercancía
	- Busque un cliente |find.bmp| seleccionandolo de la lista, o agréguelo |plus.bmp|, vea `Crear cliente <../parametros/act_clientes_pos.html#crear-un-cliente>`_
	- Puede cambiar la fecha de la programación, por defecto aparece la fecha actual
	- Introduzca la orden de compra internacional PO (Purchase Order) - Si la tiene
	- Introduzca la orden de compra nacional, del cliente directo - Si la tiene. El sistema le dejará hacer la programación con tan solo una de las dos ordenes, o las 2.

      			.. figure:: images/programacion/1.jpg
           			 :align: center

	- En el campo de texto 'Búsqueda de productos' haga click y presione Enter. En la lista desplegada de productos, haga click sobre uno y presione Enter
	- En la 'Unidad de medida' ecoja de la lista la adecuada (kg, toneladas, unidades). Si selecciona 'unidades' en el siguiente campo seleccione la presentación, ejemplo: bolsa de 10kg
	- El campo 'Existencias' muestra la cantidad de producto existente según la unidad seleccionada. Seleccione en el campo 'Cantidad' la cantidad de producto según la unidad elegida.

		.. NOTE::

			Es muy importante tener en cuenta la presentación del producto a la hora de elegir el peso del producto en Kilos o Toneladas. La cantidad debe poder coincidir con un número entero de presentaciones del producto, por ejemplo: Si el producto tiene una única presnetacion de 1250 Kg, entonces la cantidad no podrá ser 1 tonelada o 1300 Kg, sino más bien 1.25 toneladas o 1250 kg. De lo contrario, no podrá elegir los lotes para el despacho en el siguiente paso.

	- A continuación seleccione la cantidad de Containers en los que el producto será despachado. Un container es un recipiente con una capacidad limitada. Puede elegir la cantidad de containers que desee. `Para crear un Container <../parametros/act_lab_contenedores.html>`_
	- Seleccione ahora el tipo de container adecuado. Deberám coincidir la capacidad del container con la cantidad de producto seleccionada.
	- Pulse |plus.bmp|

      			.. figure:: images/programacion/1b.jpg
           				 :align: center

	- Ahora que el producto está en la lista, puede proceder a guardar la programación de despacho haciendo click en |save.bmp| *Guardar*

	.. NOTE::

		Puede eliminar productos de la lista haciendo click sobre el nombre en la grilla y presionando Supr

Buscar una programación
-----------------------

	- Ejecute la opción *Programación de despachos*
	- En la primera lista, seleccione el almacén donde realizó la programación
	- Si desea un cliente en particular, puede buscarlo en la lista <<Clientes>>, si no, se mostrarán las programaciones de todos.
	- Puede seleccionar la opción 'Pedidos Vigentes' que mostrará todos los despachos que aún no han sido culminados. También puede buscar 'Por períodos', seleccionado la fecha de inicio y la fecha fin.
	- Haga click en |btn_ok.bmp| para aplicar los filtros y realizar la búsqueda.



Modificar una programación
--------------------------

	 - Realice el proceso de búsqueda para encontrar la programación a modificar, vea `Buscar una programación`_
	 - Al final de la fila de la programación en la grilla, haga click en |export1.gif|
	 - Escoja la opción |wzedit.bmp| *Modificar programación de despacho ####*
	 - A continuación, proceda a modificar los datos de la programación. Si tiene dudas sobre los campos requeridos, vea `crear una programación de despacho`_
	 - Al finalizar los cambios presione |save.bmp| *Guardar*

	      .. figure:: images/programacion/2.jpg
            		:align: center

Anular una programación
-----------------------

	 - Realice el proceso de búsqueda para encontrar la programación a modificar, vea `Buscar una programación`_
	 - Al final de la fila de la programación en la grilla, haga click en |export1.gif|
	 - Escoja la opción |delete.bmp| *Anular programación de despacho ####*. La anulación no elimina la programación, más bien la inhabilita y la señala como 'Anulada'
	 - En la ventana emergente, escriba las razones por las cuales decidió anular la programación y presione |btn_ok.bmp| *Aceptar* o F2 en el teclado.


	      .. figure:: images/programacion/3.jpg
            			:align: center

Imprimir una programación
-------------------------

	 - Realice el proceso de búsqueda para encontrar la programación a modificar, vea `Buscar una programación`_
	 - Al final de la fila de la programación en la grilla, haga click en |export1.gif|
	 - Escoja la opción |printer_q.bmp| *Imprimir programación de despacho #####*


	      .. figure:: images/programacion/4.jpg
           			 :align: center

Imprimir una selección de lotes
-------------------------------

	 - Realice el proceso de búsqueda para encontrar la programación a modificar, vea `Buscar una programación`_
	 - Al final de la fila de la programación en la grilla, haga click en |export1.gif|
	 - Escoja la opción |printer_q.bmp| *Imprimir selección de lotes #####*

	 La impresión de la selección de lotes, contiene la misma información que la programación, pero muestra los sacos que se llevarán al container en el orden establecido cuando se hizo la selección.








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

	