Examen Practic - Configuracio inicial
# Cognom1Cognom2Examen2425
Aquest projecte és un exemple bàsic d'una pàgina web per a l'examen.
# Examen: GuerreroCastilloExamen2425

## **1. Configuración inicial**

### **1.1. Comprobar versión de Git**
- Comando ejecutado:
  ```bash
  git --version
  ```
- ![Captura de la versión de Git](./Captures%20de%20pantalla/img1.png)

### **1.2. Configurar Git**
- Comando para configurar usuario y correo:
  ```bash
  git config --global user.name "TuNombre"
  git config --global user.email "TuCorreo@example.com"
  ```
- Comando para verificar configuración:
  ```bash
  git config --list
  ```
- - ![Captura de la versión de Git](./Captures%20de%20pantalla/img2.png)

### **1.3. Inicializar repositorio**
- Comandos ejecutados:
  ```bash
  mkdir Cognom1Cognom2Examen2425
  cd Cognom1Cognom2Examen2425
  git init
  echo "# Cognom1Cognom2Examen2425" > README.md
  git add README.md
  git commit -m "1 - Git init"
  ```
- ![Captura de la versión de Git](./Captures%20de%20pantalla/img3.png)
- ![Captura de la versión de Git](./Captures%20de%20pantalla/img4.png)
---

## **2. Creación del proyecto web**

- Archivos creados:
  ```bash
  touch index.html testunitari.html style.css main.js
  ```
  - ![Captura de la versión de Git](./Captures%20de%20pantalla/img5.png)
---

## **3. Gestión con Git**

### **3.1. Añadir archivos al staging**
- Comando utilizado:
  ```bash
  git add *.html *.css
  ```
- - ![Captura de la versión de Git](./Captures%20de%20pantalla/img4.png)

### **3.2. Verificar estado del repositorio**
- Comando utilizado:
  ```bash
  git status
  ```
- ![Captura de la versión de Git](./Captures%20de%20pantalla/img5.png)

### **3.3. Eliminar archivo del staging**
- Comando utilizado:
  ```bash
  git reset testunitari.html
  ```

### **3.4. Realizar commit**
- Comando utilizado:
  ```bash
  git commit -m "2- Estructura bàsica"
  ```

### **3.5. Consultar historial de commits**
- Comando utilizado:
  ```bash
  git log --oneline
  ```
- - ![Captura de la versión de Git](./Captures%20de%20pantalla/img6.png)

---

## **4. Creación de ramas y documentación**

### **4.1. Crear una nueva rama**
- Comandos utilizados:
  ```bash
  git branch documentacio
  git checkout documentacio
  ```

### **4.2. Editar y documentar el archivo README.md**
- Contenido agregado:
  ```markdown
  # Cognom1Cognom2Examen2425

  Aquest projecte és un exemple bàsic d'una pàgina web per a l'examen.
  ```
- Comando para añadir y realizar commit:
  ```bash
  git add README.md
  git commit -m "3 - README.md amb documentació inicial"
  ```

### **4.3. Fusionar cambios con la rama principal**
- Comandos utilizados:
  ```bash
  git checkout main
  git merge documentacio
  ```

---

## **5. Remoto y publicación**

### **5.1. Configurar un remoto**
- Comando utilizado:
  ```bash
  git remote add origin https://github.com/kevin-guerrero/GuerreroCastilloxamen2425.git
  ```
- ![Captura de la versión de Git](./Captures%20de%20pantalla/img7.png)

### **5.2. Subir cambios al remoto**
- Comando utilizado:
  ```bash
  git push -u origin main
  ```
- ![Captura de la versión de Git](./Captures%20de%20pantalla/img8.png)

### **5.3. Publicar en Vercel**
- Enlace al proyecto publicado:
  ```
  https://enllaç.vercel.app
  ```

---

## **Conclusión**
Este documento detalla los pasos realizados para completar el examen, incluyendo la creación de un proyecto web básico, la gestión con Git, el uso de ramas y la publicación en un entorno remoto.