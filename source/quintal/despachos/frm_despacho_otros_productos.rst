============================================
Administración despacho para otros productos
============================================


Ubicación
---------

:Módulo:
 Real Q

:Grupo:
 Despachos

:Descripción:
  Administración despacho para otros productos


Introducción
============

	Use esta interfaz para registrar la entrada y salida de productos que no hacen parte del sistema.

Buscar un registro
------------------

	- Ejecute la opción *Administración despacho para otros productos*
	- Selección en la lista 'Seleccione Almacén' el Almacén donde se dio el registro.
	- Elija un periodo marcando la opción 'Por periodos' o marque 'Actuales' Para ver los despachos o ingresos que aún no han sido terminados
	- Haga click en |btn_ok.bmp| para ejecutar la búsqueda

	.. NOTE::

		Puede hacer una búsqueda directa si posee el número de referencia del registro usando la casilla de texto: "Filtrar por # ingreso"

Registrar una Entrada de producto
=================================

Registrar ingreso de vehículo con producto
------------------------------------------

	- Ejecute la opción *Administración despacho para otros productos*
	- En la lista "Seleccione almacén" escoja el almacén donde hará la entrada o la salida de producto
	- En la lista "Seleccione el tipo pesaje" puede elegir si el producto está entrando o saliendo
	- Haga click en |wznew.bmp| 
		      .. figure:: images/despaotros/3.jpg
           				 :align: center

	- Seleccione un conductor de la lista haciendo click en el botón |find.bmp|. Si no tiene el conductor guardado, llene los datos correspondientes (nombres y apellidos) y quedará guardado de manera automática al finalizar este proceso.
	- Escriba la placa del vehículo de transporte (tres letras - tres números)
	- Seleccione una transportadora en la lista o agréguela haciendo click en el botón |plus.bmp|. Siga las instrucciones de `Crear transportadora <../parametros/act_transportadoras.html#crear-una-transportadora>`_
	- Si el caso es el de tener una rampa/báscula conectada al sistema, verifique que el peso marcado en "Peso Entrada" es coherente. Si desea marcarlo manualmente, haga click en "Capturar peso manual" (Debe tener el permiso necesario). El sistema pedirá una contraseña, introduzcala y proceda a marcar el peso
	- En el cuadro de texto inferior puede hacer alguna observación pertinente
	- Presione |save.bmp| *Guardar* o F2



Registrar una salida de vehículo vacío
--------------------------------------
	
	- Ejecute la opción *Administración despacho para otros productos*
	- Realice una búsqueda de la entrada en peso. `Buscar un registro`_
	- Localice el despacho en la grilla, y al final de la fila presione |export1.gif|. Seleccione la opción "Registro de Salida"
	- Escoja la origen del producto: Cliente, Traslado, Libre
		- **Cliente:** Elija un cliente como destino del vehículo - `Crear un cliente </parametros/act_clientes_pos.html#crear-un-cliente>`_
		- **Traslado:** Se usa para trasladar entre almacenes de la misma empresa, el almacén debe haber sido establecido como destino en: `Configuración de destinos <../parametros/act_destinos.html#agregar-un-nuevo-destino>`_
		- **Libre:** Puede poner una descripción libre del destino
	- Puede seleccionar varios productos para sumar el peso total de la báscula. Se usa para llevar un control simple. En la lista "Seleccione el producto a despachar" escoja el producto, seleccione la cantidad en Kg y pulse |plus.bmp|. Se agrega a la grilla
	- Repita hasta haber completado la lista de productos
	- Si el caso es el de tener una rampa/báscula conectada al sistema, verifique que el peso marcado en "Peso Salida" es coherente. Si desea marcarlo manualmente, haga click en "Capturar peso manual" (Debe tener el permiso necesario). El sistema pedirá una contraseña, introduzcala y proceda a marcar el peso
	- En el cuadro de texto inferior puede hacer alguna observación pertinente
	- Presione |save.bmp| *Guardar* o F2

Registrar una Salida de producto
================================

Registrar una entrada de vehículo vacío
---------------------------------------


	- Ejecute la opción *Administración despacho para otros productos*
	- En la lista "Seleccione almacén" escoja el almacén donde hará la entrada o la salida de producto
	- En la lista "Seleccione el tipo pesaje", elija: Producto Saliendo
	- Haga click en |wznew.bmp| 
		      .. figure:: images/despaotros/1.jpg
           				 :align: center
	- Seleccione un conductor de la lista haciendo click en el botón |find.bmp|. Si no tiene el conductor guardado, llene los datos correspondientes (nombres y apellidos) y quedará guardado de manera automática al finalizar este proceso.
	- Escriba la placa del vehículo de transporte (tres letras - tres números)
	- Seleccione una transportadora en la lista o agréguela haciendo click en el botón |plus.bmp|. Siga las instrucciones de `Crear transportadora <../parametros/act_transportadoras.html#crear-una-transportadora>`_
	- Si el caso es el de tener una rampa/báscula conectada al sistema, verifique que el peso marcado en "Peso Salida" es coherente. Si desea marcarlo manualmente, haga click en "Capturar peso manual" (Debe tener el permiso necesario). El sistema pedirá una contraseña, introduzcala y proceda a marcar el peso
	- En el cuadro de texto inferior puede hacer alguna observación pertinente
	- Presione |save.bmp| *Guardar* o F2

	


Registrar salida de vehículo con producto
-----------------------------------------

	- Ejecute la opción *Administración despacho para otros productos*
	- Realice una búsqueda de la entrada en peso. `Buscar un registro`_
	- Localice el despacho en la grilla, y al final de la fila presione |export1.gif|. Seleccione la opción "Registro de Salida"
		      .. figure:: images/despaotros/2.jpg
           				 :align: center
	- Escoja la destino del producto: Cliente, Traslado, Libre
		- **Cliente:** Elija un cliente como destino del vehículo - `Crear un cliente </parametros/act_clientes_pos.html#crear-un-cliente>`_
		- **Traslado:** Se usa para trasladar entre almacenes de la misma empresa, el almacén debe haber sido establecido como destino en: `Configuración de destinos <../parametros/act_destinos.html#agregar-un-nuevo-destino>`_
		- **Libre:** Puede poner una descripción libre del destino
	- Puede seleccionar varios productos para sumar el peso total de la báscula. Se usa para llevar un control simple. En la lista "Seleccione el producto a despachar" escoja el producto, seleccione la cantidad en Kg y pulse |plus.bmp|. Se agrega a la grilla
	- Repita hasta haber completado la lista de productos
	- Si el caso es el de tener una rampa/báscula conectada al sistema, verifique que el peso marcado en "Peso Entrada" es coherente. Si desea marcarlo manualmente, haga click en "Capturar peso manual" (Debe tener el permiso necesario). El sistema pedirá una contraseña, introduzcala y proceda a marcar el peso
	- En el cuadro de texto inferior puede hacer alguna observación pertinente
	- Presione |save.bmp| *Guardar* o F2








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
.. |find.bmp| image:: ../../../_images/generales/find.bmp
