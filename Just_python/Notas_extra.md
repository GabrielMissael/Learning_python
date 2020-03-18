# Linea de comandos, notebooks, github, ....
=========================================================================

1. **.py** son archivos de python
2. **.ipynb** son notebooks

### Notas: Linea de comandos.

Para la terminal de **Windows**:
1. **cd** te da el path del directorio actual (current directory)
    1. **cd "directorio"** para cambiar directorio
    2. **cd ..** para regresar al directorio anterior
2. **dir** muestra el contenido del directorio
3. **clear** limpia la terminal
4. **python "nombre".py** para ejecutar programa

### Notas: Crear repositorio git.

Para crear un nuevo repositorio y asociarlo a uno en github:
1. **git init**
2. **git add .** agregar todos los archivos (por eso el punto), aunque puedes no agregarlos todos
3. **git commit -m "descripción"** se breve en la descripción de cada commit, y has uno para cada conjunto de cambios
4. **git remote add origin git@github.com:username/new_repo** Link al repo en github
5. **git push -u origin master** sube los archivos existentes en el repo local

Para actualizar:
1. **git pull** descarga los archivos en github que no estén en el repo local

### Jupyter notebook shortchuts.
Algunos shortcuts para ser mas cool y hacerse notar. Generales:

1. **Shift+Enter** corre la celda actual y va a la celda de abajo
2. **Ctrl+Enter** corre la celdas seleccionadas
3. **Ctrl+s** guarda y crea checkpoint
4. **Alt+enter** corre la actual, inserta una debajo

Modo edición:
1. **enter** entra en modo edición
2. **Ctrl+]** comenta lineas seleccionadas

Modo comandos:
1. **Esc** entra al modo de comandos
2. **F** encuentra y reemplaza
3. **H** muestra todos los shortcuts
4. **Y** cambia celda a codigo
5. **M** cambia celda a markdown
6. **Shif+(up or down)** selecciona celdas
7. **A** inserta celda arriba
8. **B** inserta celdad abajo
9. **X** corta celdas seleccionadas
10. **C** copia celdas seleccionadas
11. **D+D** borra celda seleccionada
12. **Z** desborra las celdas xD

### Markdown

Cosas y estilos que no usé aqui pero que podria utilizar de Markdown:
1. Para lista de elementos "-", "*" o "+" sin numerar y "1." para numerados
2. Encierra en * para *cursiva* y en ** para **negrita**
3. Para citas ">".
> "Que onda que pex" - Missael Barco
4. Para bloques de codigo encierra en "~" y para menos de un renglon en comillas sencillas `Asi se veria` la linea y el parrafo:
~~~ 
print("Las poderosisimas aguilas del america")
~~~
5. Para un [enlace](http://www.google.com): `[enlace en línea](http://www.google.com)`
6. Para agregar imagenes `![Texto alternativo](/ruta/a/la/imagen.jpg)`:
![Puppies](https://i.ytimg.com/vi/mRf3-JkwqfU/hqdefault.jpg)