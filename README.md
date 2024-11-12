# Como construir esta documento

Crear un virtual environment de python para evitar problemas de 
de dependencias de versiones con otros proyectos.

``` bash
python -m venv venv
```

Activar el virtual env:

``` bash
source venv/bin/activate
```

Instalar mkdocs-material

``` bash
pip install mkdocs-material
```

Adición de la funcionalidad de zoom a las imágenes

``` bash
pip install mkdocs-glightbox
```

Para crear un nuevo proyecto (pero no es necesario en este caso porque 
ya está creado):

``` bash
mkdocs new .
```

Para observar en tiempo real los cambios al documento se lanza un servidor local:

``` bash
mkdocs serve
```
