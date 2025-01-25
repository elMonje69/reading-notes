## Comandos Básicos de Git

### 1. **`git init`**
   Inicializa un repositorio Git vacío en el directorio actual.
   ```bash
   git init
   ```
   
### 2. **`git clone <url>`**
   Clona un repositorio remoto a tu máquina local.
   ```bash
   git clone https://github.com/usuario/repositorio.git
   ```

### 3. **`git status`**
   Muestra el estado de los archivos en tu directorio de trabajo, como los cambios no guardados.
   ```bash
   git status
   ```

### 4. **`git add <archivo>`**
   Agrega un archivo o cambios específicos al área de preparación (staging area).
   ```bash
   git add archivo.txt
   ```

### 5. **`git commit -m "<mensaje>"`**
   Realiza un commit con los cambios que has agregado al área de preparación.
   ```bash
   git commit -m "Mensaje del commit"
   ```

### 6. **`git push`**
   Sube tus cambios locales al repositorio remoto.
   ```bash
   git push origin master
   ```

### 7. **`git pull`**
   Obtiene y fusiona los cambios del repositorio remoto a tu repositorio local.
   ```bash
   git pull origin master
   ```

### 8. **`git branch`**
   Muestra las ramas locales disponibles en tu repositorio.
   ```bash
   git branch
   ```

### 9. **`git checkout <rama>`**
   Cambia a la rama especificada.
   ```bash
   git checkout nombre-de-rama
   ```

### 10. **`git merge <rama>`**
   Fusiona los cambios de una rama en la rama actual.
   ```bash
   git merge nombre-de-rama
   ```

### 11. **`git log`**
   Muestra el historial de commits.
   ```bash
   git log
   ```

### 12. **`git remote -v`**
   Muestra las URL de los repositorios remotos.
   ```bash
   git remote -v
   ```

### 13. **`git fetch`**
   Obtiene los cambios desde el repositorio remoto, pero sin fusionarlos automáticamente.
   ```bash
   git fetch
   ```

### 14. **`git reset`**
   Deshace los cambios en el área de preparación o en los commits recientes.
   ```bash
   git reset --hard
   ```

### 15. **`git diff`**
   Muestra las diferencias entre los archivos modificados y los commits previos.
   ```bash
   git diff
   ```

### 16. **`git stash`**
   Guarda cambios temporalmente para limpiar el área de trabajo.
   ```bash
   git stash
   ```

### 17. **`git tag`**
   Añade una etiqueta a un commit específico.
   ```bash
   git tag v1.0
   ```

### 18. **`git rm <archivo>`**
   Elimina un archivo del directorio de trabajo y del área de preparación.
   ```bash
   git rm archivo.txt
   ```

### 19. **`git config --global user.name "<nombre>"`**
   Establece tu nombre de usuario global.
   ```bash
   git config --global user.name "Tu Nombre"
   ```

### 20. **`git config --global user.email "<email>"`**
   Establece tu dirección de correo electrónico global.
   ```bash
   git config --global user.email "tucorreo@example.com"
   ```

Estos comandos cubren lo básico que necesitas para gestionar un repositorio Git en proyectos.