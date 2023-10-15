# docker
Balanceo de cargas y monitoreo de logs en Nginx

Implementación de un servidor Nginx como proxy inverso y balanceador
de cargas, con dos servidores Apache y un sistema de monitoreo de
registros en Docker.

Configurararemos un balanceo de carga utilizando Nginx
y dos servidores Apache, y al mismo tiempo haremos un monitoreo y un registro de los
logs al servidor Nginx con ayuda de plugin de Grafana llamado Loki y Grafana que nos
permitirá la visualización de los logs. Este enfoque se llevará a cabo utilizando Docker,
encargado del despliegue de los contenedores.
