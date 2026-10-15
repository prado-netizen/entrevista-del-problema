# ENTREVISTA DE LOS TRABAJADORES DE LA TIENDA

## 1. Objetivo de la entrevista

### Objetivo general

Recopilar información sobre los procesos de atención al cliente, elaboración de muebles a medida, gestión de pedidos, control de materiales y servicios de ensamblaje de una mueblería, con la finalidad de identificar los requisitos necesarios para diseñar una base de datos que permita organizar y administrar la información de manera eficiente.

### Objetivos específicos:

- Identificar los datos necesarios para registrar a los clientes y sus pedidos.

- Conocer el proceso de selección, diseño y personalización de muebles.

- Determinar cómo se registran los materiales, precios y características de los muebles.

- Identificar la información necesaria para gestionar los servicios de ensamblaje y entrega.

- Establecer las entidades, los atributos y las relaciones necesarias para diseñar la base de datos.

## 2. Personas entrevistadas y sus cargos

Para el levantamiento de requisitos se propone entrevistar a seis personas que desempeñen diferentes funciones dentro de una mueblería.
Cargos
Propietario o administrador:
Administración general, pedidos, precios y funcionamiento del negocio.
Vendedor o encargado de atención al cliente:
Registro de clientes, consultas, cotizaciones y pedidos.
Diseñador de muebles:
Diseños personalizados, medidas, colores y acabados.
Carpintero o fabricante:
Fabricación, materiales y características de los muebles.
Encargado de inventario:
Existencias de materiales, entradas y salidas de productos.
Técnico de ensamblaje e instalación:
Servicios de montaje, asignación de trabajadores y fechas de instalación.

## 3 Preguntas y respuestas

### A. Clientes y pedidos

**1. ¿Qué datos se registran de cada cliente al realizar una compra?
Se registran el nombre completo del cliente, número de teléfono, correo electrónico y dirección de domicilio. Estos datos permiten identificar al cliente y mantener comunicación para informar sobre sus pedidos y coordinar las entregas.
**2. ¿Cómo se registra actualmente un pedido de muebles?
El pedido se registra anotando los datos del cliente, el tipo de mueble solicitado, las cantidades, las medidas, los materiales, el precio acordado y la fecha estimada de entrega. La información puede almacenarse en un registro manual o en una hoja de cálculo.
**3. ¿Un cliente puede realizar varios pedidos?
Sí, un cliente puede realizar varios pedidos en diferentes fechas. Cada pedido debe contar con un código único para facilitar su identificación y seguimiento.
**4. ¿Qué estados puede tener un pedido (pendiente, en fabricación, terminado, entregado)?
Un pedido puede tener los estados pendiente, en diseño, en fabricación, terminado, en proceso de entrega, entregado o cancelado. Estos estados permiten conocer la situación actual del pedido y facilitar el control de las actividades pendientes.
**5. ¿Qué información se necesita para consultar el historial de pedidos de un cliente?
Se necesita el código del cliente, la fecha de cada pedido, los muebles solicitados, los precios, el estado de cada pedido y las fechas de entrega. Con esta información se puede consultar el historial de compras y verificar los pedidos anteriores.

### B. Muebles a medida
**6. ¿Qué tipos de muebles se fabrican o venden?
Se pueden fabricar o vender roperos, armarios, camas, mesas, escritorios, estantes, muebles de cocina, muebles para televisores y otros productos personalizados según las necesidades del cliente.
**7. ¿Qué medidas se necesitan para fabricar un mueble personalizado?
Se necesitan las dimensiones de alto, ancho y profundidad, expresadas generalmente en centímetros o metros. Según el tipo de mueble, también pueden requerirse medidas internas, distribución de compartimentos y espacios disponibles para su instalación.
**8. ¿Qué materiales, colores y acabados puede elegir el cliente?
El cliente puede elegir materiales como melamina, madera maciza o MDF, dependiendo de las opciones disponibles en la mueblería. También puede seleccionar colores, texturas, tipos de acabado y accesorios, como manijas, bisagras y rieles.
**9. ¿Cómo se calcula y registra el precio de un mueble a medida?
El precio se calcula considerando las dimensiones del mueble, los materiales utilizados, los costos de fabricación, la mano de obra y los servicios adicionales de transporte o ensamblaje. El precio acordado debe registrarse junto con las características del pedido para mantener un control del importe total.
**10. ¿Se deben almacenar diseños, fotografías o planos de los muebles solicitados?
Sí, es conveniente almacenar fotografías, diseños o planos digitales para representar las características del mueble solicitado. En la base de datos se puede guardar el nombre del archivo o su ubicación digital, relacionándolo con el mueble o pedido correspondiente.

C. Ensamblaje, inventario y entrega
**11. ¿Qué servicios de ensamblaje o instalación se ofrecen?
Se pueden ofrecer servicios de ensamblaje de muebles, instalación de roperos y armarios, montaje de muebles de cocina, instalación de estantes y colocación de muebles en el domicilio del cliente. Los servicios dependerán de las capacidades y condiciones de la mueblería.
**12. ¿Cómo se registra la fecha, el costo y el responsable del ensamblaje?
Se registra el código del servicio, el pedido relacionado, la fecha programada, el costo, el estado del servicio y el trabajador responsable. Esta información permite organizar las instalaciones y consultar los trabajos pendientes o completados.
**13. ¿Qué materiales y productos se deben controlar en el inventario?
Se deben controlar las existencias de madera, melamina, MDF, tornillos, bisagras, manijas, rieles, pegamentos y otros materiales utilizados en la fabricación. También pueden registrarse los muebles terminados disponibles para la venta, según el funcionamiento del negocio.
**14. ¿Cómo se registran los proveedores y las compras de materiales?
Se registran los datos del proveedor, como nombre, teléfono, dirección y productos suministrados. Las compras deben incluir la fecha, los materiales adquiridos, las cantidades, los precios y el importe total, para facilitar el control de abastecimiento y gastos.
**15. ¿Qué información se necesita para controlar las entregas y verificar si el trabajo está terminado?
Se necesita registrar el código del pedido, la dirección de entrega, la fecha programada, la fecha de entrega efectiva, el responsable y el estado del trabajo. También se pueden incluir observaciones sobre retrasos, inconvenientes o trabajos pendientes de ensamblaje.