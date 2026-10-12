# odhst-control-secretos

Fixture de prueba ODHST, clave falsa.

`clave-falsa.pem` es una clave RSA generada para este repositorio y no se usa en ningún sitio.
Existe para comprobar que el gate de secretos del build ODHST pone el pipeline en rojo
cuando un repo declarado en `repos.yaml` mete una clave privada en la imagen.
