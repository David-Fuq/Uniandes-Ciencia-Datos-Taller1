# Taller 1 - Ciencia de Datos (MAIA-4101)

## Intergrantes del Equipo
- David Fuquen - 202021113
- Santiago Martinez - 202112020

## Conclusiones (insights)

Todos los insights, conclusiones y resultados, así como las estrategias recomendadas a la cadena hotelera, pueden ser encontrados en informe ejecutivo `Taller_1_Ciencia_Datos.pdf`. En este se sintetiza el trabajo realizado. 

## Instrucciones de ejecución 

### Requisitos previos
- Python 3.8 o superior
- pip (gestor de paquetes de Python)
- Jupyter Notebook o JupyterLab

### Pasos para ejecutar el proyecto

1. **Clonar el repositorio** (si aún no lo has hecho):
   ```bash
   git clone https://github.com/David-Fuq/Uniandes-Ciencia-Datos-Taller1.git
   cd Uniandes-Ciencia-Datos-Taller1
   ```

2. **Instalar las dependencias**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Verificar que los datos estén en su lugar**:
   - Asegúrate de que el archivo `hotel_bookings_modified.csv` esté en la carpeta `data/`
   - Asegúrate de que el archivo `Hotel Bookings Demand Data Dictionary.xlsx` esté en la carpeta `data/`

4. **Ejecutar el análisis**:
   ```bash
   jupyter notebook EDA.ipynb
   ```
   O alternativamente:
   ```bash
   jupyter lab EDA.ipynb
   ```

5. **Ejecutar las celdas**:
   - Ejecuta todas las celdas en orden secuencial usando "Run All" o ejecutándolas una por una
   - El notebook está dividido en secciones claras: preparación, entendimiento, limpieza y análisis estratégico

### Estructura de ejecución del notebook

- **Sección 0**: Preparación inicial e importación de librerías
- **Sección 1**: Entendimiento y exploración de los datos
- **Sección 2**: Preparación y limpieza de los datos
- **Sección 3**: Análisis estratégico completo (4 fases)

## Dependencias

### Librerías principales

- **pandas >= 1.5.0**: Manipulación y análisis de datos estructurados
- **numpy >= 1.21.0**: Operaciones numéricas y arrays multidimensionales
- **matplotlib >= 3.5.0**: Visualización básica de datos y gráficos
- **seaborn >= 0.11.0**: Visualización estadística avanzada
- **scikit-learn >= 1.1.0**: Machine learning (clustering, PCA, escalado)
- **scipy >= 1.9.0**: Análisis estadístico y funciones científicas
- **openpyxl >= 3.0.0**: Lectura de archivos Excel (.xlsx)

### Librerías de desarrollo (opcionales)
- **jupyter >= 1.0.0**: Entorno de notebooks interactivos
- **ipykernel >= 6.0.0**: Kernel de Python para Jupyter

### Instalación de dependencias

#### Opción 1: Usando requirements.txt (recomendado)
```bash
pip install -r requirements.txt
```

#### Opción 2: Instalación manual
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy openpyxl jupyter ipykernel
```

#### Opción 3: Usando conda
```bash
conda install pandas numpy matplotlib seaborn scikit-learn scipy openpyxl jupyter ipykernel
```

### Notas adicionales
- Se recomienda usar un entorno virtual para evitar conflictos de dependencias
- El módulo `warnings` es parte de la librería estándar de Python (no requiere instalación)
- Las versiones especificadas son mínimas; versiones más recientes también son compatibles
