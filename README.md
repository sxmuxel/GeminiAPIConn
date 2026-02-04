# Procedimiento para ejecutar el código de conexión

## Requisitos previos
- Python
- Git
- Clave de acceso a la API de Gemini

## Instrucciones de ejecución (Windows)

### Paso 1: Clonar repositorio

En la terminal:
```bash
git clone https://github.com/sxmuxel/GeminiAPIConn.git
cd GeminiAPIConn
```

### Paso 2: Crear entorno virtual

En la terminal:
```bash
python -m venv venv
.\venv\Scripts\activate
```

### Paso 3: Instalar dependencias

En la terminal:
```bash
pip install -r requirements.txt
```

### Paso 4: Configurar la variable de entorno

Crear un archivo .env en la raíz del proyecto a partir del archivo de ejemplo.

En la terminal:
```bash
copy .env.example .env
```
Reemplazar la clave genérica por la clave propia.

### Paso 5: Ejecutar el script de conexión

En la terminal:
```bash
python app_gemini.py
```

---

# Evidencia de ejecución del script de conexión
<img width="1290" height="948" alt="Evidencia de ejecución" src="https://github.com/user-attachments/assets/f1a168b6-a78f-41af-9545-d48fdf525f39" />




