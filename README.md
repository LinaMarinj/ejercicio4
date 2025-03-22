<h1 align="left">Ejercicio 4</h1>

###

<p align="left">Nombres cortos 💻</p>

###

<p align="left">Este proyecto consta de una aplicación sencilla en la que podrás ingresar los nombres y notas de 3 estudiantes, almacenándolos en un archivo de Excel. Se recopilan los datos de los estudiantes y se guardan en un diccionario. Posteriormente, se crea un archivo Excel y se filtran los nombres que tienen cuatro letras o menos, los cuales se escriben en la hoja de cálculo. Finalmente, el archivo Excel se guarda bajo el nombre 'ejercicio4.xlsx', facilitando el manejo de datos y la creación de reportes en formato Excel</p>

###

<h2 align="left">instrucciones de instalación</h2>

###

<p align="left"></p>

###

Sigue estos pasos para clonar el repositorio, configurar el entorno virtual, instalar las dependencias y ejecutar la aplicación.

1. Clonar el repositorio - Abre la terminal y ejecuta:
``` bash
https://github.com/LinaMarinj/ejercicio4.git
```

2. Acceder a la carpeta del proyecto - Navega al directorio clonado:
``` bash
cd nombre-de-la-carpeta
```


3. Abrir el proyecto en Visual Studio Code - Inicia VS Code desde la terminal:
``` bash
code .
```
También puedes abrir Visual Studio Code manualmente y seleccionar la carpeta del proyecto desde "Archivo" > "Abrir carpeta".


4. Abrir una nueva terminal en Visual Studio Code:


  - En Windows, presiona Ctrl + ñ.
  - O, desde el menú superior, haz clic en los tres puntos ... y selecciona New Terminal.


5. Seleccionar el perfil de terminal recomendado:

   En la terminal, haz clic en la flecha hacia abajo llamada Launch Profile y elige Command Prompt (CMD).

6. Configurar un entorno virtual - Ejecuta el siguiente comando:
``` bash
   python -m venv .venv
```

7. Activar el entorno virtual:
``` bash
   -Windows:
    .venv\Scripts\activate

  -Linux/macOS:
   source .venv/bin/activate
```


8. Instalar las dependencias del proyecto ejecutando:

``` bash
   pip install -r requirements.txt
```
   
Nota: No cierres la terminal mientras se instalan las dependencias, ya que interrumpirás el proceso.

9. Ejecutar la aplicación:
``` bash
    python main.py
```


<h3 align="left">Uso del programa</h3>

###

<p align="left"></p>

###

<p align="left">✔️ Ingreso de Datos: Al ejecutar el programa, se te pedirá ingresar el nombre y la nota de 3 estudiantes. <br><br>✔️ Filtrado de Nombres: Después de ingresar los datos, el programa filtrará automáticamente los nombres de los estudiantes que tengan cuatro letras o menos.<br><br>✔️ Creación del Archivo Excel: El programa creará un archivo Excel nuevo con una hoja de cálculo en la que se escribirán los nombres filtrados.<br><br>✔️ Guardado del Archivo: Finalmente, el archivo se guardará con el nombre "ejercicio4.xlsx", listo para ser revisado con cualquier programa que soporte archivos Excel.</p>

###
