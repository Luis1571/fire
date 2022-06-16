# fire
El proyecto Fire es un ejemplo de prueba de un proyecto Angular desplegado con el Hosting de Firebase.
Para el despliegue se ha seguido los pasos del video:
https://www.youtube.com/watch?v=GwWIlMKUCJo

Sin embargo, tiene ciertas peculiaridades el pryecto se despliega en la carpeta dist. Al despliegue  ha creado dos carpetas dist una fuera del proyecto (es la que hará el despliegue)    y otra dentro.
Hay una pequeña falla. Por ello hay que seguir los siguientes pasos:
•	ng build (crea la carpeta fire  que lleva el nombre del proyecto, dentro de la carpeta dist de dentro del proyecto)
•	mover la carpeta fire del dist de dentro del proyecto al directorio dist de fuera del proyecto 
•	Ejecutar el comando “firebase deploy”

Hacer estos pasos cada vez que se construya  y se hayan querido realizar cambios
URL: https://udemy-tarjeta.web.app/
