# iaw-practica-12

## Crear una máquina virtual en Amazon EC2.

La Amazon Machine Image (AMI) que vamos a seleccionar para esta práctica será [la última versión de Ubuntu Server](https://bitnami.com/stack/drupal/cloud/aws/amis).

![BIT](https://github.com/jesus2307/iaw-practica-12/blob/main/imagen/1.PNG "BIT")

Para evitar problemas con la instalación vamos a añadir 2 GB de RAM a la instancia EC2.

![BIT](https://github.com/jesus2307/iaw-practica-12/blob/main/imagen/2.PNG "BIT")

Cuando esté creando la instancia deberá configurar los puertos que estarán abiertos para poder conectarnos por SSH y para poder acceder por HTTP/HTTPS.

- SSH (TCP)22
- HTTP (TCP)80
- HTTPS (TCP)443

![BIT](https://github.com/jesus2307/iaw-practica-12/blob/main/imagen/3.PNG "BIT")

## Crear un par de claves (pública y privada) para conectar por SSH con su instancia.

Seguimos la [guía de la documentación oficial](https://www.drupal.org/docs/user_guide/en/index.html).

```
64.161045] bitnami[538]: #########################################################################
[   64.167011] bitnami[538]: #                                                                       #
[   64.173209] bitnami[538]: #        Setting Bitnami application password to 'Xvfh8qpcQ2NN'         #
[   64.180585] bitnami[538]: #        (the default application username is 'user')                   #
[   64.187358] bitnami[538]: #                                                                       #
[   64.193578] bitnami[538]: #########################################################################
```

## Realizar la instalación del módulo de Drupal de Bitnami sobre la máquina.

[En la documentación oficial](https://bitnami.com/stack/drupal/README.txt) encontramos los pasos que tenemos que seguir para realizar la instalación.

A continuación se muestra una captura de pantalla que demuestra que la instalación se ha realizado de forma correcta.

![BIT](https://github.com/jesus2307/iaw-practica-12/blob/main/imagen/4.PNG "BIT")
