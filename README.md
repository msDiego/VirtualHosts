# VirtualHosts

Dentro de la terminal de Ubuntu, hemos ejecutado sudo apt install nginx para instalar el programa
Una vez instalado, hemos actualizado para después upgradear desde terminal

<img width="407" alt="9376bb38cfaf130ce1e85bab6c5db08d" src="https://user-images.githubusercontent.com/91744554/166510052-88e67c30-8433-4f2b-bf9d-b1f02427fdf7.png">

Una vez acabado el upgrade, la terminal procede a desempaquetar los paquetes requeridos para la descarga correcta de nginx

<img width="403" alt="33a977211602972d9fa7f0021726ca1b" src="https://user-images.githubusercontent.com/91744554/166510355-d3069a90-b62a-4b46-89af-7fa16a07b6ff.png">

Una vez tenemos instalado, en nuestro navegador podemos introducir la ip de la máquina de nginx para ver la página de bienvenida

<img width="496" alt="385019cca815897f677b2cef3ecd3924" src="https://user-images.githubusercontent.com/91744554/166514339-a7a2d575-71d9-4ba0-b3e3-1afc69bad16a.png">

Editaremos el directorio de nginx, donde en el directorio 'sites-available' nos pondrá 'default'

<img width="399" alt="e0d5bb9e2f2cf1584d2dfdc88c6b4e18" src="https://user-images.githubusercontent.com/91744554/166518660-3e672835-c7aa-4d33-a7ca-b83b8a956b9b.png">

Dentro de los directorios creados dentro de var/www tenemos carpeta1 y carpeta 2. Dentro de carpeta1 descargaremos el código fuente de uno de los juegos:

<img width="407" alt="23c84d57ad612942cb26087f369e9b76" src="https://user-images.githubusercontent.com/91744554/166522824-87baac91-74e2-4256-a90e-c739a7c471d3.png">

Y quedaría así:

<img width="399" alt="0e9d6f268b65882404cdf386a45a7e2a" src="https://user-images.githubusercontent.com/91744554/166522861-d6fd90bf-f60b-442a-95c1-e39dce387043.png">

Hacemos lo mismo en carpeta2:

<img width="400" alt="f60868bddb7e1c10b7f16dfa6bd3ef98" src="https://user-images.githubusercontent.com/91744554/166523177-b281b28a-3b39-4c29-8b28-997e6dfaf2aa.png">

<img width="400" alt="f60868bddb7e1c10b7f16dfa6bd3ef98" src="https://user-images.githubusercontent.com/91744554/166523298-c34d0de1-007b-4bbc-b47f-f52fbb3d90ec.png">

Ponemos los subdominios deseados en el directorio de 'sites-available':

<img width="397" alt="66cd536450ac521b331a5b02050b9caa" src="https://user-images.githubusercontent.com/91744554/166523660-2d9c9ff9-93b7-45c9-aa10-cfef3245c3a5.png">

Cambiamos las direcciones correspondientes:

<img width="394" alt="0fce14b9c144e016851b81d14aa29ef1" src="https://user-images.githubusercontent.com/91744554/166524356-abb52871-a0be-4dd8-9927-00deabebfc5a.png">
