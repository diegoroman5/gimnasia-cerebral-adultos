# 📤 GUÍA PARA SUBIR A GITHUB

## Opción 1: Usar GitHub Desktop (MÁS FÁCIL)

### Paso 1: Descargar GitHub Desktop
1. Ve a https://desktop.github.com/
2. Descarga e instala la aplicación
3. Inicia sesión con tu cuenta de GitHub

### Paso 2: Crear el repositorio
1. Abre GitHub Desktop
2. Click en "File" → "New Repository"
3. Nombre: `gimnasia-cerebral`
4. Description: `Landing page de gimnasia cerebral para adultos mayores`
5. Local Path: Selecciona la carpeta donde descargaste estos archivos
6. Initialize with README: NO (ya tenemos uno)
7. Click "Create Repository"

### Paso 3: Publicar a GitHub
1. En GitHub Desktop, click "Publish repository"
2. Asegúrate que "Keep this code private" esté desmarcado (para que sea público)
3. Click "Publish repository"
4. ¡Listo! Tu código está en GitHub

### Paso 4: Activar GitHub Pages
1. Ve a tu repositorio en GitHub.com
2. Click en "Settings" (⚙️)
3. En el menú lateral, click en "Pages"
4. En "Source", selecciona "main" branch
5. Click "Save"
6. Espera 1-2 minutos
7. Tu página estará disponible en: `https://glivo.github.io/gimnasia-cerebral/`

---

## Opción 2: Usar la Terminal (PARA USUARIOS TÉCNICOS)

### Paso 1: Instalar Git
Si no tienes Git instalado:
- Mac: `brew install git`
- Windows: Descarga de https://git-scm.com/
- Linux: `sudo apt-get install git`

### Paso 2: Configurar Git (primera vez)
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

### Paso 3: Crear repositorio en GitHub
1. Ve a https://github.com/new
2. Repository name: `gimnasia-cerebral`
3. Description: `Landing page de gimnasia cerebral para adultos mayores`
4. Public repository
5. NO marcar "Initialize with README"
6. Click "Create repository"

### Paso 4: Subir tu código
Abre la terminal en la carpeta del proyecto y ejecuta:

```bash
# Inicializar Git
git init

# Agregar todos los archivos
git add .

# Hacer el primer commit
git commit -m "Initial commit: Landing page de gimnasia cerebral"

# Conectar con GitHub (reemplaza USUARIO con tu usuario de GitHub)
git remote add origin https://github.com/USUARIO/gimnasia-cerebral.git

# Cambiar a rama main
git branch -M main

# Subir el código
git push -u origin main
```

### Paso 5: Activar GitHub Pages
1. Ve a tu repositorio en GitHub.com
2. Click en "Settings" (⚙️)
3. En el menú lateral, click en "Pages"
4. En "Source", selecciona "main" branch
5. Click "Save"
6. Tu página estará en: `https://USUARIO.github.io/gimnasia-cerebral/`

---

## Opción 3: Subir archivos directamente en GitHub.com (MÁS SIMPLE)

### Paso 1: Crear repositorio
1. Ve a https://github.com/new
2. Repository name: `gimnasia-cerebral`
3. Description: `Landing page de gimnasia cerebral para adultos mayores`
4. Public repository
5. Marcar "Add a README file"
6. Click "Create repository"

### Paso 2: Subir archivos
1. En tu repositorio, click en "Add file" → "Upload files"
2. Arrastra TODOS los archivos de tu carpeta (excepto el README que ya existe)
3. En "Commit changes", escribe: "Subir landing page completa"
4. Click "Commit changes"

### Paso 3: Actualizar README
1. Click en el archivo README.md
2. Click en el ícono de lápiz (Edit)
3. Borra el contenido
4. Copia y pega el contenido del README.md que te proporcioné
5. Click "Commit changes"

### Paso 4: Activar GitHub Pages
1. Click en "Settings" (⚙️)
2. En el menú lateral, click en "Pages"
3. En "Source", selecciona "main" branch
4. Click "Save"
5. Tu página estará en: `https://USUARIO.github.io/gimnasia-cerebral/`

---

## ✅ VERIFICAR QUE TODO FUNCIONA

Después de subir, verifica:

1. **README se ve bien**
   - Ve a tu repositorio
   - El README debe mostrarse formateado con todos los emojis

2. **Todos los archivos están**
   - Debe haber: index.html, README.md, LICENSE, .gitignore
   - Carpeta assets/images/ con todas las imágenes

3. **GitHub Pages funciona**
   - Espera 2-3 minutos después de activar Pages
   - Visita: `https://USUARIO.github.io/gimnasia-cerebral/`
   - Debe verse exactamente como tu página local

4. **Imágenes cargan correctamente**
   - Todas las imágenes deben verse
   - Los logos deben aparecer
   - Los testimonios deben tener fotos

5. **Video funciona**
   - El video de YouTube debe reproducirse
   - Debe verse sin problemas

6. **Botones funcionan**
   - "Comprar ahora" debe ir a Hotmart
   - Enlaces de redes sociales (actualízalos)

---

## 🔄 ACTUALIZAR EL SITIO DESPUÉS

### Si usas GitHub Desktop:
1. Haz cambios en tu archivo index.html
2. Abre GitHub Desktop
3. Verás los cambios listados
4. Escribe un mensaje describiendo el cambio
5. Click "Commit to main"
6. Click "Push origin"
7. Espera 1-2 minutos y los cambios estarán en vivo

### Si usas Terminal:
```bash
# Después de hacer cambios
git add .
git commit -m "Descripción del cambio"
git push
```

### Si usas GitHub.com:
1. Ve al archivo que quieres editar
2. Click en el ícono de lápiz
3. Haz tus cambios
4. Click "Commit changes"

---

## 🆘 PROBLEMAS COMUNES

**Problema**: GitHub Pages muestra 404
- **Solución**: Espera 5 minutos más. Puede tardar.
- **Solución**: Verifica que el archivo se llame `index.html` (no Index.html)

**Problema**: Las imágenes no se ven
- **Solución**: Verifica que la carpeta sea `assets/images/` (no Assets o Images)
- **Solución**: Verifica que las rutas en index.html sean correctas

**Problema**: El video no carga
- **Solución**: Verifica tu conexión
- **Solución**: Prueba en modo incógnito
- **Solución**: Verifica que YouTube no esté bloqueado

**Problema**: Los cambios no se reflejan
- **Solución**: Limpia el caché del navegador (Ctrl + Shift + R)
- **Solución**: Espera 2-3 minutos después de hacer push

---

## 📞 NECESITAS AYUDA?

Si tienes problemas:
1. Lee los mensajes de error con cuidado
2. Google el mensaje de error
3. Consulta: https://docs.github.com/pages
4. O contacta a tu desarrollador web

---

¡ÉXITO CON TU PROYECTO! 🎉
