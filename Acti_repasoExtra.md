---

## **Actividad: `git add` y Patrones**

---

### **Estructura Inicial del Proyecto**
1. Crea la siguiente estructura de archivos y directorios:
   ```bash
   mkdir -p proyecto-patrones/{docs,scripts,images,temp}
   touch proyecto-patrones/{docs/{manual.txt,guia.md,readme.txt},scripts/{app.js,utils.py,config.js},images/{logo.png,icon.jpg,banner.gif},temp/{pruebas.log,debug.txt,draft.md}}
   ```

2. Verifica que la estructura es la siguiente:

   ```
   proyecto-patrones/
   ├── docs/
   │   ├── manual.txt
   │   ├── guia.md
   │   ├── readme.txt
   ├── scripts/
   │   ├── app.js
   │   ├── utils.py
   │   ├── config.js
   ├── images/
   │   ├── logo.png
   │   ├── icon.jpg
   │   ├── banner.gif
   ├── temp/
       ├── pruebas.log
       ├── debug.txt
       ├── draft.md
   ```

3. Inicializa el repositorio y haz un commit inicial.

---

### **COMENZAMOS**

#### **1. Prepara archivos con patrones simples**

1. Añade  **solo** los archivos `.txt` que están en la carpeta `docs/` y muestra el estado.

2. Haz un commit.
---

#### **2. Trabaja con subdirectorios y extensiones**

1. Añade **todos los archivos `.js`** del directorio `scripts/` pero **excluye `config.js`** y muestra el estado.

2. Haz un commit con los cambios.
---

#### **3. Máscaras en niveles**

1. Añade **todas las imágenes excepto las que terminan en `.gif`**

2. Confirma que los archivos `.png` y `.jpg` están en el área de preparación y muestra el estado.

3. Haz un commit.
---
