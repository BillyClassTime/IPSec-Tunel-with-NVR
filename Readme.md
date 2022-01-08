# Mikrotik IpSec



Site 1

Mostoles Central



Site 2 

Mostoles Paseo de Arroyo Molinos



## Configuración de las reglas del Firewall

![](Firewall Rules.png)



## Configuración reglas de NAT

![](Nat Rules.png)



## Cámaras en site 1

![](03-Grandstream.png)

## Cámaras en site 2

![](02-Grandstream.png)

## Configuraciones para el IPSec

![](IPSec control grabador.png)

Lo que esta resaltado es la configuración realizadad, lo que no, lo que viene en el apartado: [Manual:IP/IPsec - MikroTik Wiki](https://wiki.mikrotik.com/wiki/Manual:IP/IPsec#Site_to_Site_IPsec_tunnel)



## Grabador con todas las cámaras

El grabador ahora debería ver las cámaras en el site 1 y 2, pero no ve las del site 2

![](GrabadorConCamaras.png)

No se ha abierto el puerto 8080, al parecer el ONVIF requiere este puerto aunque no se abra en el NAT.

![](GrabadorConCamarasEnVivo.png)