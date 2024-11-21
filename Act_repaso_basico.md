## **Ejercicio**

### **Escenario**
Estás desarrollando una página web y necesitas gestionar las ramas de desarrollo y resolver conflictos.

---

### **Pasos del Ejercicio**

#### **1. Configuración Inicial**
1. Crea un repositorio nuevo llamado *Apellido1Apellido2Nombre_2425* e inicia git.
2. Crea un archivo básico `index.html` y haz tu primer commit:
   ```html
   <!DOCTYPE html>
   <html>
   <head>
       <title>Mi Página Web</title>
   </head>
   <body>
       <h1>Bienvenidos a mi página web</h1>
   </body>
   </html>
   ```
---

#### **2. Crea Ramas para Nuevas Funcionalidades**
Crea tres ramas para trabajar en nuevas características:
1. `rama-header`: Modificaciones en el encabezado.
2. `rama-footer`: Creación del pie de página.
3. `rama-estilos`: Diseño con CSS.

---

#### **3. Implementa Funcionalidades**
Trabaja en cada rama por separado.

##### **En `rama-header`**
1. Cambia a la rama
2. Modifica el archivo `index.html` para agregar un encabezado:
   ```html
   <header>
       <h1>Encabezado Principal</h1>
   </header>
   ```
3. Haz un commit

##### **En `rama-footer`**
1. Cambia a la rama
2. Modifica el archivo `index.html` para agregar un pie de página:
   ```html
   <footer>
       <p>Derechos reservados © 2024</p>
   </footer>
   ```
3. Haz un commit

##### **En `rama-estilos`**
1. Cambia a la rama
2. Crea un archivo nuevo `styles.css` con el siguiente contenido:
   ```css
   body {
       font-family: Arial, sans-serif;
       background-color: #f0f0f0;
   }
   header {
       background-color: #4CAF50;
       color: white;
       text-align: center;
       padding: 10px;
   }
   footer {
       background-color: #333;
       color: white;
       text-align: center;
       padding: 5px;
   }
   ```
3. Modifica `index.html` para enlazar el archivo CSS:
   ```html
   <link rel="stylesheet" href="styles.css">
   ```
4. Haz un commit
---

#### **4. Fusiona las Funcionalidades**
Fusiona **todas** las ramas en la rama principal **`main`**.

#### **¡Se genera un conflicto!**
Habrá un conflicto entre los cambios de `rama-estilos` (enlazar el CSS) y los cambios en el HTML. Resuelve el conflicto!

1. Edita el archivo `index.html` para mantener todos los cambios:
   ```html
   <!DOCTYPE html>
   <html>
   <head>
       <title>Mi Página Web</title>
       <link rel="stylesheet" href="styles.css">
   </head>
   <body>
       <header>
           <h1>Encabezado Principal</h1>
       </header>
       <h1>Bienvenidos a mi página web</h1>
       <footer>
           <p>Derechos reservados © 2024</p>
       </footer>
   </body>
   </html>
   ```
2. Marca el conflicto como resuelto:
   ```bash
   git add index.html
   git commit -m "Resolved merge conflict"
   ```
---
