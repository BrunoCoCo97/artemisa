# Intro

hola

## Capitulo 1

Podríamos decir que todo inicia con el siguiente segmento de código:

```
<html>
  <head>
    <title>Hola</title>
  </head>
  <body>
    <h1>Hello</h1>
  </body>
</html>
```
  
Si gardamos este código en un archivo llamado ```index.html``` y lo abrimos con nuestro navegador favorito, podremos visualizar algo muy similar a esto: 

<img width="499" alt="imagen" src="https://user-images.githubusercontent.com/17259655/210629548-97f7499a-7c61-4851-b2ed-fe88e5f488df.png">

De lo anterior, podemos observar varias cosas interesantes:
- El navegador está "interpretando" el código que está en el interior del archivo ```index.html``` y de esa forma presenta un texto con ciertas características de tamaño, color y posición determinadas.
- El archivo ```index.html``` vive en nuestro equipo y debemos editarlo localmente para producir un cambio visible en el navegador
- La sintáxis para crear el archivo ```index.html``` es muy particular y conocida como Hyper Text Markup Lanlguage (HTML)

En el dia a dia de nuestro quehacer, recibimos archivos con estructura HTML de máquinas remotas que igualmente son interpretados por nuestro navegador, aunque el HTML de tales "paginas" es en general, mucho mas complejo y sofisticado que el de nuestro ejemplo inicial. Sin embargo, la forma de acceder a tales archivos (o páginas) al ya no ser local, sólo podrán ser encontradas a través del "nombre" de nuestra organización y luego, posiblemente, una ruta definida por símbolos ```/``` que, por ejemplo, se ve de esta manera: ```https://www.google.com/index.html```

El "nombre" de nuestra organización se llama "nombre de dominio" e identifica a un sitio de manera única en todo el mundo. Actualmente hay mas de 360 millones de nombres de dominio registrados en internet. Un nombre de dominio puede ser adquirido por tan sólo unos cuantos dólares al año. Con el tiempo y gracias a su contenido, los nombres de dominio suben de valor. Actualmente hay nombres de dominio que valen una fortuna. Por ejemplo, el sitio cars.com fué vendido en 872 millones de dólares en el año de 2017.

Un nombre de dominio "por si solo" no sirve para nada. Una vez adquirido, es necesario "que apunte" a una máquina que tendrá contenido (es decir, páginas como la primera que mostramos) que sea de interés al público mundial. El procedimiento para que un dominio "apunte" a una máquina con contenido es relativamente sencillo: 

- Se le indica al vendedor de dominios (también conocido como "registrar") quiénes son los servidores de nombre de dominio que resolverán la liga. 
- Posteriormente, se le indica a cada uno de esos servidores de dominio cuál es la dirección IP de la máquina que resuelve.

De lo anterior, cada vez que alguien navega en su computadora a algún sitio, el "registrar" que vendió el sitio simplemente indica cuál es el servidor de dominio que sabe la IP del sitio buscado para que se le pregunte a él tal IP. Al final del dia, todo en internet son IP's, pero los nombres de dominio nos facilitan la vida y además nos proporcionan beneficios adicionales que veremos mas adelante, como su uso en los "reverse proxies".

Y a todo esto, te estarás preguntanso: ¿Qué es una dirección IP? Pues una IP (dirección del Protocolo de Internet) es un conjunto de números que determinan de manera única una máquina en internet. Actualmente existe el prtocolo IP v4 y el mas reciente IP v6. El mas conocido (IPv4) se podia identificar fácilmente por su estructura: XX:XX:XX:XX en donde cada XX podia variar entre 0 y 255.

En la actualidad hay tantos dispositivos que la cantidad de direcciones IP que se podían formar con el patrón de IPv4 ya se está agotando y por tal motivo, ha nacido el proocolo IPv6.

En este curso usaremos aun el protocolo IPv4.




