# G6 - MISO4206

Este proyecto contiene la información relacionada con el proyecto del curso de maestría MISO4206 en el cual se plantea una arquitectura de software ágil para la aplicación Nidoo.

En la [wiki](https://github.com/MISO-4206/201820-Repo-Grupo-06/wiki) del repositorio se encuentra toda la información relevante. 

## Integrantes - Grupo 6

- Alejandro García - 201326489
- Alex Chacón - 200327603
- Gabriel Pinto - 201515275
- Jair García - 201210425
- José Álvarez - 201628933

### Arquitecturas Ágiles - Grupo No. 6. Proyecto contruido a partir de la arquitectura propuesta por Serverless Architecture with Java 8, AWS Lambda, and Amazon DynamoDB 


![Architecture](images/architecture.jpg)


### Despliegue de la aplicación:

Se deben seguir los siguientes pasos para desplegar la aplicación:

-  Crear la colección Parqueadero en DynamoDB con los siguientes atributos y llaves.

![Dynamo](images/ParqueaderoDynamo.png)

CoordenadaX: PartitionKey
CoordenadaY: SortKey

-  Crear las funciones lambda, una función por cada manejador definido en la clase ParqueaderosFunctions class.

-  Crear un API Gateway.  
