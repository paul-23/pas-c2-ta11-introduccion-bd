# TA11 – Introducción a Bases de dades
Instalar y configurar lo siguiente:
### 1. VirtualBox
![image](https://user-images.githubusercontent.com/62121921/227792892-3cc8f751-4a89-441c-a23a-cb92264e2ecb.png)
***
### 2. Sistema operativo Fedora Server
![image](https://user-images.githubusercontent.com/62121921/227792925-f902a55d-c65e-43b1-baca-5a9b10b4f622.png)
![image](https://user-images.githubusercontent.com/62121921/227792936-660e5273-89ff-4c21-b645-8b45dda4ecd1.png)

Creamos un usuario nuevo: \
![image](https://user-images.githubusercontent.com/62121921/227792953-a9234a26-94a7-48f0-9e8f-4bbc50906be9.png)
![image](https://user-images.githubusercontent.com/62121921/227792961-42c9481d-217c-4bf6-8b7b-6c70648133cd.png)
![image](https://user-images.githubusercontent.com/62121921/227792965-d43debc0-f12e-45b9-86c9-f510f68c42a6.png)
***
### 3. MySQL 8
Hacemos un update para actualizar los paquetes con el servidor \
![image](https://user-images.githubusercontent.com/62121921/227792976-d4e82fa1-0c6b-4731-b6e1-5a5e5740258a.png)

Instalamos el repositorio en Fedora 37 \
![image](https://user-images.githubusercontent.com/62121921/227792979-18a56444-2b6d-4e55-970c-0568f4d6a3e3.png) \
![image](https://user-images.githubusercontent.com/62121921/227792984-9ab7711e-221f-4f32-8582-13ecb69a79e5.png) \

Instalamos MySQL 8 \
![image](https://user-images.githubusercontent.com/62121921/227792994-cb9372ee-37ab-4882-a8c2-a43019396ef8.png)
![image](https://user-images.githubusercontent.com/62121921/227792998-938908c4-15f9-4766-a582-c26030dacaf5.png)

Generamos una contraseña temporal \
![image](https://user-images.githubusercontent.com/62121921/227793384-5ec3b6eb-e5dd-4a75-9bec-037c2b0b47d9.png)

Usamos la contraseña creada anteriormente para ejecutar el siguiente comando: \
![image](https://user-images.githubusercontent.com/62121921/227793400-b8382253-e75e-473b-a30e-4bf6deb31791.png)

Actualizamos la contraseña: \
![image](https://user-images.githubusercontent.com/62121921/227793411-1ecd21e4-958b-4ad2-896b-e608565c2a81.png)

Seguimos los pasos indicados por pantalla: \
![image](https://user-images.githubusercontent.com/62121921/227793420-587e430d-1fc3-474e-b1f1-70fb535eddc4.png)
![image](https://user-images.githubusercontent.com/62121921/227793430-03bb25c4-dab5-464e-bda4-2a6910f147c1.png)

Iniciamos el prompt de MySQL \
![image](https://user-images.githubusercontent.com/62121921/227793443-69b18c87-acf4-48ed-bc7a-0aea55c839dc.png)

Cambiamos la contraseña del usuario root \
![image](https://user-images.githubusercontent.com/62121921/227793451-2add177c-f6cd-4eaa-b8cb-5b18939475dd.png)

Añadimos los servicios de MySQL al firewall \
![image](https://user-images.githubusercontent.com/62121921/227793471-cbd2f70e-0fec-4fde-bf82-cd2d5a2dcbb0.png)
![image](https://user-images.githubusercontent.com/62121921/227793475-e256777e-4dbd-47f0-a126-fa14f376094f.png)

Finalmente reiniciamos el servicio de MySQL \
![image](https://user-images.githubusercontent.com/62121921/227793495-5dcab235-6dd9-4054-b20d-d6616957ddb0.png)
***
### 4. MySQL Workbench
Instalamos MySQL Workbench y nos conectamos al servidor creado anteriormente. \
![image](https://user-images.githubusercontent.com/62121921/227793532-177fe6d2-6e80-4bda-99cb-9a0656c0f88f.png)
![image](https://user-images.githubusercontent.com/62121921/227793534-c1b99f81-c48f-41fb-8b2d-cf29f53dfb1d.png)
