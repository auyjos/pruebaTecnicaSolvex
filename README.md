
# Ejercicios de Data Engineering y Web Scraping

Este repositorio agrupa cuatro ejercicios prácticos en Python, Pandas, PySpark y Web Scraping:

1. **Ejercicio 1: Manipulación de datos con Pandas y COVID-19**  
   - Descarga los datos públicos de COVID-19 de la Universidad Johns Hopkins.  
   - Carga CSV/JSON en un `pandas.DataFrame`.  
   - Calcula el promedio de casos confirmados diarios en un país.  
   - Encuentra los 10 países con mayor tasa de mortalidad (muertes/casos) hasta la fecha (limitado a 2023).

2. **Ejercicio 2: Procesamiento de datos con PySpark y vuelos 2015**  
   - Usa el dataset de Kaggle (`flights.csv`) en lugar de la descarga directa de BTS, ya que los datos de Kaggle vienen preprocesados y limpios.  
   - Carga en un `Spark DataFrame` con `pyspark==4.0.0.dev1`.  
   - Calcula el retraso promedio de llegada (`ARRIVAL_DELAY`) para un aeropuerto específico.  
   - Obtén las 10 rutas (origen→destino) con más vuelos.

3. **Ejercicio 3: Integración de Pandas y Spark con películas y críticas**  
   - Construye un `pandas.DataFrame` de películas y un `Spark DataFrame` de críticas.  
   - Agrupa y calcula la puntuación media por película en Spark.  
   - Convierte a Pandas y combina ambos para mostrar Título, Año y PuntuaciónMedia.

4. **Ejercicio 4: Web Scraping con Requests y BeautifulSoup**  
   - Script en Python que obtiene el precio actual de Bitcoin desde CoinMarketCap.  
   - Incluye manejo de `User-Agent`, selección del elemento HTML (`data-test="text-cdp-price-display"`) y manejo de errores.

---

## Requisitos y Configuración

1. **Crear y activar un entorno virtual**

   ### Linux / macOS (bash)
   ```bash
   # Crear el virtualenv
   python -m venv venv

   # Activar
   source venv/bin/activate

   # Instalar dependencias
   pip install -r requirements.txt
````

### Windows (PowerShell)

```powershell
# Crear el virtualenv
python -m venv venv

# Activar
.\venv\Scripts\Activate.ps1

# Instalar dependencias
pip install -r requirements.txt
```

### Windows (CMD)

```cmd
REM Crear el virtualenv
python -m venv venv

REM Activar
venv\Scripts\activate.bat

REM Instalar dependencias
pip install -r requirements.txt
```

