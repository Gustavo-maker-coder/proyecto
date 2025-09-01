# Proyecto InnovaSys - Configuración DevOps con Ansible

Este proyecto automatiza la instalación y configuración de **Apache** y **Samba** en un servidor Ubuntu Server 24.04 usando **Ansible** desde un nodo de control Linux Lite.

## Requisitos
- Nodo de control: Linux Lite con Ansible y Git.
- Nodo gestionado: Ubuntu Server 24.04 con SSH habilitado.
- Conectividad entre ambas VMs (VirtualBox): NAT + Red Interna.

## Topología sugerida
- Linux Lite (control): 192.168.56.20/24 (red interna)
- Ubuntu Server (gestionado): 192.168.56.10/24 (red interna)

## Instrucciones de uso
1. Clonar este repositorio:
   ```bash
   git clone https://github.com/tuusuario/proyecto-innovasys.git
   cd proyecto-innovasys
