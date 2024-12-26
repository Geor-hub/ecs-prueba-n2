# ecs-prueba-n2
Se describirá el proceso de Integración Continua y Despliegue Continuo que automatiza y despliega una aplicación usando el ECS de AWS.
Se utilizarán variables de entorno seguras para acceder a AWS.
A través del Docker se crea una imagen y se etiqueta.
Se procede a subir la imagen creada al ECR.
Para finalizar se actualiza el ECS con nueva task definition que despliega una nueva versión.
