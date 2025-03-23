Ayúdame a llenar las plantillas con los datos de la pagina web.

Tienes varias opciones en los "Conjuntos de Datos" para crear la "Lista de datos" utiliza solo la opción que mejor se ajuste, estos te ayudaran a identificar que plantilla utilizar.

Conjuntos de Datos:

-Datos de "Remesa" (Ordercode, Cliente Id, Fecha, Estado Orden, Monto Pagado, Via, Tarjeta, Risk, IP, Client DeviceId, ID Oferta=no es "ID o FOI", Titulo, Descripción, Estado, Precio Listado, Descuento, Precio total, Fecha Inicio, Fecha Final, ID, tipo, Proveedor, status, amount, intentos, Provincia, Nro de Reparto) consideración adicional:
- Proveedores validos: MULTIENVIA, REMITTANCES_MS, SAGUAENVIO, RAPIENVIO.
- El "ID Oferta" no es "ID o FOI:"
- El "ID" si es "ID o FOI:"

-Datos de "MLC" (Iguales a "Remesa" pero se diferencia porque adicionalmente tienen "Numero Tarjeta" y "Banco")

-Datos de "Recarga" (Personificado por, ID Oferta, Titulo, Descripción, Estado, Precio Listado, Descuento, Precio total, Fecha Inicio, Fecha Final, id, tipo, status, amount, currency, operador, destino="Teléfono Recargado" no es "Teléfono Correcto", nombre=no es "Nombre completo", validez, intentos) consideración adicional:
- Si dice "CUBACEL" es "Datos de recargas".
- Si dice "CUBACEL_PLAN" es "Datos de recargas".

-Datos de "Mercado" (Cuenta="ID cliente", Orden, Solicitud, Total, Negocio, Creado, Entregado)

-Datos de "Envios" (id="ID cliente", (Correo), OrdenId="Orden ID":, Referencia:, Estado:, Estado del Pago:, Semanas Total: )


Consideraciones:

- Solo podrás usar los datos de la ultima imagen que te pase.
- Cuando se pida "Solicitud", solo deja un espacio.
- Cuando se pida "Canal" Siempre es CC.
- Si dice "CUBACEL" es "Datos de recargas".
- Si dice "CUBACEL_PLAN" es "Datos de recargas".
- Proveedores validos: MULTIENVIA, REMITTANCES_MS.
- Buscar el valor mas cercano al dato.
- Extrae la mayor cantidad de datos posible, pero sin agregar datos no solicitados.
- Si un dato no tiene valor o no se encuentra se deja (No especifica).
- En "Correo" va sin texto adicional.
- Reemplaza "# de orden:" por "Nro de orden"
- Solo con la primera orden
- Todo en formato de lista.
- No puedes combinar los "Conjuntos de Datos".

Rellena las plantilla de acuerdo al que mas se adecue

"Mercado" rellenas la siguiente plantilla
"-ID cliente:  
-Nro de orden:  
-Solicitud:"

"Envio" rellenas la siguiente plantilla
"-ID cliente:  
-Correo: Asegurarse que sea un correo activo  
-Orden ID:  
-Canal:  
-Solicitud:"

"Remesa" rellenas la siguiente plantilla
"-ID del cliente:  
-Tipo de remesa: Domicilio  
-Provincia:  
-Número de reparto: Ubicado en la parte inferior izquierda.(APLICA SOLO PARA -REMESAS A DOMICILIO)
-Order code:  
-ID o FOI: ID debajo del ID de oferta (al lado del tipo de producto) se deberá desplegar la oferta para ver este dato.  
-Status:  
-Proveedor:  
-Solicitud:"

"MLC" rellenas la siguiente plantilla
"-ID del cliente:  
-Tipo de remesa: MLC  
-Provincia:  
-Order code:  
-ID o FOI: ID debajo del ID de oferta (al lado del tipo de producto) se deberá desplegar la oferta para ver este dato.  
-Status:  
-Proveedor:  
-Solicitud:"

"Recarga" rellenas la siguiente plantilla
"ID del cliente: 
Teléfono Recargado: 
Order code: 
ID o FOI: ID debajo del ID de oferta (al lado del tipo de producto) se deberá desplegar la oferta para ver este dato.  
Status: 
Solicitud: