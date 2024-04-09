# Repositorio del Equipo #9

¡Bienvenidos al repositorio del Equipo #9! Aquí encontrarás nuestras soluciones y trabajos colaborativos.

## Integrantes del Equipo
- Acierno Hernández, Deco
- Laines Nabte, Jaime Sebastián
- Montero Salazar, Luis Ángel

## Instalación de iRacket y Jupyter

### Paso 1: Instalar iRacket
Para instalar iRacket, sigue los siguientes pasos:

1. Descarga iRacket desde [la página oficial](https://racket-lang.org/download/).
2. Sigue las instrucciones de instalación específicas para tu sistema operativo.

### Paso 2: Instalar Jupyter
Para instalar Jupyter, puedes usar pip (Python Package Installer). Asegúrate de tener Python instalado en tu sistema. Luego ejecuta el siguiente comando en tu terminal:

```bash
pip install jupyter
```

### Paso 3: Configurar Jupyter con el Kernel de iRacket

Después de instalar Jupyter, necesitas configurarlo para usar el Kernel de iRacket. Sigue estos pasos:

1. Abre una terminal y ejecuta el siguiente comando para instalar el Kernel de iRacket:

```bash
raco pkg install --auto iracket
```

2. Una vez instalado, ejecuta el siguiente comando para registrar el Kernel de iRacket con Jupyter:

```bash
jupyter-kernelspec install $RACKET_HOME/share/pkgs/iracket/iracket/kernel
```

## Ejecución de los Problemas

Cada problema se ejecuta de la siguiente manera:

1. Abre Jupyter Notebook en tu terminal con el comando jupyter notebook.
2. Navega hasta el archivo del problema que deseas ejecutar.
3. Abre el archivo y ejecuta las celdas de código según sea necesario.

¡Listo! Ahora estás listo para trabajar con iRacket y Jupyter en nuestro repositorio. 
