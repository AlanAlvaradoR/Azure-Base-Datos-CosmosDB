# Azure-Base-Datos-CosmosDB
Creación de base de datos cosmos DB en Azure, modificación y adición de datos

![Logo de cosmosdb](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/cosmosdb.jpg)

## Requisitos

- Cuenta de [Azure](https://portal.azure.com/) con suscripción activa
- Computadora con Windows, Linux o MacOs

---------------------------------------------------------

## Pasos

- Se inicia sesión en la página de [Azure](https://portal.azure.com/)

![P5-0](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/inicio%20Azure.PNG)

- Se busca "Azure Cosmos DB" y se presiona enter

![P12-1](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-1.PNG)

- Se selecciona "crear" en la esquina superior izquierda

![P12-2](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-2.PNG)

- Se selecciona "crear núcleo SQL"

![P12-3](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-3.PNG)

- En el apartado de "grupo de recursos" se selecciona "crear nuevo", se le da un nombre y se da click en "aceptar"

![P12-4](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-4.PNG)

- Se le coloca un nombre de la cuenta, se selecciona la ubicación y se da click en "Revisar y crear"

![P12-5](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-5.PNG)

- Se espera que se valide la configuración y se habilite le botón "crear". Una vez habilitado se da click en él.

![P12-6](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-6.PNG)

- Se mostrará una ventana como la siguiente mientras se realiza la implementación:

![P12-7](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-7.PNG)

- Una vez completada, se muestra la siguiente ventana, se da click en "ir al recurso"

![P12-8](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-8.PNG)

- Se selecciona el lenguaje en el cual se va a trabajar, en este caso node.js

![P12-9](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-9.PNG)

- Se da click en "crear el contenedor items"

![P12-10](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-10.PNG)

- Una vez termine, se da click en "descargar"

![P12-11](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-11.PNG)

- Se da click en "Abrir el explorador de Archivos"

![P12-12](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-12.PNG)

- Se abrirá una ventana como la siguiente, se da click en "to do list", luego en "items" y finalmente en "items"

![P12-13](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-13.PNG)

- Se da click en "Nuevo item"

![P12-14](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-14.PNG)

- Se mostrará una ventana como la siguiente, donde se puede escribir el código correpondiente para modificar la base de datos

![P12-15](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-15.PNG)

- En este caso se escribe el siguiente código y se da click en "guardar"

```SQL
{
"id": "1",
"nombre": "Alan",
"apellido": "Alv"
}
```
![P12-16](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-16.PNG)

- Se mostrará un cambio al código que hermos escrito, indicando que ya se ha implementado, damos click en "Nuevo item" para agregar otro item

![P12-17](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-17.PNG)

- Ahora se escribe el siguiente código y se da click en guardar

```SQL
{
"id": "1",
"nombre": "Alan",
"apellido": "Alv",
"email": "ceinnova10934@gmail.com"
}
```
![P12-18](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-18.PNG)

- Se da click en el ícono mostrado en la siguiente imagen:

![P12-19](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-19.PNG)

- Se escribe le siguiente código para consultar la base de datos y se le da click en "ejecutar":

```SQL
SELECT * FROM c
```

![P12-20](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-20.PNG)

- Al ejecutar el comando aparecerá un resultado en la parte baja:

![P12-21](https://github.com/AlanAlvaradoR/Azure-Base-Datos-CosmosDB/blob/main/imagenes/P12-21.PNG)







