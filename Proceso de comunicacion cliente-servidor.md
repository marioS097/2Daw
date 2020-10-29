# Proceso de comunicación cliente/Servidor

1.	En el navegador hacer una petición de una página web
2.	La petición es mandada mediante un protocolo htttp o https
3.	Llega la petición a la tarjeta de red
4.	El dns traduce la dirección web en una dirección IP 
5.	Según el protocolo saldrá por un puerto u otro (80 o 446).
6.	Llega al router donde será enrutado y manda la petición al servidor destino o a otro router que lo reenviará hasta que encuentre el destino
7.	Llega al servidor
8.	Buscará la información en sus memorias (caché, interna) o en otros sitios como su red local, BBDD o otros servidores
9.	Una vez encontrado el recurso, será devuelto al cliente mediante routers
10.	Con el recurso en el ordenador local, el navegador lo mostrará
