## ¿Qué es Ansible?
Ansible es una herramienta de automatización que es utilizada para configurar, desplegar aplicaciones, orquestación o aprovisionamiento. 
Ansible permite hacer tareas repetitivas en todas las máquinas de la red de forma sencilla y segura

Con Ansible se pueden automatizar configuraciones de base de datos, almacenamiento, redes, firewall. Se asegura que todos los paquetes necesarios y el resto del software sean coherentes en el servidor para ejecutar la aplicación

Es muy sencillo instalar y configurar una aplicación utilizando Ansible
Simplemente basta con enumerar tareas que hay que realizar escribiendo playbooks y Ansible se encarga de ejecutar las tareas en cada dispositivo

Ansible también organiza las aplicaciones instaladas por playbooks para que se relacionen correctamente entre si.

### Inventory
Es una colección organizada de máquinas, hosts o nodos. 
Esta colección organizada ayuda a que los playbooks puedan ejecutarse de una manera mas ordenada

### Playbooks
Permite gestionar uno o varios servidores o máquinas. 
Playbooks utiliza "inventory" para ejecutar las tareas de manera ordenada en las máquinas

Lo podriamos llamar como el lenguaje de automatización de Ansible. Es un archivo simple con un conjunto de instrucciones. Aqui definimos que tareas queremos que realice Ansible

Son archivos simples escritos en código YAML.

## * Hosts y usuarios
Los hosts se agregan al inventory a través de sus direcciones IP.


