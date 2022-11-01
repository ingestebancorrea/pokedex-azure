<h1> Despliegue de aplicación pokedex en Azure</h1>

En primer lugar, debemos crear un recurso que se hara mediante
<img src="https://user-images.githubusercontent.com/111609882/199324900-866f8021-1a9e-47bf-b83d-35e67db0f769.png">

Luego, se debe buscar el recurso con el nombre Static Web Apss que permitira compilar aplicaciones nuestra aplicación web en Azure desde un respositorio de código.
<img src="https://user-images.githubusercontent.com/111609882/199325206-bf438407-4aab-4ab7-af1f-9205d9234cc0.png"
     
Posteriormente, cuando nos encontremos posicionados en el servicio descrito anteriormente se debe presionar en create
<img src="https://user-images.githubusercontent.com/111609882/199325402-f3a02dab-4568-4cfe-99c3-900f76b463a8.png">

Por otro lado, a partir de este punto inicia la configuración y creación de nuestra aplicación web estatica.
<img src="https://user-images.githubusercontent.com/111609882/199325713-b9b2d3d4-9e72-46a0-b24d-bf68efd39595.png">

Seguir los siguientes pasos:
1. Seleccionar grupo
<img src="https://user-images.githubusercontent.com/111609882/199325878-f4d86291-7ba7-4f02-ab19-b517dcf65e1b.png">

2. Enlazar con repositorio github en el cual se encuentra el proyecto
<img src="https://user-images.githubusercontent.com/111609882/199326021-dedc8b6e-955b-4328-a036-42c7f1380d4b.png">

3. Seleccionar la estructura del proyecto en nuestro caso Angular.
<img src="https://user-images.githubusercontent.com/111609882/199326161-c2a977e8-1f2f-4435-817b-644cc51ff931.png">

4. Luego, presionamos en revisar y crear en este proceso se validan las especificaciones de la creación de la app web estática
<img src="https://user-images.githubusercontent.com/111609882/199326264-68c6fc2e-85a9-4b74-a386-b07e621b26a4.png">

5. Finalmente, si todo esta bien se procede con la creación y deployment en Azure
<img src="https://user-images.githubusercontent.com/111609882/199326481-f2fa9367-fd3c-41d9-9138-24734a9cf7c8.png">

Siguiendo los pasos descritos anteriormente nos lleva a confirmar el despliegue de la app.
<img src="https://user-images.githubusercontent.com/111609882/199326772-0cc5ebe1-f786-45d0-bb0e-f9f6f5d7a7b4.png">

En esta página se pueden visualizar el estado e información del sitio publicado.
<img src="https://user-images.githubusercontent.com/111609882/199331488-0856b4d3-3a04-4ee0-82bf-f8dce0e79896.png">

En consecuencia, ingresamos a la url y se procede abrir la app subida o publicada en Azure.
<img src="https://user-images.githubusercontent.com/111609882/199331702-929a11db-51c8-4c2c-8fe9-79ced075ba12.png">
<img src="https://user-images.githubusercontent.com/111609882/199331924-685a1704-b70c-4b82-9772-d56ccf370fe0.png">

***Nota***
<br>
En GitHub se puede verificar el estado del despliegue en el apartado actions
<img src="https://user-images.githubusercontent.com/111609882/199332185-999574b4-af8c-4497-9423-7994440ddfd6.png">

Posteriormente, se puede observar los flujos de trabajo (workflow) en Github.
<img src="https://user-images.githubusercontent.com/111609882/199332280-10a927bf-3a07-449e-bb9a-c5c00ffbed40.png"> 

Por utlimo, podemos ver que el despliegue fue exitoso en la siguiente imagen.
<img src="https://user-images.githubusercontent.com/111609882/199332450-39240825-8e04-4a7b-bf30-966ace0754f4.png">
