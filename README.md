# 🤖 Sí, Otro Curso de IA

<div align="center">

![AI Course Banner](https://img.shields.io/badge/AI-Course-blue?style=for-the-badge&logo=artificial-intelligence)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

**Una landing page moderna y elegante para promocionar un curso práctico de Inteligencia Artificial**

[🚀 Ver Demo](#) • [📚 Documentación](#características-principales) • [🐛 Reportar Bug](#contacto)

</div>

---

## 📋 Descripción del Proyecto

Este proyecto es una **Single Page Application (SPA)** diseñada para promocionar un curso práctico sobre Inteligencia Artificial. La página se enfoca en la **usabilidad** y **accesibilidad**, ofreciendo una experiencia de usuario moderna, fluida y totalmente adaptable a cualquier dispositivo.

## ✨ Características Principales

### 🎨 **Diseño Responsivo**
- Optimizada para dispositivos de escritorio, tabletas y móviles
- Adaptación fluida a cualquier tamaño de pantalla
- Experiencia consistente en todos los dispositivos

### 🎭 **Animaciones Dinámicas**
- Implementación de la API `Intersection Observer`
- Animaciones de entrada (`fade-in`) activadas por scroll
- Transiciones suaves y naturales

### 🧭 **Navegación Fluida**
- Barra de navegación con indicador de sección activa
- Desplazamiento suave entre secciones
- Experiencia de navegación intuitiva

### 📱 **Menú de Hamburguesa**
- Menú adaptable optimizado para dispositivos móviles
- Mejora significativa de la usabilidad en pantallas pequeñas
- Transiciones animadas

### 🪟 **Modal Interactivo**
- Pop-up con información detallada de los módulos del curso
- Carga de contenido sin refrescar la página
- Fácil cierre y navegación

## 🛠️ Tecnologías Utilizadas

| Tecnología | Propósito |
|------------|-----------|
| **HTML5** | Estructura semántica y accesible |
| **CSS3** | Estilos personalizados, variables CSS y media queries |
| **JavaScript** | Interactividad, animaciones y lógica de la aplicación |

## 📁 Estructura del Proyecto

```
📦 si-otro-curso-de-ia/
├── 📄 index.html          # Archivo principal (HTML + CSS + JS)
├── 📖 README.md           # Documentación del proyecto
└── 📋 .gitignore         # Archivos ignorados por Git
```

> **💡 Nota:** El proyecto está diseñado como un **archivo único** para facilitar el despliegue y la gestión.

## 🚀 Despliegue en Netlify

### ⚠️ Problema Común: Error 404

El problema más frecuente al desplegar en **Netlify** es el **nombre del archivo principal**.

> **🔑 Regla de Oro:** El archivo HTML raíz **DEBE** llamarse `index.html`

Si tu archivo tiene un nombre diferente (`home.html`, `inicio.html`, `main.html`, etc.), el despliegue parecerá exitoso, pero mostrará un **error 404** al acceder a la URL.

### 🔧 Solución del Error

#### **Opción 1: Línea de Comandos Git**
```bash
git mv <nombre-de-tu-archivo>.html index.html
git commit -m "Renombra el archivo principal a index.html"
git push
```

#### **Opción 2: Interfaz de GitHub**
1. Navega hasta el archivo en tu repositorio
2. Haz clic en el icono del lápiz (✏️ **Editar**)
3. Cambia el nombre a `index.html` en la parte superior
4. Guarda los cambios con un commit

## 🚀 Cómo Usar Este Proyecto

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/si-otro-curso-de-ia.git
   ```

2. **Abre el archivo:**
   ```bash
   cd si-otro-curso-de-ia
   open index.html  # En macOS
   # o simplemente abre index.html en tu navegador favorito
   ```

3. **¡Listo!** 🎉 No requiere instalación de dependencias

## 🌟 Características Técnicas

- ✅ **Responsive Design** con CSS Grid y Flexbox
- ✅ **Animaciones CSS** con `@keyframes`
- ✅ **JavaScript Vanilla** sin dependencias externas
- ✅ **Optimizado para SEO** con etiquetas meta
- ✅ **Accesibilidad** siguiendo estándares WCAG
- ✅ **Performance** optimizado para carga rápida

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para cambios importantes:

1. Fork el proyecto
2. Crea tu Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la Branch (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 📞 Contacto

Para cualquier consulta sobre este proyecto, no dudes en contactar al creador a través de los enlaces disponibles en la página del proyecto.

---

<div align="center">

**¿Te gustó este proyecto?** ⭐ ¡No olvides darle una estrella!

![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge)

</div>
