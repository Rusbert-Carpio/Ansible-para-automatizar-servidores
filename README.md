📘 README — Práctica: Automatización con Ansible + Docker

Este proyecto demuestra cómo automatizar la configuración de múltiples servidores Ubuntu usando Docker, WSL y Ansible.
La práctica consiste en crear 5 servidores Ubuntu dentro de contenedores, configurarlos vía SSH y luego automatizarlos completamente con Ansible.

🚀 Objetivos de la práctica

Crear una imagen customizada de Ubuntu con:

SSH server instalado

Usuario ansible con password ansible

Privilegios sudo sin contraseña

Crear 5 servidores usando Docker Compose

Instalar Ansible en WSL

Configurar inventario y ansible.cfg

Automatizar configuraciones:

Actualizar paquetes del sistema

Crear usuario itla

Crear carpeta /home/itla/app

Crear archivo hola.txt

Instalar aplicaciones cowsay y htop

🗂️ Estructura del proyecto
practica-ansible-docker/
├─ Dockerfile
├─ docker-compose.yml
└─ ansible/
   ├─ ansible.cfg
   ├─ inventory.ini
   └─ playbook.yml
