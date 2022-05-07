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

![image](https://user-images.githubusercontent.com/54609399/137843471-ce56f2ab-f8f7-4323-be81-f88a436b561d.png)

3 - Instalamos el ejecutable

![image](https://user-images.githubusercontent.com/54609399/137843618-9241b307-2dff-4ba5-bcf4-4b23a811d8e5.png)

4 - Procedemos con la instalación dando click en Next

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

9 - Abrimos una consola de comandos del sistema operativo y comprobamos si tiene node instalado con el comando node -v

![image](https://user-images.githubusercontent.com/54609399/137844458-8e7ac170-f7d7-4e82-b3fa-52cad83f6c35.png)

Tambien podemos usar el comando node --version

![image](https://user-images.githubusercontent.com/54609399/137844513-3599e25c-b98e-49b0-8190-7daeca13ec1d.png)

El sistema operativo nos dice la version instalada de NodeJS

10 - Comprobamos tambien el npm (Node Pakage Manager), administra todo lo que se vaya a instalar de JavaScript en el equipo
como Angular React y otras librerias que instalaremos

![image](https://user-images.githubusercontent.com/54609399/137844630-736958e2-27c1-42e4-b4c9-ba4931489a5c.png)

![image](https://user-images.githubusercontent.com/54609399/137844674-584d7843-b25b-44d5-a13f-7530359c5f1b.png)

11 - Para saber si mongo esta instalado en el equipo vamos a probar si en verdad podemos ejecutar JavaScript sin necesidad del navegador

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

![image](https://user-images.githubusercontent.com/54609399/167241652-54e6501f-055e-4e54-a683-23f8bd7c52f4.png)


![image](https://user-images.githubusercontent.com/54609399/167241425-12d59c21-2ee6-47eb-9165-6044786d8272.png)






```
sudo n latest
```





o instalar la version estable LTS(recomendado)

```
sudo n stable
```

![image](https://user-images.githubusercontent.com/54609399/164295082-20626933-d880-497f-b129-8af4db5ebf0e.png)


4 - Ahora ejecutamos el comando para verificar las versiones

```
sudo node -v
```
```
sudo npm -v
```

![image](https://user-images.githubusercontent.com/54609399/167241652-54e6501f-055e-4e54-a683-23f8bd7c52f4.png)


*** ACTUALIZAR ***

1 - Si queremos actualizar npm en Linux solo debemos usar los siguientes comandos:

```
sudo npm -v
```
```
sudo npm install npm@latest -g
```

![image](https://user-images.githubusercontent.com/54609399/167241595-97d843c6-3234-4a4d-bd53-5969a21563a8.png)

```
sudo npm -v
```

![image](https://user-images.githubusercontent.com/54609399/164297662-09604b5d-b5fc-46e0-8da4-087d0afb9957.png)

