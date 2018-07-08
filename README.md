# CellCouter

CellCounter es un software desarrollado para contar unidades formadoras de colonias (UFC) obtenidas de análisis de viabilidad de las células sometidas a diferentes tratamientos.

## Obtener el software

Para obtener el software e iniciar su instalación basta con clonar el repositorio de github que lo contiene.

Ejecutar el siguiente comando:
```bash
git clone https://github.com/vmercau/cellcounter.git
```

### Prerequisitos

Para instalar CellCounter se debe asegurar contar con una instalación de python 2.7 y las bibliotecas:
* OpenCV 3.4.1.15
* Argparse 1.4.0
* Imutils 0.4.6
* Numpy 1.14.5



Para realizar la instalación en un entorno Linux, ejecutar el siguiente comando en una terminal:
```bash
pip2 install numpy opencv argparse imutils
```

### Instalación

Al tratarse de un programa enteramente desarrollado en python, al tener todos los archivos del repositorio y las bibliotecas necesarias, el programa ya se encuentra en condiciones de ser ejecutado.

## Ejecución del programa

La ejecución de CellCounter consta de ejecutar el siguiente comando en la terminal, en la carpeta contenedora del programa:

```bash
python2 contador_colonias.py -i <imagen de entrada> -o <imagen de salida>
```
Por ejemplo:

Tomando como referencia la imagen *in.jpeg* 
![alt text](https://raw.githubusercontent.com/vmercau/cellcounter/master/in.jpeg)

ejecutar el siguiente comando:

```bash
python2 contador_colonias.py -i in.jpeg -o out.jpg
```
**NOTA: Puede notar que el archivo *in.jpeg* ya viene incluido en el repositorio**


Se obtendra como resultado:

```bash
54 colonies
159 loops
```

Y se generará la imagen *out.jpg* en la cual se podrán observar las colonias que pudieron ser contadas marcadas con un círculo verde.
![alt text](https://raw.githubusercontent.com/vmercau/cellcounter/master/out.jpg)
## Autora

* **Mariana Vanesa Mercau** - *Trabajo inicial y evolución del proyecto*

## Licencia

Este proyeccto esta licenciado bajo la Licencia MIT - vea el [LICENSE.md](LICENSE.md) para mas detalles
