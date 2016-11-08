# Ansible [genDevOps]: roles y best-practices

El objetivo de esta práctica es empezar a rodar con la creación de playbooks 
y roles, aplicando en la medida de lo posible las best-practices que hemos visto.

## AWS

El servidor será una instancia de AWS con Ubuntu 16.04 escuchando por el puerto `8080`. 
`tags` al rescate!

# Usuario

Provisionar el servidor con tu usuario nominal y clave pública.

# Nginx

Instalar nginx en la maquina destino, personalizando `index.html` y `error.html`. 
No olvides configurarlo por el puerto correspondiente.

**Se incluye una propuesta de layout con algunas claves en examples/**

