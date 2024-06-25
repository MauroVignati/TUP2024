# Python-final
## Hoy vamos a hacer actividad en Python en un día como programadores:

> 1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

> 2. Creamos una carpeta o directorio: 
```sh
mkdir python-final
```
> 3. Entramos en ella: 
```sh

cd python-final
```
> 4. Iniciamos el repositorio:
```sh

git init
```
> 5. Creamos un archivo:
```sh

touch finales.py
```
> 6. Abrimos VSC:
```sh

code .
```
> 7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
```sh

python -V

python3 -V
```
> 8. Creamos el entorno virtual en Python:
```sh

python3 -m venv venv #Creamos el entorno virtual
```
> 9. Activamos el entorno virtual:
```sh

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows
```
> 10. Hacemos actualización del pip de Python
```sh

python3 -m pip install --upgrade pip #Actualizamos el pip
```
> 11. Investigar ¿Qué es el pip y porque lo actualizamos?

Pip es el gestor de paquetes oficial de Python. Permite instalar, actualizar y desinstalar paquetes y sus dependencias desde el Índice de Paquetes de Python (PyPI) y otros índices. Estos paquetes pueden incluir bibliotecas, herramientas y marcos que extienden la funcionalidad de Python y facilitan el desarrollo de software.

### Lo actualizamos por:</sub>

<sub>1. Seguridad: Las versiones más recientes de pip pueden incluir parches de seguridad que corrigen vulnerabilidades detectadas en versiones anteriores.</sub>

<sub>2. Compatibilidad: Nuevas versiones de pip pueden proporcionar compatibilidad con nuevas versiones de Python y sus entornos de desarrollo. Esto es crucial a medida que Python evoluciona.</sub>

<sub>3. Nuevas Funcionalidades: Actualizaciones de pip pueden incluir nuevas funcionalidades y mejoras que facilitan la gestión de paquetes, tales como mejor manejo de dependencias, mejoras en la velocidad de instalación y nuevas opciones de configuración</sub>
   
<sub>4. Corrección de Errores: Las actualizaciones a menudo incluyen correcciones de errores que mejoran la estabilidad y el rendimiento de pip.</sub>

<sub>5. Deprecación de Características: Mantener pip actualizado asegura que se eviten posibles problemas derivados del uso de características o comandos que han sido deprecados en versiones más antiguas.</sub>


> 12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.
