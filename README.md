# falabella-challenge
C.R.U.D test
Proyecto CRUD realizado como prueba para Falabella.

# El siguiente proyecto fue construido en las siguientes tecnologias:

- Gradle 6.0.1
- Java 11
- Springboot 2.5.5
- 
El proyecto cumple con las primisas dadas en las cuales se debe ejecutar el codigo para la creacion, edicion, eliminacion y demas tareas requeridas por el challenge.

# Para el levantamiento del proyecto.
- Descargar el proyecto localmente, es decir clonar el repositorio github.
- Abrir en IDE de su preferencia
- Correr el proyecto en el IDE de preferencia.

# Se agrego swagger para la visualizacion y utilizacion de los servicios
A forma de documentacion para la exposicion de los endpoints requeridos se expone en la aplicacion la siguiente url:
http://localhost:8080/swagger-ui/index.html#/ProductController/

# Request de ejemplo para probar el servicio de creacion:

http://localhost:8080/api/v1/products: 
{
  "brand": "Pool",
  "id": 1,
  "name": "franela",
  "otherImages": [
    "https://www.google.com/search?q=real+madrid&rlz=1C1GCEU_enAR932AR933&tbm=isch&sxsrf=AOaemvLkLeErODyTJvM87zd7kc8OywNcAQ:1634158434828&source=lnms&sa=X&ved=2ahUKEwibr47IosjzAhXVppUCHbLJCQIQ_AUoAnoECAEQBA&biw=1280&bih=609&dpr=1.5#imgrc=Fhtd1CCWY9MJiM"
  ],
  "price": 123,
  "principalImage": "https://www.google.com/search?q=real+madrid&rlz=1C1GCEU_enAR932AR933&tbm=isch&sxsrf=AOaemvLkLeErODyTJvM87zd7kc8OywNcAQ:1634158434828&source=lnms&sa=X&ved=2ahUKEwibr47IosjzAhXVppUCHbLJCQIQ_AUoAnoECAEQBA&biw=1280&bih=609&dpr=1.5#imgrc=Fhtd1CCWY9MJiM",
  "size": "12",
  "sku": "FAL-12314222"
}

# Autor
 
 [Eleonay Bermudez](https://www.linkedin.com/in/eleonay-leandro-bermudez-063a4915a/)
