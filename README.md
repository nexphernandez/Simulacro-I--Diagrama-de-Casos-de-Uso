# Tienda de comercio electronico

## Diagrama de uso

<img src="img.drawio.png">



## Especificaciones de lso actores y casos de uso

### Actores

   #### Cliente

|  Actor | Cliente|
|---|---|
| Descripción  | Persona interesada en comprar. |
| Características  ||
| Relaciones |  |
| Referencias | Navegar por el catalogo, Comprar e informar dirección|   
|  Notas ||
| Autor  | Nicolás Expósito Hernández |
|Fecha | 05/11/2024 |

   #### Banco

|  Actor | Banco|
|---|---|
| Descripción  | Actor externo que se encarga del tramite de pago |
| Características  ||
| Relaciones |  |
| Referencias | Verificar datos de la tarjeta, realizar compra y enviar facturas|   
|  Notas ||
| Autor  | Nicolás Expósito Hernández |
|Fecha | 05/11/2024 |

#### Sistema

|  Actor | Sistema|
|---|---|
| Descripción  | Se encarga de enviar facturas al usuarui|
| Características  ||
| Relaciones |  |
| Referencias | Enviar facturas|   
|  Notas ||
| Autor  | Nicolás Expósito Hernández |
|Fecha | 05/11/2024 |

## Casos de uso

### Autor

#### Navegar por el catalogo

|  Caso de Uso	CU.1 | Navegar por el catalogo |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al [documeto](). |
  | Actor  |  Usuario general, |
  | Descripción | Navegar por la aplicacion para ver los productos |
  | Flujo básico ||
  | Pre-condiciones | |  
  | Post-condiciones  | |  
  |  Requerimientos |  |
  |  Notas |  |
  | Autor  | nexphernandez |
  |Fecha | 05/11/2024|

#### Compra

|  Caso de Uso	CU.2 | compra |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al [documeto](). |
  | Actor  |  Usuario general, |
  | Descripción | El cliente compra un producto |
  | Flujo básico ||
  | Pre-condiciones |Elegir artículo y completar datos de la tarjeta |  
  | Post-condiciones  | realizar compra |  
  |  Requerimientos |  |
  |  Notas |  |
  | Autor  | nexphernandez |
  |Fecha | 05/11/2024|

#### Informar direccion

|  Caso de Uso	CU.3 | informar direccion |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al [documeto](). |
  | Actor  |  Usuario general, |
  | Descripción | El cliente indica el lugar donde se envia el producto|
  | Flujo básico ||
  | Pre-condiciones ||  
  | Post-condiciones  | |  
  |  Requerimientos |  |
  |  Notas |  |
  | Autor  | nexphernandez |
  |Fecha | 05/11/2024|

### Banco

#### Verificar datos de la tarjeta

|  Caso de Uso	CU.1 | Verificar datos de la tarjeta |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al [documeto](). |
  | Actor  |  Banco |
  | Descripción | Se verifica que los datos de la tarjeta sean correctos|
  | Flujo básico ||
  | Pre-condiciones | Completar datos de la tarjeta |  
  | Post-condiciones  | |  
  |  Requerimientos |  |
  |  Notas |  |
  | Autor  | nexphernandez |
  |Fecha | 05/11/2024|

  #### Realizar compra

|  Caso de Uso	CU.2 | Realizar compra |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al [documeto](). |
  | Actor  |  Banco |
  | Descripción | Da permiso para que se realize la compra o no|
  | Flujo básico ||
  | Pre-condiciones | Elegir articulo |  
  | Post-condiciones  | |  
  |  Requerimientos |  |
  |  Notas |  |
  | Autor  | nexphernandez |
  |Fecha | 05/11/2024|

### Sistema

#### Enviar una factura al email

|  Caso de Uso	CU.1 | Enviar una factura al email |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al [documeto](). |
  | Actor  |  Banco |
  | Descripción | Se envia un mensaje al email del cliente cuando se realice una compra|
  | Flujo básico ||
  | Pre-condiciones ||  
  | Post-condiciones  | |  
  |  Requerimientos |  |
  |  Notas |  |
  | Autor  | nexphernandez |
  |Fecha | 05/11/2024|

# Sistema Videomax

<img src="alguiler-pelicula-cu.png">

## Especificación de Actores y Operaciones

### Actores

   #### Cliente

|  Actor | Cliente|
|---|---|
| Descripción  | Persona interesada en alquilar una pelicula. |
| Características  ||
| Relaciones |  |
| Referencias | Proporcional datos personales, alquilar pelicula y reservar una pelicula|   
|  Notas ||
| Autor  | Nicolás Expósito Hernández |
|Fecha | 05/11/2024 |

   #### Proveedor

|  Actor | Proveedo|
|---|---|
| Descripción  | Actor que se encarga de abastecer el stock si es necesario |
| Características  ||
| Relaciones |  |
| Referencias | Abastece peliculas segin existencia|   
|  Notas ||
| Autor  | Nicolás Expósito Hernández |
|Fecha | 05/11/2024 |

   #### Admisnistrador VideoMax

|  Actor | Admisnistrador VideoMax|
|---|---|
| Descripción  | Se encarga de que funcione el sistema|
| Características  ||
| Relaciones |  |
| Referencias | Registra a los clientes, Registrar alquiler, Registra reserva, Registra pelicula y Actualiza proveedor|   
|  Notas ||
| Autor  | Nicolás Expósito Hernández |
|Fecha | 05/11/2024 |

## Casos de uso

### Autor

#### Registrarse

|  Caso de Uso	CU.1 | Registrarse |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al [documeto](). |
  | Actor  |  Usuario general, Administrador |
  | Descripción | Registrarse en la tienda  |
  | Flujo básico ||
  | Pre-condiciones | |  
  | Post-condiciones  | Se genera un perfil |  
  |  Requerimientos | Correo electronico |
  |  Notas |  |
  | Autor  | nexphernandez |
  |Fecha | 05/11/2024|