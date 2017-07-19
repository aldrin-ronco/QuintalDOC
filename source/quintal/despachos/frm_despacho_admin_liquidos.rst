=========================================
Administración Despacho Productos Líquidos
=========================================

Ubicación
---------

:Módulo:
 Real Q

:Grupo:
 Despachos

:Descripción:
  Administración Despacho Productos Líquidos


Introducción
============

	Después de crear una órden de compra, empieza la configuración del despacho. Aquí, puede crear un nuevo despacho marcando el peso de entrada y de salida de un camión.

	Existen dos formas de obtener el peso del camión de transporte: automática y manual. La forma automática se logra conectando la báscula a la red local; el sistema está escuchando un ingreso constantemente. En la forma manual, es el usuario quien introduce el peso de entrada del camión y el de salida.

	Para poder introducir datos manualmente necesita los permisos adecuados. Diríjase al administrador del sistema.

	Paso 1:
	-------

		Cree la entrada del despacho `Crear un nuevo despacho - Entrada`_

	Paso 2:
	-------

		`Ingrese un Análisis <../productoTerminado/frm_analisis_liquidos.html#crear-un-nuevo-ingreso-de-analisis-liquido>`_ y `asocielo a un vehículo <../productoTerminado/frm_analisis_liquidos.html#asociar-un-analisis-a-un-vehiculo>`_. Este paso no es obligatorio para ir al paso 3, pero sí para terminar el proceso.

	Paso 3:
	-------

		Registre la salida del camión con su nuevo peso y evalúe el peso final del producto despachado según la concentración `Crear un nuevo despacho - Salida`_





Crear un nuevo despacho - Entrada
---------------------------------
	
	- Ejecute la opción "Administración Despacho Productos Sólidos"
	- Haga aclick en el botón |wznew.bmp|
	- Selección en la lista 'Seleccione Almacén' el Almacén de donde sale el despacho
	- Seleccione un conductor de la lista haciendo click en el botón |buscar.bmp|. Si no tiene el conductor guardado, llene los datos correspondientes (nombres y apellidos) y quedará guardado de manera automática al finalizar este proceso.
	- Escriba la placa del vehículo de transporte (tres letras - tres números)
	- Seleccione una transportadora en la lista o agréguela haciendo click en el botón |plus.bmp|. Siga las instrucciones de `Crear transportadora <>`_
	- Si el caso es el de tener una rampa/báscula conectada al sistema, verifique que el peso marcado en "Peso Entrada" es coherente. Si desea marcarlo manualmente, haga click en "Capturar peso manual" (Debe tener el permiso necesario). El sistema pedirá una contraseña, introduzcala y proceda a marcar el peso
	- En el cuadro de texto inferior puede hacer alguna observación pertinente
	- Presione |save.bmp| *Guardar* o F2


	
Buscar un despacho
------------------

	- Ejecute la opción "Administración Despacho Productos Líquidos"
	- Selección en la lista 'Seleccione Almacén' el Almacén de donde sale el despacho.
	- Seleccione un producto - Opcional
	- Elija un periodo marcando la opción 'Por periodos' o marque 'Actuales' Para ver los despachos creados
	- Haga click en |btn_ok.bmp| para ejecutar la búsqueda	



Registrar una salida en el despacho
-----------------------------------

		.. NOTE:

			Al buscar el despacho - entrada creado anteriormente recuerde que no puede usar el filtro cliente ya que no ha sido asignado.

	- Ejecute la opción "Administración Despacho Productos líquidos"
	- Realice una búsqueda del despacho al que ya realizó una entrada en peso. `Buscar un despacho`_
	- Localice el despacho en la grilla, y al final de la fila presione |export1.gif| Seleccione la opción "Registro de Salida"
	- Seleccione el cliente |buscar.bmp| *Cliente*
	- Seleccione el producto |buscar.bmp| *Producto*
	- Si ya ha asociado este auto aun análisis, entonces verá como los datos del análisis son cargados en pantalla. Si no lo ha hecho, no podrá ver el peso final real de la solución por los momentos, ya que no se tienen los datos de concentración
	- Si el caso es el de tener una rampa/báscula conectada al sistema, verifique que el peso marcado en "Peso Salida" es coherente. Si desea marcarlo manualmente, haga click en "Capturar peso manual" (Debe tener el permiso necesario). El sistema pedirá una contraseña, introduzcala y proceda a marcar el peso
	- Revise que el tercer digito: Peso Materia Prima, coincida con el peso requerido por el cliente. **Recuerde que la concentración en el análisis es un factor determinante en el peso final**
	- En el cuadro de texto inferior puede hacer alguna observación pertinente
	- Presione |save.bmp| *Guardar* o F2

Anular un despacho/ingreso de vehículo
--------------------------------------

Al anular un ingreso de vehículo se inhabilita el proceso, pero se deja registro del ingreso para poder consultarlo más adelante.

	- Ejecute la opción "Administración Despacho Productos Líquidos"
	- Realice una búsqueda del despacho al que ya realizó una entrada en peso. `Buscar un despacho`_
	- Localice el despacho en la grilla, y al final de la fila presione |export1.gif|. Seleccione la opción "Anular ingreso de vehículo"

Eliminar un despacho/ingreso de vehículo
--------------------------------------

Al eliminar un ingreso, no se deja registro alguno. El consecutivo de los registros no se retrocede: si elimina el registro 17, su próximo registro NO tomará ese luhar sino más bien el siguiente: 18.

	- Ejecute la opción "Administración Despacho Productos Líquidos"
	- Realice una búsqueda del despacho al que ya realizó una entrada en peso. `Buscar un despacho`_
	- Localice el despacho en la grilla, y al final de la fila presione |export1.gif|. Seleccione la opción "Eliminar ingreso de vehículo"








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
	