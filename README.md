## Medidas de protección:
## Detección de ataque MITM (ARP poisoning) con Snort


### ¿Qué es un ataque MIMT?

Un ataque **Man in the Middle** o ataque de intermediario es un tipo de ataque destinado a interceptar, sin autorización, la comunicación entre dos dispositivos (hosts) conectados a una red.

Este ataque le permite al ciberdelincuente manipular el tráfico interceptado de diferentes formas, ya sea para escuchar la comunicación y obtener información sensible, como credenciales de acceso, información financiera, etc., o para suplantar la identidad de alguna de las partes.

Para que un ataque MITM funcione correctamente, el ciberdelincuente debe asegurarse que será el único punto de comunicación entre los dos dispositivos, es decir, el ciberdelincuente debe estar presente en la misma red que los hosts apuntados en el ataque para cambiar la tabla de enrutamiento para cada uno de ellos.

### Características principales de un ataque MITM

- El ataque se realiza sobre la transmisión de tráfico o datos entre dos partes, ya sean dos usuarios, o un usuario y un servidor.
- El atacante actúa como intermediario en la comunicación, suplantando la identidad de una de las partes (o de ambas), de forma que los datos siempre pasan por él antes de ser enviados a la otra parte.
- Aunque la información entre ambos host viaje cifrada, el ciberdelincuente puede descifrarla antes de transmitirla a la otra parte.
- Quienes realizan la comunicación no saben que están siendo objeto de este ataque, y creen que se están comunicando entre ellos de forma normal.
- Estos ataques son muy peligrosos y difíciles de detectar.
- El ciberdelincuente puede decidir si el mensaje interceptado continuará, si lo hará con la misma información o si lo hará con otro contenido modificado que pudiera suponerle una ventaja o beneficio.

### Tipos de ataques

Los ataques MITM tienen diferentes modalidades que dependen de la técnica empleada:

- Puntos de acceso wifi abiertos o con baja seguridad

Los puntos de acceso wifi públicos o con bajo nivel de seguridad pueden suponer un riesgo en el que un atacante de forma deliberada permite la conexión para poder efectuar un ataque de “Man in the middle”.

Otra modalidad consiste en imitar el nombre de una red cercana (SSID) para crear confusión y que algunas personas conecten por error a ella, además muchos dispositivos están configurados por defecto para conectar sin preguntar, conectándose automáticamente a las redes abiertas más cercanas o cuyo nombre SSID es igual.


- Redes locales (LAN)

Las redes locales (Local Area Network LAN) de las empresas también son vulnerables a este tipo de ataques.

El atacante deberá tener acceso a la red local corporativa, donde podrá lanzar un ataque que consistirá en engañar a los equipos de la red local haciéndoles creer que es un dispositivo legítimo de la misma y forzando a que todo el tráfico generado pase a través del dispositivo controlado por el ciberdelincuente.

El acceso a las redes locales puede ser llevado a cabo de forma física, por ejemplo con un ordenador o mediante malware, infectando por ejemplo determinados servidores y pudiendo manipular sus respuestas.

- Software de navegación anticuado.

Por otro lado, los atacantes también aprovechan las vulnerabilidades de los navegadores obsoletos o no actualizados, por lo que debemos prestar especial atención.
