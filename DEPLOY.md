# 🚀 Guía de Despliegue en GitHub Pages

## Pasos para subir tu sitio a GitHub

### 1. Crear un repositorio en GitHub

1. Ve a [GitHub](https://github.com) e inicia sesión
2. Haz clic en el botón "+" en la esquina superior derecha
3. Selecciona "New repository"
4. Nombra tu repositorio (ejemplo: `la-fuente-cafeteria`)
5. Marca como "Public"
6. NO inicialices con README (ya tienes uno)
7. Haz clic en "Create repository"

### 2. Subir archivos desde tu computadora

Abre la terminal en la carpeta de tu proyecto y ejecuta:

```bash
# Inicializar git
git init

# Agregar todos los archivos
git add .

# Hacer el primer commit
git commit -m "Initial commit - La Fuente Cafetería"

# Conectar con tu repositorio de GitHub
git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git

# Subir los archivos
git branch -M main
git push -u origin main
```

### 3. Activar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Haz clic en "Settings" (Configuración)
3. En el menú lateral, busca "Pages"
4. En "Source", selecciona:
   - Branch: `main`
   - Folder: `/ (root)`
5. Haz clic en "Save"
6. Espera 2-3 minutos

### 4. Ver tu sitio publicado

Tu sitio estará disponible en:
```
https://TU-USUARIO.github.io/TU-REPOSITORIO/
```

## 📋 Checklist de Verificación

- ✅ Diseño responsive (móvil, tablet, escritorio)
- ✅ Carrusel interactivo funcionando
- ✅ Slider infinito animado
- ✅ Logo SVG personalizado
- ✅ Navegación funcional
- ✅ Transiciones suaves
- ✅ Meta tags para SEO
- ✅ Código limpio y comentado
- ✅ README.md documentado

## 🔄 Actualizar el sitio

Cuando hagas cambios, ejecuta:

```bash
git add .
git commit -m "Descripción de los cambios"
git push
```

Los cambios se reflejarán en 1-2 minutos.

## 🎨 Estructura del Proyecto

```
proyecto/
├── index.html          # Página principal (raíz para GitHub Pages)
├── pages/
│   ├── index.html     # Versión alternativa
│   └── styles.css     # Estilos CSS
├── assets/
│   ├── logo.svg       # Logo personalizado
│   └── *.jpg          # Imágenes del sitio
├── README.md          # Documentación
├── DEPLOY.md          # Esta guía
└── .gitignore         # Archivos a ignorar
```

## 🌐 Compatibilidad de Navegadores

- ✅ Chrome/Edge (últimas 2 versiones)
- ✅ Firefox (últimas 2 versiones)
- ✅ Safari (últimas 2 versiones)
- ✅ Opera (últimas 2 versiones)
- ✅ Navegadores móviles

## 📱 Breakpoints Responsive

- 📱 Móvil pequeño: 320px - 480px
- 📱 Móvil: 481px - 768px
- 💻 Tablet: 769px - 1024px
- 🖥️ Escritorio: 1025px+

## 🎯 Características Implementadas

### Diseño Visual
- Header sticky con logo SVG
- Hero section con título destacado
- Carrusel principal con controles
- Tarjetas de características con hover
- Slider infinito de valores
- Footer informativo

### Interactividad
- Carrusel con botones prev/next
- Puntos de navegación clickeables
- Botón de pausa/play
- Animación infinita automática
- Efectos hover en imágenes y botones

### Responsive
- Adaptación fluida a todos los tamaños
- Navegación colapsable en móvil
- Imágenes optimizadas por dispositivo
- Tipografía escalable

## 💡 Consejos

1. **Optimiza las imágenes**: Usa herramientas como TinyPNG antes de subir
2. **Prueba en diferentes dispositivos**: Usa las DevTools de Chrome
3. **Verifica los enlaces**: Asegúrate de que todas las rutas sean correctas
4. **Actualiza el contenido**: Personaliza textos, imágenes y datos de contacto

## 🆘 Solución de Problemas

### El sitio no se ve
- Verifica que GitHub Pages esté activado
- Espera 2-3 minutos después de activarlo
- Revisa que el repositorio sea público

### Las imágenes no cargan
- Verifica las rutas en el HTML
- Asegúrate de que las imágenes estén en la carpeta `assets/`
- Revisa que los nombres coincidan (case-sensitive)

### El CSS no se aplica
- Verifica la ruta del CSS en el `<link>`
- Limpia la caché del navegador (Ctrl + Shift + R)

---

¡Listo! Tu sitio está preparado para GitHub Pages 🎉
