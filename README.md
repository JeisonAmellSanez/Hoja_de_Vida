# Mi Hoja de Vida - Página Web

Una página web moderna y profesional para mostrar tu currículum vitae en línea.

## 🚀 Características

- ✨ Diseño moderno y responsive
- 🎨 Gradientes y animaciones suaves
- 📱 Compatible con dispositivos móviles
- 💼 Secciones completas: experiencia, educación, habilidades, proyectos
- 🎯 Fácil de personalizar

## 📋 Cómo Personalizar

1. **Información Personal**: Edita el archivo `index.html` y reemplaza:
   - "Tu Nombre Completo"
   - Tu información de contacto
   - Enlaces a LinkedIn y GitHub

2. **Experiencia y Educación**: Modifica las secciones con tu información real

3. **Habilidades**: Ajusta los porcentajes de las barras según tu nivel

4. **Colores**: En `styles.css` puedes cambiar el gradiente principal:
   ```css
   background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
   ```

## 🌐 Cómo Publicar en GitHub Pages

1. **Crear un repositorio en GitHub**:
   - Ve a GitHub.com e inicia sesión
   - Haz clic en "New repository"
   - Nómbralo como: `tu-usuario.github.io` (reemplaza "tu-usuario" con tu nombre de usuario)
   - Marca como público

2. **Subir los archivos**:
   ```bash
   git init
   git add .
   git commit -m "Primer commit - Mi hoja de vida"
   git branch -M main
   git remote add origin https://github.com/tu-usuario/tu-usuario.github.io.git
   git push -u origin main
   ```

3. **Activar GitHub Pages**:
   - Ve a Settings → Pages
   - En "Source", selecciona "main" branch
   - Guarda los cambios

4. **Ver tu sitio**:
   - Tu página estará disponible en: `https://tu-usuario.github.io`

## 📁 Estructura del Proyecto

```
resume-website/
│
├── index.html      # Página principal con tu información
├── styles.css      # Estilos y diseño
├── script.js       # Animaciones e interactividad
└── README.md       # Este archivo
```

## 🎨 Personalización Avanzada

### Cambiar la Foto de Perfil
Reemplaza el ícono de Font Awesome en `index.html` con una imagen:
```html
<div class="profile-img">
    <img src="tu-foto.jpg" alt="Tu Nombre">
</div>
```

Y agrega este CSS en `styles.css`:
```css
.profile-img img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 5px solid white;
}
```

### Agregar más secciones
Puedes duplicar cualquier `<section>` en el HTML y personalizarla.

## 💡 Consejos

- Usa imágenes optimizadas para web (JPG/PNG comprimidos)
- Mantén la información actualizada
- Prueba tu sitio en diferentes dispositivos
- Agrega enlaces a tus proyectos reales en GitHub

## 📧 Contacto

Actualiza tus datos de contacto en el header del archivo HTML.

---

¡Buena suerte con tu búsqueda laboral! 🎯
