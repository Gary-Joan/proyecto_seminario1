### VPC
Amazon Virtual Private Cloud (Amazon VPC) le permite lanzar recursos de AWS en una red virtual que haya definido. Dicha red virtual es prácticamente idéntica a las redes tradicionales que se utilizan en sus propios centros de datos, con los beneficios que supone utilizar la infraestructura escalable de AWS.


La siguiente imagen muestra un diagrama de lo genera la plantila de VPC que se encuentra en 

[VPC](https://github.com/Gary-Joan/proyecto_seminario1/blob/master/RED/plantilla-vpc.yaml)

![alt text](https://github.com/Gary-Joan/proyecto_seminario1/blob/master/imagenes/VPC.jpg)

## OUTPUT VPC Y SG
Aqui se muestran las salidas que tiene esta plantilla
+ VPCID: Se muestra el id de la vpc que se crea.
+ AZ1NAME: Muestra el availability zone numero 1 de la infraestructura.
+ AZ2NAME: Muestra el availability zone numero 2 de la infraestructura
+ PUBLICSUBNET1: Muestra el id de la primera subnet publica en zone 1 antes creada.
+ PRIVATESUBNET1: Muestra el id de la primara subnet privada en la zone 1 antes creada.
+ PUBLICSUBNET2: Muestra el id de la segunda subnet publica en la segunda zona antes creada.
+ PRIVATESUBNET2: Muestra el id de la segunda subnet pribada en la segunda zona antes creada.
