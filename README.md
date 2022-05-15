# Guide_NodeJS_Install

- INSTALACIÓN EN WINDOWS (10 Y 11)
- INSTALACION EN LINUX (UBUNTU 20.04.4 LTS Y 22.04 LTS)

________________________________________

**** INSTALACIÓN EN WINDOWS (10 Y 11) ****
________________________________________

NodeJS es instalar JavaSctipt en el sistema operativo
el front utiliza javascript para los navegadores y eventos en las paginas ahora vamos a usar JavaScript para el backend
por eso NodeJS se instala para permitirnos esto.

1 - Vamos a la página oficial de de nodeJS https://nodejs.org/es/

2 - Descargamos la version LTS (Long Time Support) osea mas tiempo de soporte y menos errores que la otra la version mas reciente puede tener muchos errores

![image](https://user-images.githubusercontent.com/54609399/168495034-e454e288-7528-4cf6-a3a5-f20bcde717d8.png)

3 - Instalamos el ejecutable

![image](https://user-images.githubusercontent.com/54609399/168495061-ac68ca8a-1c4d-4973-9153-9237dd950f37.png)

4 - Procedemos con la instalación dando click en Next (Puede que tarde un poco en aparecer habilitado el next)

![image](https://user-images.githubusercontent.com/54609399/137843653-3bfdfd22-a14e-43c6-bcdb-7a3f9eecb5bf.png)

5 - Aceptamos los terminos y damos siguiente

![image](https://user-images.githubusercontent.com/54609399/137843870-1799dac2-76c2-49b3-9f30-8e9035109f4a.png)

6 - Damos siguiente sin cambiar la ubicacion hay que dejarlo en la raiz osea el C

![image](https://user-images.githubusercontent.com/54609399/137843895-e463ac36-d8dc-4422-8285-3d66474b46e0.png)

Tambien damos siguiente sin modificar nada

![image](https://user-images.githubusercontent.com/54609399/137843936-5e8ab91d-f264-428b-a080-fc18060f5864.png)

Tambien damos siguiente sin modificar nada

![image](https://user-images.githubusercontent.com/54609399/137843982-346d24f2-6873-488c-bf99-387be19e763d.png)

damos click en install para iniciar el proceso

![image](https://user-images.githubusercontent.com/54609399/137844052-63301c4c-f93d-4bcd-ab8e-92f07b18ea05.png)


7 - se inicia el proceso y esperamos

![image](https://user-images.githubusercontent.com/54609399/137844087-9652839c-5297-424b-b712-ca54c0275fc4.png)

8 - damos click en finish

![image](https://user-images.githubusercontent.com/54609399/137844135-8ae0d94f-df54-4fdf-aaf8-b098a83202b4.png)

Con esto ya tenemos instalado NodeJS en el equipo ahora nuestro PC lee JavaScript sin necesidad de un navegador

9 - Abrimos una consola de comandos del sistema operativo y comprobamos si tiene node instalado con el comando node -v o node --version para comprobar que si quedo instalado

(Recomendado) comando abreviado
```
node -v
```
comando completo
```
node --version
```

![image](https://user-images.githubusercontent.com/54609399/168495204-f8cc9731-45b3-4935-a794-f633344f8fe4.png)


El sistema operativo nos dice la version instalada de NodeJS

10 - Comprobamos tambien el npm (Node Pakage Manager), administra todo lo que se vaya a instalar de JavaScript en el equipo
como Angular React y otras librerias que instalaremos

(Recomendado) comando abreviado
```
npm -v
```
comando completo
```
npm --version
```

![image](https://user-images.githubusercontent.com/54609399/168495300-8ce8a1c0-9676-44a6-8bb0-b5eba6ad7c69.png)

NOTA: npm siempre suele instalarce en una version anterior a la estable para ello podmeos actualizarlo en la ultima versión de la siguiente manera

- Abrimos la consola cmd en modo administrador y ejecutamos el siguiente comando

```
npm install -g npm-windows-upgrade
```

![image](https://user-images.githubusercontent.com/54609399/168495623-79625258-dd1a-4551-bfbc-43382f560c4d.png)

luego ejecutamos el comando que nos indica en verte (el numero de la version se debe poner tal cual como salga en la linea de color verde):

```
npm install -g npm@8.10.0
```

![image](https://user-images.githubusercontent.com/54609399/168495752-b8c8c53b-918c-45a7-837e-8b8fb1260be1.png)

y con esto ya tenemos la versión mas reciente de npm

11 - Para saber si node esta instalado en el equipo vamos a probar si en verdad podemos ejecutar JavaScript sin necesidad del navegador

primero creamos una carpeta en el escritorio llamada PruebaNode

![image](https://user-images.githubusercontent.com/54609399/138186678-4b629919-802b-4100-b71e-840b493ae028.png)

luego abrimos esta carpeta en Visual Studio Code

![image](https://user-images.githubusercontent.com/54609399/138186738-47ccdc9e-f067-4468-bbf3-e5e904c6931b.png)

creamos un archivo script.js

![image](https://user-images.githubusercontent.com/54609399/138186799-4f2779df-aba1-4d29-b85f-6bccd3c2bb4d.png)

dentro del archivo escribimos un console.log con algun mensaje

![image](https://user-images.githubusercontent.com/54609399/138186864-c7f6cb54-0d40-4e11-84c8-d43225655a3f.png)


anteriormente necesitabamos un index.html y un navegador para ejecutar el console.log y ver el mensaje

pero ahora podemos ejecutarlo sin necesidad de nada de eso, solo nuestro sistema operativo basta para ejecutarlo en una consola de comandos

por eso abriremos una consola de comandos en la carpeta, los de mac o linux le dan click derecho y a brir en una terminal

los de windows hacemos lo siguiente

entramos a la carpeta pruebaNode

![image](https://user-images.githubusercontent.com/54609399/138187030-e987c56c-d301-4b50-b54a-86dc06d8ea8b.png)

nos ubicamos en la barra y escribimos cmd y damos ENTER esto nos abre una consola desde la carpeta

![image](https://user-images.githubusercontent.com/54609399/138187083-e0824826-5237-4b84-b7cd-dbaa411735b9.png)

podemos observar que se abrio una terminal con la ruta de la carpeta

![image](https://user-images.githubusercontent.com/54609399/138187155-d13490aa-928c-49ec-a3b4-371eaf8e8f19.png)

escribimos node script.js y damos enter

esto ejecutara el archivo y lo que tenga escrito en el osea ejecuta el javascript como si fuera un navegador

![image](https://user-images.githubusercontent.com/54609399/138187236-8245c040-c84e-43ca-bef6-0f1437a1ee57.png)

![image](https://user-images.githubusercontent.com/54609399/138187324-09377d69-77f6-40df-ac53-926b7ed81c64.png)

tambien lo podemos probar desde la consola del Visual Studio Code

![image](https://user-images.githubusercontent.com/54609399/168495875-52a28d24-7701-4864-bd9b-1dd90632e476.png)


Listo ya tenemos NodeJS listo en nuestro PC


________________________________________

**** INSTALACION EN LINUX (UBUNTU 20.04.4 LTS Y 22.04 LTS) ****
________________________________________

1 - Escribimos en la consola:

```
sudo apt-get install nodejs
```

![image](https://user-images.githubusercontent.com/54609399/167240873-feac90c3-c3dd-40eb-9a3b-c816431d59ba.png)

Nos pedira confirmación con "y" si el sistema operativo esta en ingles o "s" si esta en español.

![image](https://user-images.githubusercontent.com/54609399/167240938-97040ad2-9d87-4064-9991-92e8b1e157b5.png)


2 - Luego instalamos el npm, este comando también nos pedira confirmación

```
sudo apt-get install npm
```

![image](https://user-images.githubusercontent.com/54609399/167241044-cd04f763-d088-4f2f-98b9-1d04ad4430c1.png)

3 - Para probar que ambos quedaron instalados ejecutamos los siguientes comandos.

![image](https://user-images.githubusercontent.com/54609399/167241127-728ab3cf-2c0d-4dd4-a23c-e58cb9e94895.png)

4 - Si nos fijamos en la pagina oficial de NodeJS nos encontramos con una version estable superior.

![image](https://user-images.githubusercontent.com/54609399/167241237-cdff92b8-c391-40ff-9081-22dbf880edcc.png)

5 - Para actualizar nuestra versión instalada realizaremos los siguientes pasos.

Limpiamos cache de npm

```
sudo npm cache clean -f
```

![image](https://user-images.githubusercontent.com/54609399/167241302-0bf4ca46-a232-477d-821e-4e9ced483a6d.png)

Se instala la ultima versión estable de NodeJs

```
sudo npm install -g n
```

![image](https://user-images.githubusercontent.com/54609399/167241339-2e0fc5d9-33b5-4c9f-a30b-e907dfabc4aa.png)

Confirmamos la ultima versión estable de NodeJs

```
sudo n stable
```

EXTRA: Si no requieren la version estable LTS (recomendada), si no que por alguna solicitud necesitan la ultima version de node:

![image](https://user-images.githubusercontent.com/54609399/167242248-b2994b17-d5d0-4402-af2d-5311801f82b6.png)

No ejecutamos el comando *sudo n stable* sino el comando *sudo n latest*

```
sudo n latets
```

6 - Instalamos la ultima versión estable de npm

```
sudo npm install npm@latest -g
```

![image](https://user-images.githubusercontent.com/54609399/167241595-97d843c6-3234-4a4d-bd53-5969a21563a8.png)

7 - Volvemos a verificar las versiones con los siguientes comandos:

```
sudo node -v
```
```
sudo npm -v
```

![image](https://user-images.githubusercontent.com/54609399/167242167-c721b159-1d83-4c9e-b0b9-bad13392ff52.png)

NOTA: Si ejecutamos los comandos

```
node -v
```
```
npm -v
```
![image](https://user-images.githubusercontent.com/54609399/167242076-6052a31f-da68-4f41-a669-47cdc941937b.png)

Podemos ver que si ejecutamos los comandos sin el *sudo* nos muestra un node versión 10 el cual quedo como base de algunos paquetes en ubuntu y el npm no nos muestra resultaso, igualmente las ultimas versiones que salen con el comando *sudo node -v* y *sudo npm -v* son las que el sistema utilizara para el desarrollo.

![image](https://user-images.githubusercontent.com/54609399/167242167-c721b159-1d83-4c9e-b0b9-bad13392ff52.png)

Para confirmar esto podemos pobrar los comandos con *sudo* y sin *sudo* en la consola de Visual Studio Code y nos arrojara las versiones reales, las cuales deben ser las mismas

![image](https://user-images.githubusercontent.com/54609399/167242554-957d6e9f-d5e1-4f91-a226-993f32337f50.png)

Para poder ver esto mismo en la terminala del sistema es facil, ejecutamos los siguientes comandos:

```
sudo apt-get update
```
```
sudo apt-get upgrade
```

Reiniciamos el sistema y luego probamos los comandos y ya deberia estar todo a la par:

```
node -v
```
```
npm -v
```
```
sudo node -v
```
```
sudo npm -v
```
![image](https://user-images.githubusercontent.com/54609399/167242932-456537dc-9043-48a9-ae4d-a4e4ee41d6ce.png)

Ya tenemos todo instalado 
