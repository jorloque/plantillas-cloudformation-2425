# plantillas-cloudformation-2425
Plantillas CE modulo despliegue

- <b><u>miprimerec2.yaml</u></b>
Creación de un ec2 con lo mínimo, sin grupo de seguridad, ni vpc, ni subred. En el lab del academy ya le asigna una vpc y una subred por defecto. Comprobad añadiendo un grupo de seguridad que se puede acceder por ssh al ec2

- <b><u>02_ec2_con_gs.yaml</u></b>
Se le añade un grupo de seguridad al ec2.

- <b><u>03_ec2_gs_paramtetro.yaml</u></b>
Se le pasa por parametro la ami del ec2

- <b><u>04_vpc_srpublica_ec2_igw.yaml</u></b>
Se crea una VPC, una subred publica y un internet gateway para dar salida a internet. Además del grupo de seguirdad que arrastramos de ejercicios anteriores.

- <b><u>05_vpc_srpub_srpr_ec2_natgw_igw.yaml</u></b>
Añadimos una subred privada y un nat gateway para que el ec2 de la subredprivada pueda salir al exterior.

- <b><u>06_bucket.yaml</u></b>
Creación de un bucket por plantilla

- <b><u>07_**.yaml</u></b>
Plantilla para ver un balanceador y grupo de autoescalado + alarma.

- <b><u>10-11-12.yaml</u></b>
Plantilla para crear una arquitectura para una webapp con una BBDD

- <b><u>conditions1.yaml</u></b>
Plantilla para explicar las condiciones 

- <b><u>conditions2.yaml</u></b>
Plantilla para explicar las condiciones


- <b><u>maps1.yaml</u></b>
Plantilla para explicar los mapeos

- <b><u>rules1.yaml</u></b>
Plantilla para explicar las reglas
