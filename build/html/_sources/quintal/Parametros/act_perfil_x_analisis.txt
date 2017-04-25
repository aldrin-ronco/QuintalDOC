===============================================
Administración de Perfiles por tipo de Análisis
===============================================

Ubicación
---------

:Módulo:
 Real Q

:Grupo:
 Parámetros

:Descripción:
  Administración de Perfiles por tipo de Análisis

Introducción
============

	
	Tipos de Análisis
	-----------------

	Los perfiles están agrupados según el momento o proceso (Tipo de análisis) en el cual se aplican. Puede crear nuevos tipos desde esta interfaz. Los tipos que aparecen en la lista, fueron creados en la interfaz `Administración de Análisis <../parametros/act_analisis.html#crear-un-tipo-de-analisis>`_

	Ejemplo: La agrupación 'Materia Prima' requiere de los perfiles: Azufre, carbón vegetal, ácido sulfúrico, etc.

	Perfil
	------

	Un perfil es un conjunto de análisis que pueden ser aplicados a un producto/proceso para obtener un resultado útil. Cree nuevos perfiles y agregue análisis, desde esta interfaz. **Los análisis que puede agregar a un perfil son solamente aquellos que fueron agregados al Tipo de Análisis** en la interfaz `Administración de Análisis <../parametros/act_analisis.html#crear-un-tipo-de-analisis>`_

	Ejemplo: El perfil 'Análisis de Azufre' requiere de análisis como: % de acidez, constantes, % de azufre, % de humedad, etc.

	Análisis y Variables
	--------------------

	Cada Análisis es distinto y usted puede agregar las variables que necesite para su desarrollo (Estándar, Especiales y constantes), desde esta interfaz puede agregar nuevas variables al análisis. 

	Cada Variable/Constante tiene configuraciones propias que puede agregar también a partir de este apartado.

	Las variables se pueden ordenar dentro del análisis para ser mostradas en pantalla en el orden correcto de cálculo. También pueden ser ordenadas para su respectivo orden dentro de los comprobantes/certificados. 

	Por defecto ningún Análisis tiene variables agregadas para la impresión del certificado; esto se debe a que muchos análisis son internos y no requieren de impresión en ningún formato.


	Árbol:
	------
		- Agrupación de perfiles
			- Perfil
				-Análisis
					-Variables/constantes

Tipos de Análisis
=================

Crear un tipo de Análisis
-------------------------

	- Ejecute la opción *Administración de Perfiles por tipo de Análisis*
	- En cualquier lugar vacío de la ventana desplegada haga clic derecho. 
	- Haga clic en |wznew.bmp| *Nuevo tipo de análisis*
	- Verá crearse un nuevo folder en la lista donde podrá introducir el nombre del tipo. Ejemplo: Materia Prima (aquí se agruparán todos los análisis necesarios para certificar la materia prima)

Cambiar Nombre a un tipo de Análisis
------------------------------------

	- Ejecute la opción *Administración de Perfiles por tipo de Análisis*
	- Haga clic derecho en el tipo de análisis cuyo nombre desea modificar
	- Escoja la opción |wzedit.bmp| *Cambiar nombre a [nombre de tipo]*
	- Digite el nuevo nombre y presione Enter

Eliminar un tipo de Análisis
----------------------------

	- Ejecute la opción *Administración de Perfiles por tipo de Análisis*
	- Haga clic derecho en el tipo de análisis que desea eliminar
	- Elija la opción |delete.bmp| *Eliminar tipo Análisis [Nombre de tipo]*
	- En la ventana de confirmación pulse 'sí'

Perfiles
========

Agregar un perfil a un tipo 
---------------------------

	- Ejecute la opción *Administración de Perfiles por tipo de Análisis*
	- Haga clic derecho sobre el tipo al que agregará un Perfil
	- Elija la opción |wznew.bmp| *Nuevo Perfil*
	- Se agregará un nuevo Perfil bajo el icono del Tipo, digite el nombre del Perfil y presione Enter

Agregar Análisis al Perfil
--------------------------
	
	- Ejecute la opción *Administración de Perfiles por tipo de Análisis*
	- Haga clic derecho en el Perfil 
	- Escoja la opción |wzedit.bmp| *Configurar Análisis*
	- Se desplegará una nueva ventana, en cualquier lugar vacío haga clic derecho. 
	- Elija |wznew.bmp| *Agregar análisis a la lista*
	- En la ventana emergente encontrará la lista de análisis disponibles:
		- Recuerde que los análisis disponibles son solamente los que fueron agregados a este tipo de Análisis en la pantalla de Administración de Análisis REF
		- Puede seleccionar varios análisis para agregar, chequeando las casillas al final de cada fila de análisis
		- En la grilla, junto al nombre de cada análisis, encontrará una lista de agrupaciones menores en las que puede elegir vaya el análisis.
	- Una vez seleccionados los análisis, presione |btn_ok.bmp| *Seleccionar*
	

Eliminar un Análisis
--------------------

	- Ejecute la opción *Administración de Perfiles por tipo de Análisis*
	- Haga clic derecho en el Perfil 
	- Escoja la opción |wzedit.bmp| *Configurar Análisis*
	- Haga clic derecho en el análisis que desea eliminar
	- Elija la opción |delete.bmp| *Remover Análisis [Nombre de Análisis]*, el análisis se removerá de la lista, mas no será eliminado.
	- En la ventana de confirmación pulse 'sí'

Orden de los Análisis
=====================

Definir orden de presentación de análisis
-----------------------------------------

Para ordenar los análisis en la manera más adecuada para la visualización en pantalla, siga estos pasos:

	- Ejecute la opción *Administración de Perfiles por tipo de Análisis*
	- Haga clic derecho en el Perfil a ordenar
	- Escoja la opción |wzedit.bmp| *Configurar Análisis*
	- Haga clic derecho en cualquier lugar de la ventana, escoja la opción |wzedit.bmp| *Definir orden de presentación de análisis*
	- Se desplegará una ventana con los análisis en una lista. Cada análisis tiene un panelcillo cuadrado a la izquierda. Mueva el análisis haciendo clic sobre el panel (Aparecerá una flecha bidireccional) y manteniéndolo presionado mientras mueve el ratón.
	- Haga clic en |save.bmp| *Guardar*

Definir orden de Análisis para certificado
------------------------------------------

Para ordenar los análisis en la manera más adecuada para la visualización en pantalla, siga estos pasos:

	- Ejecute la opción *Administración de Perfiles por tipo de Análisis*
	- Haga clic derecho en el Perfil a ordenar
	- Escoja la opción |wzedit.bmp| *Configurar Análisis*
	- Haga clic derecho en cualquier lugar de la ventana, escoja la opción |wzedit.bmp| *Definir orden de Análisis para certificado*
	- Se desplegará una ventana con dos paneles: uno a la derecha y otro a la izquierda. El de la izquierda lista los análisis NO incluidos aún en el certificado, el de la derecha lista los análisis ya incluidos. Incluya un análisis haciendo clic sobre su nombre y manteniéndolo presionado mientras lo arrastra hasta el panel derecho.
	- Los análisis incluidos pueden ser ordenados en la manera como se mostrarán en el certificado. Mueva el análisis haciendo clic sobre el panelcillo a su izquierda (Aparecerá una flecha bidireccional) y manteniéndolo presionado mientras mueve el ratón, subiendo o bajando.
	- Haga clic en |save.bmp| *Guardar*

Definir orden de Variables en Análisis
--------------------------------------

Para ordenar las variables dentro de un  análisis de la manera más adecuada para la visualización en pantalla, siga estos pasos:

	- Ejecute la opción *Administración de Perfiles por tipo de Análisis*
	- Haga clic derecho en el Perfil a ordenar
	- Escoja la opción |wzedit.bmp| *Configurar Análisis*
	- Haga clic derecho en cualquier lugar de la ventana, escoja la opción |wzedit.bmp|  *Definir orden de Variables en Análisis [Nombre de análisis]*
	- Se desplegará una ventana con las variables en una lista. Cada variable tiene un panelcillo cuadrado a la izquierda. Mueva la variable haciendo clic sobre el panel (Aparecerá una flecha bidireccional) y manteniéndolo presionado mientras mueve el ratón.
	- Haga clic en |save.bmp| *Guardar*

Variables
---------

Agregar constante a Análisis
----------------------------

	- Ejecute la opción *Administración de Perfiles por tipo de Análisis*
	- Haga clic derecho en el Perfil a ordenar
	- Escoja la opción |wzedit.bmp| *Configurar Análisis*
	- Haga clic derecho sobre el análisis y elija la opción |wznew.bmp| *Agregar constante [Nombre de análisis]* 
	- En la lista superior de la nueva ventana escoja la constante que necesita. Es recomendable que los nombres de sus variables/constantes (en el momento de la creación) tengan nombres que faciliten su búsqueda, por ejemplo: 'Constante 0.1516' es un buen nombre para una constante cuyo valor es 0.1516.
	- Haga clic en |save.bmp| *Guardar* o presione F2

Agregar variable Estándar
-------------------------

	- Ejecute la opción *Administración de Perfiles por tipo de Análisis*
	- Haga clic derecho en el Perfil a ordenar
	- Escoja la opción |wzedit.bmp| *Configurar Análisis*
	- Haga clic derecho sobre el análisis y elija la opción |wznew.bmp| *Agregar variable estándar [Nombre de análisis]*
	- En la lista superior de la nueva ventana escoja la variable que necesita.
	- Existen tres tipos de personalización para la variable Estándar:
		- Terceros: Si en la lista <<Configuración terceros>> usted selecciona <<configuración personalizada>>, se habilita el botón *Seleccionar Tercero*. Haga clic en él y seleccione un Tercero de la lista. Esta opción le permite que la configuración que guarde para esta variable solo esté dada para el tercero seleccionado. Para los demás terceros la variable permanece en su forma pura.
		- Presentación: Si en la lista <<Configuración Presentación>> usted selecciona <<configuración personalizada>>, se habilita el botón *Seleccionar Presentación*. Haga clic en él y seleccione una Presentación de la lista. Esta opción le permite que la configuración que guarde para esta variable solo esté dada para la presentación seleccionada. Para las demás presentaciones la variable permanece en su forma pura. 
		- Calidad: Si en la lista <<Configuración Calidad>> usted selecciona <<configuración personalizada>>, se habilita el botón *Seleccionar Calidad*. Haga clic en él y seleccione una Calidad de la lista. Esta opción le permite que la configuración que guarde para esta variable solo esté dada para la calidad seleccionada. Para las demás calidades la variable permanece en su forma pura. 
	- Puede seleccionar luego el 'Tipo de captura del valor':
		- Valor digitado por el usuario
		- Valor obtenido por medio de formulación: 
			- Si selecciona esta opción, verá desplegarse todas las variables estándar y constantes que ha agregado a este y otros análisis del mismo perfil. Estas variables están agrupadas según el análisis al que pertenecen, ya que puede darse el caso de que una variable como 'Resultado' se encuentre al mismo tiempo en varios análisis. 
			- Bajo la lista de variables existe un cuadro de texto donde puede escribir la formula. Puede hacer doble clic sobre las variables de la lista para agregarlas a la formula. Este cuadro de texto marcará en rojo la formula si existe algun error en la operación (por ejemplo, falta un paréntesis). Recuerde que se tomará en cuenta las prioridades entre operadores matemáticos y lógicos.
	- Control de mínimos o máximos: Puede establecer, si lo desea, un valor mínimo y uno máximo para esta variable. De esa manera, cuando calcule o digite su valor, el sistema mostrará un mensaje advirtiendo de que está rebosando los límites definidos.
	- Reemplazar Especificación en certificado: Algunas variables requieren un cambio de nombre al momento de mostrarse en el certificado, por razones protocolares o de entendimiento. Si chequea esta opción, puede asignarle el nombre que llevará en el certificado.
	- Requerida para impresión: Muchas variables no van impresas en el certificado. Para incluir esta variable en el certificado, chequee esta opción. 
	- Visible en la pantalla de análisis: Si desea que una variable sea calculada, y que sea vista en la pantalla de análisis, entonces marque esta opción. De lo contrario será una variable oculta. Se usa generalmente para procedimientos internos.
	- Haga clic en |save.bmp| *Guardar* o presione F2

Agregar Variables Especiales
----------------------------

Una variable especial es útil para parametrizar algunas características, por ejemplo: el estado de un análisis: aprobado, rechazado; el estado de una solución: líquido, sólido, gas; la proveniencia: norte, sur, este, oeste.

	- Ejecute la opción *Administración de Perfiles por tipo de Análisis*
	- Haga clic derecho en el Perfil a ordenar
	- Escoja la opción |wzedit.bmp| *Configurar Análisis*
	- Haga clic derecho sobre el análisis y elija la opción |wznew.bmp| *Agregar variable estándar [Nombre de análisis]*
	- En la lista superior de la nueva ventana escoja la variable que necesita.
	- En el campo 'Digite nombre de opción', puede escribir cuantas opciones necesite para esta variable especial. Escriba una opción, ejemplo: sólido, y pulse |plus.bmp|
	- Reemplazar Especificación en certificado: Algunas variables requieren un cambio de nombre al momento de mostrarse en el certificado, por razones protocolares o de entendimiento. Si chequea esta opción, puede asignarle el nombre que llevará en el certificado.
	- Requerida para impresión: Muchas variables no van impresas en el certificado. Para incluir esta variable en el certificado, chequee esta opción. 
	- Haga clic en |save.bmp| *Guardar* o presione F2

	--------------------------------------------


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