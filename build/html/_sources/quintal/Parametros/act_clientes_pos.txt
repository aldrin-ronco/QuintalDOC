==========================
Administración de clientes
==========================

Ubicación
=========

:Módulo:
  Real Q

:Grupo:
 Parámetros

:Descripción:
  Adminsitración de clientes

Introducción
============

En *Administración de clientes* podrá crear nuevos clientes, visualizarlos en forma de grilla, eliminarlos o modificar sus datos personales. Cada cliente tiene un código interno asignado y puede buscarlo desde la grilla usando el nombre o documento.

Crear un cliente
================

Para crear un cliente realice los siguientes pasos:
 	
 	- Ejecute la opción *Administración de clientes*
 	- En el pie de la ventana pulse sobre el botón |wznew.bmp| *nuevo*
 	- Se desplegará una ventana emergente donde podrá dar cavida a los datos del cliente:
 		- Régimen (tributario): 
 			- Simplificado
 			- Común
 			- Gran contribuyente
 		- **Documento de identificación**: Si este número de identificación ha sido usado en algún otro apartado (vendedores, proveedores, etc) entonces el sistema desplegará la información registrada de esta persona.

 	 		.. NOTE::

 	 			En la cabecera conseguirá dos opciones llamadas "Múltiples textos" y "Único texto" que modificarán la manera en cómo el sistema pide los datos (En uno, o en varios campos de texto)


 		- **Datos básicos**: Nombres (si es Régimen Común) o Razón social, teléfonos, dirección

 		.. NOTE::

 			Datos obligatorios: Primer nombre, primer apellido, departamento, municipio y número de documento.

 		- **Otros datos**: 

 				- Nombre comercial: Nombre del establecimiento (no razón social)
 				- lista de precios: Las listas de precios pueden ser asociadas a un cliente específico con el fin de ofrecer precios especiales al mismo. Vea `Configurar lista de precios <>`_ Esta lista será cargada automáticamente al elegir este cliente.
 				- vendedor destinado: Un vendedor puede ser asociado  a un cliente. Será cargado automáticamente en el momento de hacer una venta a este cliente.
 				- Email
 				- Plazo de crédito: El número aquí indicado será mostrado automáticamente en el momento de la facturación al elegir este cliente.
 				- Bloquear ventas a este cliente: Un usuario puede bloquear un cliente para que no pueda efectuar compras, dejando una aclaratoria en un campo de texto emergente. Cuando se vaya a facturar al cliente, la razón establecida por el usuario será mostrada en pantalla.
 				- Este cliente es exento de IVA: Márquela para que en el momento de la facturación, el IVA no se atribuya al monto.
 				- Fecha de nacimiento

 			

 		- **Sucursales**: Un cliente puede tener en cuanto a su negocio, varias sucursales. En esta pestaña se pueden crear sucursales para saber a cual se atiende en el momento de la venta. Para crear una nueva sucursal, haga click en la pestaña 'Sucursales' y luego en el botón 'Crear sucursales'. La referencia de la sucursal se refiere a cualquier nombre que la pueda identificar.


 		- **Retenciones:** Aparece un listado de retenciones creadas en sistema, puede marcar las que quiere que se apliquen **automáticamente** sobre la facturación para este cliente. 
 			- Puede marcar la casilla *Retiene sobre cualquier base* para aplicar las retenciones marcadas en cualquier monto imponible.

 		- **Leyenda Certificado:** Digite aquí un texto de personalización para la certificación de sólidos. Este texto es opcional. El resto del certificado permanece igual.




Elmiminar un cliente
====================
 	- Ejecute la opción *Administración de clientes*
 	- Seleccione, haciendo click, a un cliente en la grilla
 	- Presione el botón |delete.bmp| *eliminar* al pie de la ventana

 	- En el cuadro de confirmación presiones 'Sí'

 	.. Note:
 	No podrá eliminar un cliente que tenga cualquier tipo de transacción adjudicada.


Modificar un cliente
====================

 	- Ejecute la opción *Administración de clientes*
 	- Seleccione, haciendo click, a un cliente en la grilla
 	- Presione el botón |wzedit.bmp| *modificar* al pie de la ventana
		 


 	- Aparecerá una ventana donde podrá cambiar los datos del cliente que necesite, y dejar los que considere ya están bien.




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