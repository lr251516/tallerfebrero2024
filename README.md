# Tarea Obligatoria: Automatización con Ansible 🛠

## Descripción 📝
¡Bienvenido al repositorio del TallerFebrero2024 sobre Automatización con Ansible! Este proyecto es resultado del esfuerzo conjunto de Lucas Rodriguez y Santiago Lazaneo, realizado como parte del trabajo obligatorio para el taller de servidores Linux.

En este proyecto, exploraremos cómo Ansible puede simplificar y agilizar la administración de servidores y la configuración de infraestructuras. Nuestro objetivo es automatizar diversas tareas relacionadas con la configuración y administración de servidores, incluyendo la actualización de software, la instalación de paquetes, la configuración de servicios y más.

## Estructura del Repositorio 📁
El repositorio está organizado de la siguiente manera:

- *playbooks*: Contiene los playbooks de Ansible utilizados para realizar diferentes tareas de automatización.
- *roles*: Incluye los roles de Ansible, cada uno diseñado para realizar una tarea específica de manera modular y reutilizable. Cada rol puede tener las siguientes subcarpetas:
  - *handlers*: Handlers utilizados en el rol.
  - *tasks*: Tareas principales realizadas por el rol.
  - *vars*: Variables utilizadas en el rol.
  - *templates*: Plantillas utilizadas en el rol.
- *inventories*: Aquí se encuentran los archivos de inventario de Ansible, que especifican los servidores sobre los cuales se ejecutarán las tareas de automatización.

## Tareas Automatizadas 🤖
Algunas de las tareas que hemos automatizado en este proyecto incluyen:

1. *Actualización de Servidores*: Utilizando Ansible para aplicar actualizaciones de software de manera coordinada y segura en todos los servidores.
2. *Instalación de OpenJDK y Tomcat 8*: En uno de los servidores, se instalará OpenJDK y Tomcat 8, junto con una aplicación de muestra.
3. *Configuración de Proxy Reverso*: En el otro servidor, se configurará un proxy reverso con Apache para acceder a la aplicación Java alojada en el servidor configurado en el punto anterior.

## Cómo Usar Este Repositorio 🚀
Para utilizar este repositorio y comenzar con la automatización de tareas:

1. Clona este repositorio en tu máquina local.
2. Asegúrate de tener Ansible instalado. Si no lo tienes, sigue las instrucciones de instalación en la documentación oficial de Ansible.
3. Explora los diferentes playbooks y roles disponibles en el repositorio.
4. Configura tus inventarios y variables según sea necesario para adaptar las tareas de automatización a tu entorno.
5. Ejecuta los playbooks de Ansible según tus requisitos específicos.

## Créditos 💻
Este trabajo fue realizado por Lucas Rodriguez y Santiago Lazaneo.
