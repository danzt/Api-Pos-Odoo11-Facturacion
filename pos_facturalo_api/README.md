# pos_facturalo_api

Odoo integración al modulo POS

Configuración
=============

* Ir a menú Contactos -> botón editar/crear, llenar los campos Correspondientes, puede comenzar por agregar el tipo de documento, (RUC,DNI), al agregar un RUC puede ingresar el numero y el resto de los campos se llenarán de forma automática mediante una consulta que realiza el modulo

* Se debe marcar la casilla en Facturación -> menu configuracion/ajustes -> pestaña Facturación -> IVA de bienes digitales de la UE (ó el país actual)

* Al reailzar un pago en la sesión de punto de venta observará dos botones correspondientes a la Factura y Boleta, puede seleccionar alguno, y el documento será enviado a la API