# Homelab Infrastructure Core Stack 🚀

Repositorio de infraestructura como código (IaC) para la gestión e implementación del core de servicios en el HomeLab personal.

## 🛠️ Servicios Desplegados

* **Portainer**: Gestión visual y control centralizado de contenedores Docker.
* **Pi-hole**: Servidor DNS privado y bloqueo de anuncios/telemetría a nivel de red.
* **ownCloud (oCIS)**: Plataforma de almacenamiento en la nube privada e independiente.

## 🔒 Buenas Prácticas de Seguridad y GitOps

* **Manejo de Secretos**: Las credenciales sensibles y variables del sistema están abstraídas mediante variables de entorno (`.env`).
* **Seguridad en Git**: Sanitización de datos mediante `.gitignore` para prevenir la fuga de credenciales en repositorios públicos.

## 🚀 Despliegue Local

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/Enzoskr/Infraestructure-homelab.git](https://github.com/Enzoskr/Infraestructure-homelab.git)
   cd Infraestructure-homelab
