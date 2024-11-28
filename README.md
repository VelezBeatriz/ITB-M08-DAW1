# ITB-M08-DAW1

## Git Command

Instalar Git y verificar la versión
```bash
sudo apt update #Actualizar antes de instalar
sudo apt install git #Instalar git
git --version #Ver la versión
```
Configurar nombre y correo
```bash
git config --global user.name "TuNombreDeUsuario"
git config --global user.email "tuemail@example.com"
```
Comprobar la configuración de Git
```bash
git config --list
```

Inicializar un repositorio
```bash
git init .
```

Añadir un archivo o varios
```bash
git add . #git add index.html
git reset . #Sacar archivos del add
```

Comprobar el estado del repositorio
```bash
git status
```

Comprobar el historial
```bash
git log
git log --oneline --decorate --all --graph
```

Volver al último git registrado
```bash
git checkout -- .
```

Realizar un commit
```bash
git commit -m "Mensaje"
```

Identificar la rama
```bash
git branch
git branch nombre_rama
git branch --all #Para ver todo
```

Cambiar de rama
```bash
git checkout nombre rama
```

Ver la versión corta del Status
```bash
git status --short
```

Crear un alias
```bash
git config --global alias.s status --short #Crear un alias llamado s que realizará un status --short
```

Modificar la configuración global del Git
```bash
git config --global -e
```

Unir las ramas
```bash
# Situarte en la rama que recibira los cambios
git merge rama-alterna
```

Borrar ramas
```bash
git branch -d rama-nombre -f #Borrar forzado
```

Crear rama y moverme a la rama, hacer el switch a la rama
```bash
git checkout -b nombre-rama
```

Ver lineas modificadas
```bash
git diff
git diff --staged
```

Añadir a un repositorio remoto
```bash
git remote add nombreRemoto URL #Ejemplo: git remote add origin URL
```

Subir los cambios del repositorio local al remoto
```bash
git pish nombreRemoto rama #Ejemplo: git push origin main
```

Descargar los cambios del repositorio remoto al local y los combina
```bash
git pull nombreRemoto rama #Ejemplo: git pull origin main
```
