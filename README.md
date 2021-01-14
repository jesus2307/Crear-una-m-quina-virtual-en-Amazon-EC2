# iaw-practica-12

Crear una máquina virtual en Amazon EC2.

La Amazon Machine Image (AMI) que vamos a seleccionar para esta práctica será la última versión de Ubuntu Server.
https://bitnami.com/stack/drupal/cloud/aws/amis

https://bitnami.com/redirect/to/1303349/drupal-9.1.2-1-amidebian-x64-hvm-ebs-nami?region=us-east-1

 añadimos 2g de ram
 
Cuando esté creando la instancia deberá configurar los puertos que estarán abiertos para poder conectarnos por SSH y para poder acceder por HTTP/HTTPS.

SSH (TCP)22
HTTP (TCP)80
HTTPS (TCP)443

Crear un par de claves (pública y privada) para conectar por SSH con su instancia.
seguimos la guia 
https://www.drupal.org/docs/user_guide/en/index.html

64.161045] bitnami[538]: #########################################################################
[   64.167011] bitnami[538]: #                                                                       #
[   64.173209] bitnami[538]: #        Setting Bitnami application password to 'Xvfh8qpcQ2NN'         #
[   64.180585] bitnami[538]: #        (the default application username is 'user')                   #
[   64.187358] bitnami[538]: #                                                                       #
[   64.193578] bitnami[538]: #########################################################################

Realizar la instalación del módulo de Drupal de Bitnami sobre la máquina. Puede encontrar más información sobre cómo realizar este paso en el archivo README del instalador del módulo de Drupal de Bitnami.
