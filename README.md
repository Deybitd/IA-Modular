# IA-Modular
## Decargar Proyecto desde la fuente original
```
git clone https://github.com/ultralytics/yolov5
cd yolov5
pip install -r requirements.txt  
pip install Ipython
```

## Verificar Instalacion Proyecto
```
import torch
from IPython.display import Image, clear_output  # to display images

clear_output()
print(f"Setup complete. Using torch {torch.__version__} ({torch.cuda.get_device_properties(0).name if torch.cuda.is_available() else 'CPU'})")
```




### Descargar los pesos entrenados para deteccion de legos en este repositorio y agregarlo a la carpeta del proyecto yolov5

### Ejecutar la IA 
python detect.py --weights best-lego.pt --source 0 
