# Proyecto 2: PageRank en la Red de Control de Tráfico Aéreo (FAA)

Este repositorio contiene la implementación y el informe del **Proyecto 2** para el curso **IMT2230 - Álgebra lineal avanzada y modelamiento**. El objetivo principal es analizar la relevancia estructural de los aeropuertos en la red de control de tráfico aéreo de Estados Unidos (**maayan-faa**) utilizando el algoritmo de **PageRank**.

## Contenido del Repositorio

- **`Proyecto_2-2.ipynb`**: Notebook de Jupyter con todo el desarrollo matemático, códigos de iteración de potencias, visualizaciones de redes y el análisis e interpretación de resultados.
- **`download_data.py`**: Script en Python para descargar y preprocesar automáticamente el conjunto de datos de la red de tráfico aéreo.
- **`out.maayan-faa`**: Archivo de datos de la red (generado tras ejecutar el script de descarga o descargado manualmente).
- **`requirements.txt`**: Archivo con la lista de dependencias y librerías de Python requeridas para ejecutar el notebook.

## Fuente de Datos

La red utilizada es **maayan-faa** (Air traffic control), que consta de 1226 nodos (aeropuertos o centros de servicio de la FAA) y 2615 aristas dirigidas (rutas sugeridas). 
- Sitio oficial de la red en KONECT: [http://konect.cc/networks/maayan-faa/](http://konect.cc/networks/maayan-faa/)

## Requisitos de Ejecución y Reproducibilidad

Siga los siguientes pasos para clonar el repositorio, instalar las dependencias y ejecutar el análisis en su máquina local:

### 1. Clonar el repositorio
```bash
git clone https://github.com/<usuario>/IMT2230-PROYECTO-2.git
cd IMT2230-PROYECTO-2
```

### 2. Instalar dependencias
Se recomienda utilizar un entorno virtual de Python. Puede instalar todas las dependencias necesarias mediante `pip`:
```bash
pip install -r requirements.txt
```
Las dependencias requeridas incluyen:
- `numpy`
- `scipy`
- `networkx`
- `pandas`
- `matplotlib`
- `seaborn`

### 3. Descargar y preprocesar los datos
Ejecute el script `download_data.py` para obtener el archivo de red `out.maayan-faa` preprocesado y listo en el directorio raíz:
```bash
python download_data.py
```

### 4. Ejecutar el Notebook
Inicie Jupyter Notebook o JupyterLab y abra `Proyecto_2-2.ipynb` para reproducir todos los cálculos y gráficos del informe:
```bash
jupyter notebook Proyecto_2-2.ipynb
```
o ejecútelo celda por celda en su editor favorito (VS Code, Jupyter, etc.).