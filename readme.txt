# RASFF Alerts Extractor

Este proyecto es una aplicación en **Python** que extrae alertas de seguridad alimentaria desde la web de **RASFF** y las guarda en un archivo **Excel**. Usa **Selenium** para la automatización web, **Pandas** para el manejo de datos y **Flet** para la interfaz gráfica.

## 🚀 Características

- **Automatización con Selenium**: Extrae datos de alertas de la web de RASFF.
- **Almacenamiento en Excel**: Guarda las alertas en un archivo con historial.
- **Interfaz gráfica moderna**: Uso de **Flet** para facilitar la interacción con los usuarios.

## 🛠 Instalación y Configuración

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/tuusuario/rasff-alerts-extractor.git
cd rasff-alerts-extractor
```

### 2️⃣ Instalar dependencias
```bash
pip install -r requirements.txt
```

### 3️⃣ Ejecutar la aplicación
```bash
python app.py
```

## 📝 Uso
1. **Selecciona una fecha**: Para obtener las alertas de un día específico.
2. **Selecciona el archivo Excel**: Donde se guardarán las alertas.
3. **Haz clic en "Extraer y Guardar"**: La aplicación obtendrá las alertas y las almacenará en el archivo seleccionado.

## 🛑 Requisitos
- Python 3.8+
- Google Chrome instalado
- ChromeDriver compatible con tu versión de Chrome

