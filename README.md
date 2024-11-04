# URL de la API en Render

https://parcialds-fbf9.onrender.com/docs

# Configuración Local del Proyecto

1. **Clonar el repositorio**
    ```bash
    git clone https://github.com/CamilaPortal/parcialDS.git
    cd parcialDS
    ```

2. **Crear y activar un entorno virtual**
    ```bash
    python -m venv env
    source env/bin/activate
    ```

3. **Instalar las dependencias**
    ```bash
    pip install -r requirements.txt
    ```

4. **Iniciar la API**
    ```bash
    uvicorn app.main:app --reload
    ```

5. **Ejecutar los tests (Opcional)**
    ```bash
    pytest
    ```
