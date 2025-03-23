Hola Copilot

Ayúdame a llenar unas plantillas con los datos de la pagina web, puedes usar pista de la pagina actual.

Solo cuando te pida por escrito alguna de las siguientes plantillas llenaras la que corresponda.

"Mercado" rellenas la siguiente plantilla
- ID cliente: 
- Nro de orden: 
- Solicitud: 

"Envio" rellenas la siguiente plantilla
- ID cliente: 
- Correo:  
- Orden ID: 
- Canal: 
- Solicitud: 
Consideraciones para "Envios"
- El Campo "- Canal: " Siempre es CC.

"Remesa" rellenas la siguiente plantilla
- ID del cliente: 
- Tipo de remesa: Domicilio
- Provincia: 
- Número de reparto: 
- Order code: 
- ID o FOI: (Este lo encuentras al lado izquierdo de "tipo")
- Status: 
- Proveedor: 
- Solicitud: 
Consideraciones para "Remesa"
 - El dato "ID Oferta" no es "- ID o FOI: "
 - El dato "ID" Corresponde a "- ID o FOI: "
 - Proveedores validos: MULTIENVIA, REMITTANCES_MS, SAGUAENVIO, RAPIENVIO.


"MLC" rellenas la siguiente plantilla
- ID del cliente: 
- Tipo de remesa: MLC
- Provincia: 
- Order code: 
- ID o FOI: (Este lo encuentras al lado izquierdo de "tipo")
- Status: 
- Proveedor: 
- Solicitud: 
Consideraciones para "Remesa"
 - El dato "ID Oferta" no es "- ID o FOI: "
 - El dato "ID" Corresponde a "- ID o FOI: "
 - Proveedores validos: MULTIENVIA, REMITTANCES_MS, SAGUAENVIO, RAPIENVIO.
 
Consideraciones para todas las plantillas:

- Solo podrás usar los datos de la pagina web actual.
- Cuando el campo diga "- Solicitud: " lo dejaras en blanco.
- Buscar el valor mas cercano al dato.
- Extrae la mayor cantidad de datos posible, pero sin agregar datos no solicitados.
- Si un dato no tiene valor o no se encuentra se deja (No especifica).
- Solo con la primera orden presentada en la pagina.
- Todo en formato de lista.
- No puedes combinar las plantillas.