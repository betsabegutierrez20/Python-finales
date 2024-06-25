# Hoy vamos a hacer actividad en Python en un día como programadores:

 1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window
2. Creamos una carpeta o directorio:
 
PASO para crear un nuevo entono virtual:

```sh
mkdir python-final
```
3. Entramos en ella:
```sh
cd python-final
```
4. Iniciamos el repositorio:
```sh
git init
```
5. Creamos un archivo:
```sh
touch finales.py
```
6. Abrimos VSC:
```sh
code .
```
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
```sh
python -V
python3 -V
```
8. Creamos el entorno virtual en Python:
```sh
python3 -m venv venv #Creamos el entorno virtual
```
9. Activamos el entorno virtual:
```sh
source venv/bin/activate #Activamos el entorno virtual en Linux
venv/scripts/activate #En windows
```
10. Hacemos actualización del pip de Python
```sh
python3 -m pip install --upgrade pip #Actualizamos el pip
```

11. Investigar ¿Qué es el pip y porque lo actualizamos?
12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.
13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.


 ## RESPUESTAS 11: ¿Qué es el pip y porque lo actualizamos?
Pip es el administrador de paquetes para Python. Su nombre viene de "Pip Installs Packages". Se utiliza para instalar, actualizar y administrar paquetes de software escritos en Python. Con pip, los desarrolladores pueden acceder a una amplia variedad de bibliotecas y frameworks que facilitan el desarrollo de aplicaciones en Python.

### ¿Por qué actualizamos pip?
Actualizar pip es importante por varias razones:

1. **Seguridad**: Las versiones más recientes de pip a menudo incluyen correcciones de seguridad que protegen contra vulnerabilidades descubiertas en versiones anteriores.

2. **Nuevas funcionalidades**: Las actualizaciones de pip pueden incluir nuevas características y mejoras que facilitan su uso y aumentan su funcionalidad.

3. **Compatibilidad**: Las nuevas versiones de pip aseguran una mejor compatibilidad con las versiones más recientes de Python y otros paquetes.

4. **Corrección de errores**: Las actualizaciones de pip solucionan errores y problemas que se han identificado en versiones anteriores, mejorando la estabilidad y el rendimiento.

### ¿Cómo actualizar pip?
Para actualizar pip, puedes usar el siguiente comando en la línea de comandos:

```bash
pip install --upgrade pip
```

