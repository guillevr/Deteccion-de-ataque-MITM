## Medidas de protección:
## Detección de ataque MITM (ARP poisoning) con Snort


### ¿Qué es un ataque MIMT?

Un ataque **Man in the Middle** o ataque de intermediario es un tipo de ataque destinado a interceptar, sin autorización, la comunicación entre dos dispositivos (hosts) conectados a una red.

Este ataque le permite al ciberdelincuente manipular el tráfico interceptado de diferentes formas, ya sea para escuchar la comunicación y obtener información sensible, como credenciales de acceso, información financiera, etc., o para suplantar la identidad de alguna de las partes.

Para que un ataque MITM funcione correctamente, el ciberdelincuente debe asegurarse que será el único punto de comunicación entre los dos dispositivos, es decir, el ciberdelincuente debe estar presente en la misma red que los hosts apuntados en el ataque para cambiar la tabla de enrutamiento para cada uno de ellos.

### Características principales de un ataque MITM

- El ataque se realiza sobre la transmisión de tráfico o datos entre dos partes, ya sean dos usuarios, o un usuario y un prestador de servicios.
- El atacante actúa como intermediario en la comunicación, esto es, suplanta la identidad de una de las partes (o de ambas), de forma que los datos siempre pasan por él antes de ser enviados a la otra parte.
- Aunque la información entre ambos host viaje cifrada, el atacante la descifra antes de transmitirla a la otra parte.
- Quienes realizan la comunicación no saben que están siendo objeto de este ataque, y creen que se están comunicando entre ellos de forma normal.
