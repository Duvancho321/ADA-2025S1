# 🌍 ADA-2025S1: Análisis de Datos Ambientales  

Este repositorio contiene los **códigos y datos** utilizados en la materia **Análisis de Datos Ambientales** de la Universidad Nacional de Colombia, Sede Medellín, correspondientes al semestre **2025-S1**.  

Los códigos aquí desarrollados fueron preparados por **Duvan Nieves** en el marco de su trabajo como **monitor de la materia**, bajo la orientación del profesor **Carlos David Hoyos Ortiz**.  

---

## 📚 Sobre la materia  
La asignatura busca fortalecer las habilidades de análisis, procesamiento y visualización de datos ambientales, integrando diferentes fuentes de información climática y meteorológica.  

En este repositorio encontrarás:  
- 📂 **Scripts en Python** para el procesamiento de datos.  
- 📂 **Datos de entrada** en formato **NetCDF** y **Zarr** necesarios para ejecutar los códigos.  
- 📂 **Ejemplos de análisis** con datasets de **CHELSA** y **ERA5**.  

---

## 👨‍🏫 Docente responsable  
**Carlos David Hoyos Ortiz**  
- 🌐 Página de Cursos: [carlosdhoyos.github.io](https://carlosdhoyos.github.io/)  
- 💻 GitHub: [@carlosdhoyos](https://github.com/carlosdhoyos)  

---

## 👨‍💻 Autor de los códigos  
**Duvan Nieves**  
- 💻 GitHub: [@Duvancho321](https://github.com/Duvancho321)  

---

## ⚙️ Requerimientos  
Para instalar las dependencias necesarias, utiliza el archivo `requirements.txt`:  

```bash
pip install -r requirements.txt
```

### Dependencias principales:
- `xarray` - Para manejo de datos multidimensionales
- `pandas` - Análisis de datos  
- `numpy` - Operaciones numéricas
- `matplotlib` - Visualización básica
- `cartopy` - Mapas y proyecciones cartográficas
- `netcdf4` - Lectura de archivos NetCDF
- `zarr` - Manejo de arrays comprimidos

---

## 🚀 Uso

### Clonación del repositorio
Clona este repositorio y navega hasta la carpeta:

```bash
git clone https://github.com/Duvancho321/ADA-2025S1.git
cd ADA-2025S1
```

### Ejecución de scripts
Ejecuta los scripts en Python asegurándote de tener instaladas las dependencias y de ubicar correctamente los archivos de datos que acompañan el repositorio.

**⚠️ Importante**: Antes de ejecutar cualquier script, asegúrate de descargar y ubicar correctamente los archivos de datos en las carpetas correspondientes.

---

## 📊 Fuentes de datos

Este repositorio utiliza datasets de acceso abierto ampliamente reconocidos en climatología:

### 🌍 ERA5 – Reanálysis (ECMWF)
- Proporciona variables climáticas y meteorológicas globales con alta resolución espacial y temporal.
- **Fuente oficial**: [Copernicus Climate Data Store ↗](https://cds.climate.copernicus.eu/)
- **Referencia**: Hersbach, H., et al. (2020). *The ERA5 global reanalysis*. Quarterly Journal of the Royal Meteorological Society, 146(730), 1999-2049.

### 🌲 CHELSA – Climatologies at High Resolution for the Earth's Land Surface Areas
- Datos climáticos a escala de 30 arc-seconds (~1 km) para estudios ecológicos y ambientales.
- **Fuente oficial**: [CHELSA Climate Data ↗](https://chelsa-climate.org/)
- **Referencia**: Karger, D. N., et al. (2017). *Climatologies at high resolution for the earth's land surface areas*. Scientific Data, 4, 170122.

---

## 📝 Nota

Este repositorio es de carácter **académico y abierto**, con fines de aprendizaje y práctica.

- Los códigos fueron desarrollados como parte del trabajo de monitoría de la materia **Análisis de Datos Ambientales (2025-S1)**.
- Los datos pertenecen a **CHELSA** y **ERA5**, quienes deben ser citados y reconocidos en cualquier trabajo o publicación derivada.

---

## 📖 Cómo citar este repositorio

Si utilizas este material en un trabajo académico, puedes citarlo de la siguiente manera:

### BibTeX
```bibtex
@misc{ADA-2025S1,
    author = {Duvan Nieves and Carlos David Hoyos Ortiz},
    title = {ADA-2025S1: Análisis de Datos Ambientales},
    year = {2025},
    institution = {Universidad Nacional de Colombia, Sede Medellín},
    url = {https://github.com/Duvancho321/ADA-2025S1}
}
```

### Markdown
```markdown
Nieves, D., & Hoyos Ortiz, C. D. (2025). *ADA-2025S1: Análisis de Datos Ambientales*. Universidad Nacional de Colombia, Sede Medellín. https://github.com/Duvancho321/ADA-2025S1
```

---

## 🎯 Estructura del repositorio

```
ADA-2025S1/
├── data/                    # Datos de entrada (NetCDF, Zarr)            
├── Notebooks/               # Jupyter notebooks
├── requirements.txt         # Dependencias
└── README.md                # Este archivo
```

---