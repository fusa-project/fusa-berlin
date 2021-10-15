# fusa-berlin
Notebooks Jupyter para interactuar con los datos de FuSA

## Instalación
Crear un entorno virtual y activarlo:
```
virtualenv fusa-berlin
source fusa-berlin/bin/activate
```

Luego, instalar las librerías requeridas:
```
pip install -r requirements.txt
```

Agregar kernel de entorno virtual a jupyter notebook
```
python -m ipykernel install --user --name fusa-berlin --display-name fusa-berlin
```

## Ejecución
```
jupyter notebook Enviar datos a FuSA.ipynb
                 Explorar datos de FuSA.ipynb
```