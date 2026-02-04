<h1 align="left"> Telecom X: Análisis de deserción de clientes </h1>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Numpy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

<h2>📖 Introducción</h2>

<p>La compañía Telecom X ha recopilado información de sus clientes la cual se usará para conocer cual es la deserción de sus clientes y en base a que ocurre para así poder implementar las medidas necesarias para evitar la deserción.</p>

<h2>🎯 Objetivo</h2>

<p>En el análisis vamos a revisar la información sobre nuestros clientes para:
 
1.- Entender cual es la cantidad de clientes que desertan

2.- El motivo de la deserción

3.- Las características con las que cuentan los clientes que desertan

4.- Crear estrategias para disminuir la deserción
</p>

<h2>📊 Puntos clave</h2>

<p>Los principales hallazgos son:

- La tasa de deserción es del **26.6%**, la cual es una cifra muy alta.
- El periodo más crítico se encuentra en los primero 6 meses de servicio, con mayor deserción despues del primer mes.
- Los clientes con menos vínculos familiares mostraron mayor deserción.
- Los clientes con internet de fibra óptica sin protección de dispositivo ni soporte técnico mostraron mayor deserción.
- Los clientes con contrato mensual mostraron mayor deserción.</p>

<h2>📁 Estructura</h2>

```
challenge-telecom-x/
│
├── TelecomX_LATAM.ipynb       # Notebook principal con el análisis completo
├── data/
│   └── TelecomX_Data.json     # Dataset original (7,267 registros → 7,032 después de ETL)
└── README.md                  # Documentación del proyecto
```

- **TelecomX_LATAM.ipynb**: Contiene todo el análisis exploratorio, desde la carga de datos hasta las conclusiones finales
- **data/**: Carpeta con el dataset original en formato JSON (7,267 registros antes de ETL, 7,032 registros limpios)

<h2>📊 Ejemplos de gráficos del proyecto</h2>

### 1. Distribución de Deserción
![Churn Distribution](https://github.com/MaferVelde/Telecom-X/blob/main/Graficos/desercion.png)
*Tasa general de deserción: 26.6% de los clientes abandonan el servicio*

### 2. Antigüedad de los clientes
![Tenure Analysis](https://github.com/MaferVelde/Telecom-X/blob/main/Graficos/antig%C3%BCedad.png)
*Muestra de la antigüedad de todos los clientes, con picos en los primeros meses y en los 70 meses*

### 3. Análisis de Antigüedad vs Deserción
![Tenure Analysis](https://github.com/MaferVelde/Telecom-X/blob/main/Graficos/desercion%20antig%C3%BCedad.png)
*El 53% de la deserción ocurre en los primeros 6 meses de servicio*

### 4. Análisis de tipo de contrato y deserción
![Contract Type](https://github.com/MaferVelde/Telecom-X/blob/main/Graficos/contrato.png)
*Muestra la relación entre la deserción y el tipo de contrato del cliente*

<h2>🚀 Ejecución del proyecto</h2>

### 📍 Google Colab 

1. Haz clic en el siguiente enlace:  
   🔗 [📊 Abrir Notebook en Google Colab](https://colab.research.google.com/github/MaferVelde/Telecom-X/blob/main/Telecom_X.ipynb)

2. El notebook se abrirá directamente en tu navegador

3. En el lado superior derecho hacer click en **"Conectar"**

4. Haz clic en **"Ejecutar todo"** en el menú `Runtime > Run all`

5. Todos los gráficos y análisis se generarán automáticamente

**Ventajas:**
- ✅ No necesitas instalar nada en tu computadora
- ✅ Funciona desde cualquier dispositivo con navegador
- ✅ Incluye GPU gratuita si necesitas procesamiento adicional

<h2>🚀 Tecnología utilizada</h2>

- 🐍 **Python 3.8+** – Lenguaje principal de análisis
- 📊 **Pandas** – Manipulación y análisis de datos estructurados
- 📈 **Matplotlib / Seaborn** – Visualización de datos y gráficos estadísticos
- 🔢 **NumPy** – Operaciones numéricas y estadísticas
- ☁️ **Google Colab** – Ejecución en la nube sin instalación local
- 🌐 **Git / GitHub** – Control de versiones y colaboración

<h2>💡 Recomendaciones</h2>

De acuerdo a nuestro análisis se recomienda:

1. Hacer un seguimiento de los nuevos clientes, sobre todo en los primeros 6 meses de servicio.
2. Ofrecer incentivos para que los clientes realicen el cambio de contrato mensual a contrato por mayor tiempo.
3. Ofrecer a nuestros clientes con mayor enfasis el servicio de protección de dispositivo y de soporte técnico para así mejorar su experiencia y darles un servicio más completo, sobre todo a los clientes con internet de fibra óptica, ya que son los que muestran mayor propención a desertar.
4. Promociones como descuento a clientes que migren de contratos mensual a anual, de iguál manera para los clientes que realizan pagos con cheques para que cambien su metodo de pago a algún pago automático.
5. Realizar encuestas de satisfacción para recibir sugerencias para mejorar el servicio. 

<h2>📜 Licencia</h2>

Este proyecto se comparte bajo la licencia **MIT**.  
Puedes usarlo, modificarlo y distribuirlo libremente citando la fuente.

```
MIT License

Copyright (c) 2026 Maria Fernanda Velderrain Parra

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

<h2>✨ Autor</h2>

Maria Fernanda Velderrain Parra

Data Analyst Junior 

**📧 Contacto:**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maria-fernanda-velderrain-parra/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MaferVelde)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mafer_velde@live.com.mx)
