# 🦇 Wayne Enterprises — Django Project
## Informe Estratégico: Transformación Digital y Migración a la Nube

## ⚙️ Requisitos del sistema

Antes de ejecutar el proyecto, asegúrate de tener instalado:

- Python 3.10 o superior
- pip (gestor de paquetes de Python)
- Git
 
---
 
## INSTALACIÓN
 
```bash
git clone https://github.com/nicohr3366/waynetech-landing.git
cd waynetech
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
pip install django pillow
python manage.py makemigrations
python manage.py migrate
python manage.py loaddata core/fixtures/initial_data.json
python manage.py createsuperuser
python manage.py runserver
```
 
Abrir: http://127.0.0.1:8000/
Admin: http://127.0.0.1:8000/admin/
 
---
 
## IMÁGENES (carpeta media/)
 
Las imágenes **no están en el repositorio**. Deben ser enviadas por separado via WhatsApp.
 
Una vez recibida agregar en la carpeta `waynetech/media/`, pegarla en la raíz del proyecto:
 
> ⚠️ Sin la carpeta `media/` las imágenes no se verán en el sitio.
 
---
 
## SECCIONES
 
1. Hero — estadísticas globales de la empresa
2. Corporativo — ficha empresarial y contexto estratégico
3. Organigrama — CEO + 7 C-levels con perfil cloud (click = modal)
4. Divisiones — 7 unidades de negocio con prioridad cloud (click = modal)
5. Tecnología — gadgets filtrados por tipo (click = ficha técnica)
6. Amenazas — villanos filtrados por nivel/estado (click = expediente)
7. Estrategia Cloud — modelos operativos, CCoE, fases migración, Matriz RACI
8. KPIs — 10 indicadores agrupados por pilar estratégico con barras de progreso