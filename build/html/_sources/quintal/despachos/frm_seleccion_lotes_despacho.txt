===============================
Selección de Lotes por despacho
===============================

Ubicación
---------

:Módulo:
 Real Q

:Grupo:
 Despachos

:Descripción:
  Lotes por despacho


Introducción
------------

	Este es el segundo paso para la realización de un despacho de sólido. En esta interfaz usted podrá seleccionar, según el peso escogido y el número de containers en la programación de despacho, los lotes enumerados (producidos/en stock) que van a cada container. 

	- Primer paso: `Crear programación de despacho <../despachos/frm_pedido_venta_admin_despacho.html>`_

	Ejemplo:
	--------

	 - Usted programo 25000 kg de producto, en dos containers de 20000 kgs de capacidad. El producto viene en presentaciones de 7500kg de peso. Entonces, lógicamente deberá repartir 2 presentaciones para 1 container y 1 para otro container. 
	 - Por cada lote salen 2 presentaciones, lo que significa que al menos 2 lotes van a salir de almacen.
	 - Aunque cada presentación es individual, pertenece a un lote. Ejemplo: la presentación 'a' pertenece al lote 1, la presentación 'b' pertenece al lote 1, la presentación 'd' pertence al lote 4.
	 - Supongamos que usted tiene disponibles en almacen 5 lotes enumerados del 1 al 5, cada uno con 2 presentaciones marcadas de la 'a' a la 'j'. El sistema le permite elegir la presentacion a, la d para mnontarse en el container x1, y la presentación g para montarse en el container x2.

	 Si un lote tiene 3 presentaciones, y solo se elige una para salir, el lote seguira disponible para seleccionar las presentaciones que quedan en otra selección de lotes por despacho.

	 Las unidades/presentaciones asignadas a cada conteiner son listadas en el segundo panel. En el tercer panel puede cambiar su posición, de esta manera y en este orden, el informe de lotes por despacho será impreso.


Crear la selección de lotes por despacho
----------------------------------------

	- Ejecute la opción *Lotes por despacho*
	- En la lista superior seleccione el Almacén donde realizó la programación
	- El cursor se posicionará sobre un cuadro de texto bajo la lista, presione Enter para seleccionar un cliente de la lista. Solo aparecerán los clientes que tengan un despacho en proceso.
	- El cursor se posiciona ahora en el cuadro de texto 'Número de orden', presione Enter para ver las ordenes asociadas a este cliente que se encuentran en proceso de despacho. Haga click sobre la orden que desea procesar y lugo Enter.
	- Pulse el botón |btn_ok.bmp| *Cargar datos*
		- Aparecerá una ventana donde podrá elegir las presentaciones para el producto a despachar. En este momento verá listadas en la grilla las posibles presentaciones del producto, con una columna llamada 'Cantidad'. 
		- La suma de las cantidades de cada presentación deben coincidir con la cantidad de producto a despachar. **Ejemplo a1**: si quiero despachar 5000kg de un producto, puedo seleccionar 2 presentaciones de 2000kg y una de 1000kg; también puedo seleccionar 5 presentaciones de 1000kg.
		- Si todo está correcto, puede oprimir *Continuar*
	- Es importante resaltar que una vez carguen los datos correctamente, la programación de despacho deja de ser editable.
	- En la primera grilla horizontal, aparecerán los productos que seleccionó en la programación, divididos en las presentaciones que recién escogió, junto con la información de los container. Haga click sobre cualquiera de las filas de esta primera grilla (Cada una representa una presentacion) para ver en el panel vertical derecho los lotes que coinciden con esta presentación y la cantidad de presentaciones que contienen.
		- **Ejemplo a2:** En el 'ejemplo a1' Usted seleccionó despachar el producto en 2 presentaciones de 2000 y una de 1000 Kg. En el panel superior horizontal verá una fila para la presentación de 2000 y una para la presentación de 1000. 
		- Si hace click en la fila que indica la presentación de 2000, a la derecha, verá los lotes de esta presentación. Algo como esto:
			- Lote: 546545 | sacos: 4 | cantidad: **Usted elige** | [] |
		-Si hace check en la casilla del final, podrá elegir la cantidad de 'sacos' que desea sacar de este lote para el contenedor.
	- El panel vertical derecho muestra los lotes y le permite seleccionar la cantidad de sacos que desea sacar del lote despues de chequear la casilla de verificación. Estos lotes pueden ser agregados al **contenedor que se encuentra en la parte inferior del panel**, haciendo click en |plus.bmp|. Esta selección es guardada. 
	- A medida que va marcando lotes y eligiendo las cantidades, puede observar que se reduce la columna saldo de la grilla primera. La cantidad de sacos que elige debe ser menor a la cantidad marcada en la columna 'Bls x Contndr' (Bolsas por contenedor).
	- Una vez elija los sacos que van a ir al contenedor (después de presionar |plus.bmp|), los sacos aparecerán listados en la segunda grilla horizontal. Los sacos listados en la segunda grilla serán los de la presentación seleccionada en la primera grilla. Desde este segundo panel, la cantidad de sacos es editable, mientras esté permitida por los límites de cantidad.
	- En el panel horizontal 3 aparece la lista de sacos seleccionados para el contenedor, aquí puede arrastrarlos hacia arriba o hacia abajo para ordenarlos. Si desea cambiar de contenedor, seleccione cualquier lote en la grilla 2 del contenedor que necesita ordenar.
	- En la parte inferior, hay un cuadro de texto que le permite colocar una observación opcional acerca de este proceso del despacho.
	- Presione |save.bmp| *Finalizar despacho*. Ahora puede imprimir el documento `Imprimir la selección de Lotes`_


Imprimir la selección de Lotes
------------------------------

	- `Imprimir una selección de lotes <../despachos/frm_pedido_venta_admin_despacho.html#imprimir-una-seleccion-de-lotes>`_











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

	