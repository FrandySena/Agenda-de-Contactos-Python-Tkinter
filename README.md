# Agenda de Contactos - Python y Tkinter

Este proyecto consiste en una aplicacion de escritorio desarrollada en Python utilizando la libreria grafica Tkinter. Permite gestionar una lista de contactos de manera local con una interfaz intuitiva y funcional.

## Caracteristicas

- Gestion de contactos: Permite agregar, editar, eliminar y visualizar informacion detallada de cada persona.
- Campos de datos: Almacena nombre, apellido, correo electronico, telefono y direccion.
- Sistema de busqueda: Incluye una funcion de filtrado para localizar contactos especificos por nombre.
- Interfaz grafica: Diseñada con una estructura de contenedores (frames) para separar el area de entrada de datos, los controles y la visualizacion.
- Navegacion: Cuenta con una lista desplegable asistida por una barra de desplazamiento (Scrollbar) para facilitar el manejo de multiples registros.

## Tecnologias Utilizadas

- Lenguaje: Python 3
- Libreria de Interfaz: Tkinter (Libreria estandar de Python).

## Estructura del Repositorio

- main.py: Codigo fuente de la aplicacion.
- Gestor_Agenda.exe: Archivo ejecutable para sistemas operativos Windows.
- README.md: Documentacion del proyecto.

## Instalacion y Ejecucion

### Opcion 1: Ejecucion mediante el codigo fuente
Para ejecutar la aplicacion desde el archivo .py, es necesario tener instalado Python en su sistema.
1. Clonar o descargar el repositorio.
2. Abrir una terminal en la carpeta del proyecto.
3. Ejecutar el comando: python main.py

### Opcion 2: Uso del archivo ejecutable
Este proyecto incluye una version compilada para facilitar su uso en entornos donde no se disponga de Python instalado.
1. Dirigirse a la seccion de Releases o descargar directamente el archivo .exe desde la carpeta raiz.
2. Ejecutar Gestor_Agenda.exe.

> [!NOTE]: Al ser un software de desarrollador independiente, es posible que Windows muestre una advertencia de seguridad (SmartScreen). En tal caso, debe seleccionar "Mas informacion" y luego "Ejecutar de todas formas".

## Notas Adicionales
Esta version de la agenda utiliza un diccionario en memoria para el almacenamiento de los datos. Esto significa que la informacion se mantiene disponible mientras la aplicacion este en ejecucion, pero no persiste una vez que se cierra el programa.

**Autor:** Frandy Sena Taveras
