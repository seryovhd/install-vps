# Instalador VPS para Chasap

Este script permite realizar la instalación automática del entorno necesario para ejecutar Chasap en un servidor VPS.

## Requisitos previos

Antes de proceder con la instalación, asegúrate de tener acceso a un servidor VPS con **Linux** (Ubuntu 24.10 x64 Recomendado).

## Instrucciones de instalación

1. **Clona el repositorio en tu servidor VPS:**

    ```bash
    git clone https://github.com/MinoruMX/install-vps setup
    ```

2. **Asigna permisos para ejecutar el script:**

    ```bash
    sudo chmod -R 777 setup
    ```

3. **Accede al directorio del script:**

    ```bash
    cd setup
    ```

4. **Ejecuta el script de instalación primaria:**

    ```bash
    sudo ./setup
    ```

**O EN UNA SOLA LINEA TODO**

    git clone https://github.com/MinoruMX/install-vps setup && sudo chmod -R 777 setup && cd setup && sudo ./setup

Este script se encargará de instalar y configurar los componentes necesarios para que puedas usar Chasap en tu VPS.


## Notas adicionales

- Es recomendable realizar la instalación en un servidor limpio, sin configuraciones previas que puedan interferir con el proceso.
- Si encuentras algún error o problema, por favor abre un **issue** en el repositorio para que podamos ayudarte a solucionarlo.
