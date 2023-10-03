# template_performance
Performance test project template
# Asegúrate de estar en el directorio de tu proyecto
cd ruta/de/tu/proyecto

# Crea un entorno virtual
python3 -m venv venv

# Activa el entorno virtual
source venv/bin/activate
pip install -r requirements.txt
locust -f locustfile.py --headless -u 10 -r 2 --host=https://tu-aplicacion.com
