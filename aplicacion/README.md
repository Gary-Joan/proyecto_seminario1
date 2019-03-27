### EC2
Amazon Elastic Compute Cloud (Amazon EC2) es un servicio web que proporciona capacidad informática en la nube segura y de tamaño modificable. Está diseñado para simplificar el uso de la informática en la nube a escala web para los desarrolladores.

La siguiente imagen muestra un diagrama de lo genera la plantila de VPC que se encuentra en 

[EC2](https://github.com/Gary-Joan/proyecto_seminario1/blob/master/Aplicacion/EC2.yaml)

![alt text](https://github.com/Gary-Joan/proyecto_seminario1/blob/master/imagenes/EC2.jpg)

## OUTPUT EC2
Aqui se muestran las salidas que tiene esta plantilla
+ EC2id1: Se muestra el id de la maquina virutal 1 que se crea.
+ EC2id2: Se muestra el id de la maquina virutal 2 que se crea.

### LOAD BALANCER
Elastic Load Balancing distribuye automáticamente el tráfico de aplicaciones entrantes a través de varios destinos, tales como instancias de Amazon EC2, contenedores, direcciones IP y funciones Lambda. 

La siguiente imagen muestra un diagrama de lo genera la plantila de LOAD BALANCER ya ingresado en la infraestructura 

[LOAD BALANCER](https://github.com/Gary-Joan/proyecto_seminario1/blob/master/APLICACION/LOAD-BALANCER.yml)

![alt text](https://github.com/Gary-Joan/proyecto_seminario1/blob/master/imagenes/LOAD.jpg)

## OUTPUT LOAD BALANCER
Aqui se muestran las salidas que tiene esta plantilla
+ RedisLoadBalancer: Se muestra el id del load balancer que se creo.
+ RedisLoadBalancerUrl: Muestra el url del nuevo load balancer para verificar su usa de la distribucion de carga.
