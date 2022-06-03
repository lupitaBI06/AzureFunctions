# Azure Functions

Azure functions es un recurso de Azure sin servidor, que se utiliza cuando debe realizarse un trabajo en respuesta a un evento, ejemplo; un temporizador, mensaje de otro servicio de Azure etc. Es idela cuando importa sólo el código que ejecuta el servidor y no la infraestructura o plataforma. Es un Servicio como plataforma (PaaS).

El cobro de Azure Functios es por evento y tamaño del evento.

![Azure Functions Logo](https://github.com/lupitaBI06/AzureFunctions/blob/main/imagenes/logo.png)

**¿Qué es informática sin Servidor?**

La informática sin servidor incluye la abstracción de servidores, un escalado controlado por eventos y la microfacturación.

- Azure functions: Se puede ejecutar código en prácticamente cualquier lenguaje, requiere de escribir código para ejecutar cada paso.
- Azure logic apps: Están diseñadas en web y pueden ejecutar lógica desencadenada mediante servicios de Azure sin escribir código.

**¿Cuándo usar Azure Functions?**
- Para hacer microservicios o APIs.
- Puede usarse para hacer servicios de mensajería, IoT.

### Pasos para crear un recurso Azure Functions

- Dentro del [portal de azure](www.portal.azure.com) se busca el recurso Aplicación de funciones.

![Buscar Azure Functions](https://github.com/lupitaBI06/AzureFunctions/blob/main/imagenes/buscar_functions.PNG)

-Se le da en crear nuevo reecurso y se llenan los requerimeintos necesarios. 

![requerimientos](https://github.com/lupitaBI06/AzureFunctions/blob/main/imagenes/requerimientos.PNG)

- Una ves llenados los campos necesarios se revisa y crea el recurso. Una ves que este se crea entramos al recurso y dentro del recurso nos vamos a funciones.

![ir a funciones](https://github.com/lupitaBI06/AzureFunctions/blob/main/imagenes/ir_a_funciones.PNG)

- Dentro de funciones damos clic en crear función. Aquí seleccionamos una plantilla y damos en crear.

![funcioness](https://github.com/lupitaBI06/AzureFunctions/blob/main/imagenes/ir_a_funciones.PNG)

- En este caso se crea una función tipo HTTP trigger. Dentro de esa función damos clic en codigo y prueba. 

![boton codigo prueba](https://github.com/lupitaBI06/AzureFunctions/blob/main/imagenes/codigo_prueba.PNG)

- En este apartado se muestra un código de ejemplo.

![codigo](https://github.com/lupitaBI06/AzureFunctions/blob/main/imagenes/codigo.PNG)

- Podemos probar y ejecutar el código, si modificamos la entrada "name" nos arroja un mesaje despues de dar en ejecutar.

![probar y ejecutar](https://github.com/lupitaBI06/AzureFunctions/blob/main/imagenes/probaryejecutar.PNG)

Resultado

![resulatdo](https://github.com/lupitaBI06/AzureFunctions/blob/main/imagenes/ejecucion.PNG)

- El código se puede editar a nuestras necesidades, se muestra un ejemplo muy simple de como editarlo, una ves editado se le da en guardar.

![editar](https://github.com/lupitaBI06/AzureFunctions/blob/main/imagenes/editar.PNG)

- Se vuelve a ejecutar el código para ver que se haya modificado correctamente.

![nueva ejecucion](https://github.com/lupitaBI06/AzureFunctions/blob/main/imagenes/nueva_ejecucion.PNG)