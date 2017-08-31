=======================================
Registro de ingreso de materias primas 
=======================================
 
Ubicación
=========
 
:Módulo:
 Real Q
 
:Grupo:
 Materia Prima
 
:Descripción:
 Registro de ingreso de materias primas
 
Introducción
============
 
	Este administrador le permite buscar, anular, eliminar, crear y clasificar los ingresos de materias primas. El estado de un ingreso de mercancía se ve anunciado en la parte inferior de la ventana.
 
	El ingreso de un vehículo con materia prima se adapta a las `definiciones del producto <../materiaPrima/act_maestroinsumos.html#configuracion-avanzada-del-producto>`_. Si usted eligió que la materia prima ingresaba por lotes y además tenía presentaciones distintas, podrá ver reflejado eso en el formulario de ingresos.
 
	*En el ingreso de mercancía se marca el peso del vehículo + el peso de la materia prima. Luego de hecho un ingreso, se hace inmediatamente la salida del vehículo para finiquitar el peso real de la mercancía entrante.*

			.. figure:: images/registro/a.jpg
 						:align: center
 
	Registro rechazado: Todo aquel cuyo análisis no cumplió con lo premeditado.
 
	Registro Derogado: Aquel registro que en un principio fue rechazado, pero por alguna razón el usuario quiso permitir su entrada al almacén.
 
	Registro Liquidado: Una manera de proceder para calcular la verdadera cantidad de un producto (Carbón)
 
	Registro Aprobado: Cualquier ingreso de materia cuyo análisis haya sido exitoso.
 
Crear un Ingreso de Materia Prima
=================================
 
	- Ejecute la opción *Registro de ingreso de materias primas*
	- Haga click en |wznew.bmp|

			.. figure:: images/registro/1.jpg
 						:align: center

	- En la ventana emergente, seleccione en la lista superior el almacén donde registra el ingreso del vehículo
	- En el botón "Proveedor" seleccione la empresa que envía la materia prima
	- En "Producto" seleccione la materia prima entrante. Si usted eligió en la creación de productos que el producto entra en Sacos, entonces aparecerá un nuevo campo a la derecha para colocar el número de sacos. Si usted eligió que el producto tenía varias presentaciones, aparecerá una lista debajo con las posibles opciones; elija una.
	- Seleccione un conductor de la lista haciendo click en el botón |find.bmp|. Si no tiene el conductor guardado, llene los datos correspondientes (nombres y apellidos) y quedará guardado de manera automática al finalizar este proceso.
	- Escriba la placa del vehículo de transporte (tres letras - tres números)
	- Si el caso es el de tener una rampa/báscula conectada al sistema, verifique que el peso marcado en "Peso Entrada" es coherente. Si desea marcarlo manualmente, haga click en "Capturar peso manual" (Debe tener el permiso necesario). El sistema pedirá una contraseña, introduzcala y proceda a marcar el peso
	- En el cuadro de texto inferior puede hacer alguna observación pertinente
	- Presione |save.bmp| *Guardar* o F2
 
Buscar un Ingreso de Materia Prima
==================================
 
	En la parte superior de la ventana, encontrará los 3 filtros principales para realizar una búsqueda
 			.. figure:: images/registro/0.jpg
 						:align: center
		1 - Por salidas: Se refiere a aquellos ingresos de mercancía creados, a los que no se les ha registrado salida de automóvil. 
		2 - Por Analizar: Se refiere a aquellos ingresos de mercancía creados, a los que ya se les registro una salida pero aún no se ha ingresado el análisis correspondiente para terminar el proceso.
		3 - Rechazados: Una vez realizado el análisis, si alguna variable está fuera de rango, el ingreso es rechazado.
		- TODOS: En este filtro puede realizar una búsqueda de todos aquellos registros que han sido aprobados, liquidados o derogados.
 
	- Elija alguna de las opciones anteriores
	- A partir de ahora todos los filtros son opcionales:
		- Escoja el almacén
		- Seleccione un producto de la lista
 
	- Puede usar el campo "Filtrar por # de ingreso" si conoce la referencia del ingreso y desea buscarlo directamente. 
	- Para ejecutar la búsqueda presione |btn_ok.bmp|
 
Pesar salida de vehículo
========================
 
	- Ejecute la opción *Registro de ingreso de materias primas*
	- Encuentre el registro que busca, vea: `Buscar un Ingreso de Materia Prima`_
	- Al final de la fila del registro, presione |export1.gif|. Seleccione la opción "Realizar registro de salida" 
			.. figure:: images/registro/2.jpg
 						:align: center
	- En la ventana desplegada: Si el caso es el de tener una rampa/báscula conectada al sistema, verifique que el peso marcado en "Peso Salida" es coherente. Si desea marcarlo manualmente, haga click en "Capturar peso manual" (Debe tener el permiso necesario). El sistema pedirá una contraseña, introduzcala y proceda a marcar el peso
	- En el cuadro de texto inferior puede hacer alguna observación pertinente
	- Presione |save.bmp| *Guardar* o F2
 
Registrar Análisis de Materia Prima
===================================
	
	- Ejecute la opción *Registro de ingreso de materias primas*
	- Encuentre el registro que busca, vea: `Buscar un Ingreso de Materia Prima`_
	- Al final de la fila del registro, presione |export1.gif|. Seleccione la opción "Realizar análisis de materia prima" 
			.. figure:: images/registro/3.jpg
 						:align: center
	- En la nueva ventana:
		- En el campo "Fecha" escriba la fecha en el formato indicado
		- En lo siguiente, puede elegir una hora para la realización del análisis
		- Escoja el Almacén 
		- Elija un Analista. Vea `Crear un analista <../parametros/act_analistas.html#crear-un-analista>`_
		- Seleccione un operario. Vea `Crear un operario <../parametros/act_operarios.html#crear-un-operario>`_
		- Las líneas negras destacan los análisis disponibles para el perfil elegido para este producto. Ingrese en los campos, los valores recogidos de las muestras. Los campos etiquetados como "Resultado" son de solo lectura y provienen de ecuaciones internas, configuradas anteriormente en la creación del perfil. Si Existe algún resultado marcado en rojo, el análisis está fuera de rango y el ingreso de la materia será rechazado.
		- Puede incluir una observación
		- Presione |save.bmp|
	- Puede usar los filtros de nuevo para conseguir el registro de ingreso de materia prima -Aprobado-, esta vez aplicando el filtro principal "Todos", si fue rechazado, aplique el filtro principal número 3 "Rechazados"
 
Registrar Análisis de Materia Prima Combinado
=============================================
 
Para hacer un análisis de Materia prima combinado (Para varios vehículos) deberá primero chequear esta opción en las características de la materia prima, en la pestaña 'Otros'.
 
			.. figure:: images/registro/5a.jpg
 						:align: center

	- Ejecute la opción *Registro de ingreso de materias primas*
	- Encuentre el registro que busca, vea: `Buscar un Ingreso de Materia Prima`_
	- Al final de la fila del registro, presione |export1.gif|. Seleccione la opción "Realizar análisis 
	de materia prima" 
	- Se mostrará una grilla con los registros de vehículo para esta materia. Elija los vehículos a los que se les enlazará el análisis próximo a hacer.
	- Presione "Continuar"
	- Siga los pasos restantes descritos en `Registrar Análisis de Materia Prima`_

			.. figure:: images/registro/5b.jpg
 						:align: center
 
Derogar un registro
===================
 
	- Ejecute la opción *Registro de ingreso de materias primas*
	- Encuentre el registro que busca, vea: `Buscar un Ingreso de Materia Prima`_
	- Al final de la fila del registro, presione |export1.gif|. Seleccione la opción "Derogación materia prima" - Solo disponible para registros rechazados 
	- Verá una ventana con los resultados de los análisis que fueron rechazados y podrá escribir una observación. Justifique allí el porqué de la derogación. 
	- Haga click en |save.bmp| "Guardar"


			.. figure:: images/registro/6.jpg
 						:align: center
 
 
Liquidar un registro
===================
 
Esta opción solo está disponible para el carbón vegetal, después de haber registrado su análisis. La liquidación facilita el cálculo de la cantidad real de producto. 
 
	- Ejecute la opción *Registro de ingreso de materias primas*
	- Encuentre el registro que busca, vea: `Buscar un Ingreso de Materia Prima`_
	- Al final de la fila del registro, presione |export1.gif|. Seleccione la opción "Liquidar materia prima" - Solo disponible para registros rechazados 
	- Verá una ventana con los siguientes campos:
		- Peso Empaque: Se refiere al peso de la bolsa del saco. 
		- % Cisco
		- *Peso Cisco:* Peso del residuo natural del Carbón en Kilogramos.
		- *Sacos para Cisco:* Número de sacos para la muestra.
		- *Dcto x basura:* Ingrese el peso de los entes extraños al producto en kilogramos.
		- *Dcto x humedad:* Es calculado de acuerdo al % de humedad en el análisis.
		- Dcto x Cisco
		- Dcto x aumento
		- Cantidad Neta
		- Observación Análisis
		- Observación Derogación
 
Eliminar un registro
====================
 
Solo podrá eliminar por completo un registro antes de registrar su salida.
 
	- Ejecute la opción *Registro de ingreso de materias primas*
	- Encuentre el registro que busca, vea: `Buscar un Ingreso de Materia Prima`_
	- Al final de la fila del registro, presione |export1.gif|. Seleccione la opción "Eliminar ingreso de vehículo"
	- En la ventana emergente de confirmación presione "Aceptar"
 
Anular un registro
==================
 
Solo podrá anular un ingreso de vehículo, antes de registrar su Análisis.
 
	- Ejecute la opción *Registro de ingreso de materias primas*
	- Encuentre el registro que busca, vea: `Buscar un Ingreso de Materia Prima`_
	- Al final de la fila del registro, presione |export1.gif|. Seleccione la opción "Anular ingreso de vehículo"
	- En la ventana emergente, escriba una justificación y presione |btn_ok.bmp| *Aceptar*
 
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
 
	
 
 
