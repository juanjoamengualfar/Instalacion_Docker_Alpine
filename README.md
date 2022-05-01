### 1. Al entrar se nos pedirá que asignemos un usuario y contraseña al dispositivo.

![1](https://user-images.githubusercontent.com/91874635/166165685-add791c9-e358-4928-a839-a5f9977f0934.png)

### 2. Usando el comando *setup-alpine* elegimos el diseño del teclado y la zona horaria que queremos.

![2](https://user-images.githubusercontent.com/91874635/166165696-dbb73830-7182-49bd-b32c-e41fa112f139.png)

### 3. Nos pedirá que proporcionemos los siguientes 3 *espejo* que queremos, *ssh* que queremos y *disco duro* donde queremos que se instale alpine.

![3](https://user-images.githubusercontent.com/91874635/166165721-f2b9d109-43b5-483e-93c2-4013b01a3a9a.png)

## Docker

#### 1. Con el comando *vi /etc/ssh/sshd_config* accederemos a la configuración de ssh.

![2 2](https://user-images.githubusercontent.com/91874635/166165751-a23d22ed-ce21-473c-bb69-c9334b2e9a9d.png)

### 3. Abrimos git e ingresamos el comando ssh root@ y la contraseña correspondiente

![3 1](https://user-images.githubusercontent.com/91874635/166165832-dcf99b88-5da7-4d14-b634-b760e7f4be74.png)

### 5. Con el comando *apk add docker* se instalará Docker

![5](https://user-images.githubusercontent.com/91874635/166165873-8253f529-bfb7-4906-b529-5903e3385f8b.png)

### 7. Ponemos el comando *docker run hello-world* y asi comprobaremos que Docker se ha instalado correctamente

![7](https://user-images.githubusercontent.com/91874635/166165891-62324e34-4f28-47e8-8763-a116e092eb08.png)
