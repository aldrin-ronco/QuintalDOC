=========================================
Administración Despacho Productos Sólidos
=========================================

Ubicación
---------

:Módulo:
 Real Q

:Grupo:
 Despachos

:Descripción:
  Administración Despacho Productos Sólidos


Introducción
------------

	Una vez hecha la selección de Lotes para el despacho, debe ingresar la información referente a la salida del camión. Este despacho se logra adquiriendo el peso del camión antes y después de montar la mercancía. 

	Existen dos formas de obtener el peso del camión de transporte: automática y manual. La forma automática se logra conectando la báscula a la red local; el sistema está escuchando un ingreso constantemente. En la forma manual, es el usuario quien introduce el peso de entrada del camión y el de salida.

	Para poder introducir datos manualmente necesita los permisos adecuados. Diríjase al administrador del sistema.

Pre - requisitos
----------------

	- Haber creado la `selección de lotes (Paso 2) <../despachos/frm_seleccion_lotes_despacho.html>`_

Crear un nuevo despacho - Entrada
---------------------------------
	
	- Ejecute la opción "Administración Despacho Productos Sólidos"
	- Haga aclick en el botón |wznew.bmp|
	- Selección en la lista 'Seleccione Almacén' el Almacén de donde sale el despacho
	- Seleccione un conductor de la lista haciendo click en el botón |find.bmp|. Si no tiene el conductor guardado, llene los datos correspondientes (nombres y apellidos) y quedará guardado de manera automática al finalizar este proceso.
	- Escriba la placa del vehículo de transporte (tres letras - tres números)
	- Seleccione una transportadora en la lista o agréguela haciendo click en el botón |plus.bmp|. Siga las instrucciones de `Crear transportadora <../parametros/act_transportadoras.html#crear-una-transportadora>`_
	- Si el caso es el de tener una rampa/báscula conectada al sistema, verifique que el peso marcado en "Peso Entrada" es coherente. Si desea marcarlo manualmente, haga click en "Capturar peso manual" (Debe tener el permiso necesario). El sistema pedirá una contraseña, introduzcala y proceda a marcar el peso
	- En el cuadro de texto inferior puede hacer alguna observación pertinente
	- Presione |save.bmp| *Guardar* o F2
		      .. figure:: images/despasolidos/1.jpg
           				 :align: center


Buscar un despacho
------------------

	- Ejecute la opción "Administración Despacho Productos Sólidos"
	- Selección en la lista 'Seleccione Almacén' el Almacén de donde sale el despacho.
	- Seleccione un cliente de la lista - Opcional
	- Seleccione un producto - Opcional
	- Elija un periodo marcando la opción 'Por periodos' o marque 'Actuales' Para ver los despachos que aún no han sido terminados
	- Haga click en |btn_ok.bmp| para ejecutar la búsqueda

Registrar una salida en el despacho
-----------------------------------
	
	- Ejecute la opción "Administración Despacho Productos Sólidos"
	- Realice una búsqueda del despacho al que ya realizó una entrada en peso. `Buscar un despacho`_
	- Localice el despacho en la grilla, y al final de la fila presione |export1.gif|. Seleccione la opción "Registro de Salida"

	      .. figure:: images/despasolidos/2a.jpg
            		:align: center


	- Introduzca la referencia del Predespacho en la casila "Predespacho No"
	- En la lista "Seleccione el producto a despachar" escoja el producto.
	- En la lista "Seleccione Contenedor" escoja el número de contenedor al que le hará registro de salida. 
	- Si el caso es el de tener una rampa/báscula conectada al sistema, verifique que el peso marcado en "Peso Salida" es coherente. Si desea marcarlo manualmente, haga click en "Capturar peso manual" (Debe tener el permiso necesario). El sistema pedirá una contraseña, introduzcala y proceda a marcar el peso
	- Revise que el tercer digito: Peso Materia Prima, coincida con el peso requerido por el cliente
	- En el cuadro de texto inferior puede hacer alguna observación pertinente
	- Presione |save.bmp| *Guardar* o F2

	      .. figure:: images/despasolidos/2b.jpg
           		 :align: center
  
** Tiquete de báscula:***

 	      .. figure:: images/despasolidos/2c.jpg
              	  :align: center



Anular un despacho/ingreso de vehículo
--------------------------------------

Al anular un ingreso de vehículo se inhabilita el proceso, pero se deja registro del ingreso para poder consultarlo más adelante.

	- Ejecute la opción "Administración Despacho Productos Sólidos"
	- Realice una búsqueda del despacho al que ya realizó una entrada en peso. `Buscar un despacho`_
	- Localice el despacho en la grilla, y al final de la fila presione |export1.gif|. Seleccione la opción "Anular ingreso de vehículo"
		      .. figure:: images/despasolidos/3.jpg
           				 :align: center

Eliminar un despacho/ingreso de vehículo
--------------------------------------

Al eliminar un ingreso, no se deja registro alguno. El consecutivo de los registros no se retrocede: si elimina el registro 17, su próximo registro NO tomará ese luhar sino más bien el siguiente: 18.

	- Ejecute la opción "Administración Despacho Productos Sólidos"
	- Realice una búsqueda del despacho al que ya realizó una entrada en peso. `Buscar un despacho`_
	- Localice el despacho en la grilla, y al final de la fila presione |export1.gif|. Seleccione la opción "Eliminar ingreso de vehículo"

		      .. figure:: images/despasolidos/4.jpg
           				 :align: center


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