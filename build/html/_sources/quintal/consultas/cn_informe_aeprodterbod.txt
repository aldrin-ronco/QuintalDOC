==============================================================
Consulta aprobación y entrega de productos terminados a bodega
==============================================================

Ubicación
---------

:Módulo:
 Real Q

:Grupo:
 Consultas

:Descripción:
  Consulta aprobación y entrega de productos terminados a bodega


Introducción
------------

	Aquí puede obtener una "hoja de producción" que le permitirá conocer los productos sólidos que han sido terminados y están disponibles para despacho.

	Además, en esta interfaz podrá `imprimir rótulos`_ para las estíbas.

	
Casos de Uso
------------
	
	Usted podrá remitirse a este informe para:

		- Conocer el peso, la pureza, el lote, la fecha y el usuario de un producto disponible.


Filtros aplicables
------------------
Podrá filtrar la información por:

	- Almacén
	- Producto
	- Proceso
	- Rango de fechas
	- Lote
	- Presentación
	- Calidad

Opciones de salida
------------------

	- |printer_q.bmp| Impresión

      .. figure:: images/13.jpg
            :align: center


Imprimir Rótulos
----------------

	- Para imprimir los rótulos deberá tener presente el lote que desea identificar. 
	- Deberá además llenar TODOS los filtros disponibles.
	- Cada lote cuenta con cierta cantidad de bolsas de x peso.
	- Cada producto está configurado para que sus estibas llevén un peso máximo x.
	- Al momento de hacer la rotulación se dividirá: El Peso Estiba/Número de bolsas/Peso de cada bolsa. Para sacar una etiqueta por estiba.


      .. figure:: images/13b.jpg
            :align: center


	Información en la etiqueta:

		- Producto
		- Calidad
		- Lote
		- Sacos
		- Peso total
		- Concentración
		- Fecha
		- Analista

Ejemplo:

	Un Lote ### de 50 sacos de 50kg cada uno. El producto X, está configurado para 1000 kg por estiba.
	El resultado serán 3 Etiquetas con la siguiente información:

	Etiqueta 1:

	- Producto X
	- Lote ###
	- Sacos: 20
	- Peso: 1000Kg

	Etiqueta 2:
	
	- Producto X
	- Lote ###
	- Sacos: 20
	- Peso: 1000Kg

	Etiqueta 3:
	
	- Producto X
	- Lote ###
	- Sacos: 10
	- Peso: 500Kg

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