# 🎵 WaveCast - Plataforma de Podcasts

![WaveCast Logo](./src/imagenes/Logos/CastWave_logo.svg)

## 📋 Descripción

WaveCast es una plataforma web moderna para reproducir y descubrir podcasts, inspirada en interfaces de streaming musical. El proyecto está desarrollado como parte del curso de CSS Grid Layout de Oracle ONE en colaboración con Alura.

## ✨ Características

- **Diseño Responsivo**: Adaptable a dispositivos móviles, tablets y escritorio
- **Navegación Intuitiva**: Menú lateral y barra de navegación inferior para móviles
- **Funcionalidad de Búsqueda**: Sistema de búsqueda dinámico con filtros en tiempo real
- **Layout con CSS Grid**: Implementación avanzada de CSS Grid y Flexbox
- **Interfaz Moderna**: Diseño con gradientes y efectos visuales atractivos
- **Accesibilidad**: Etiquetas ARIA y navegación por teclado

## 🚀 Demo

[Ver Demo en Vivo](https://dany1986-dra.github.io/WaveCast/)

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: 
  - CSS Grid Layout
  - Flexbox
  - Custom Properties (Variables CSS)
  - Media Queries para responsividad
- **JavaScript Vanilla**: Funcionalidad interactiva
- **Google Fonts**: Tipografía Open Sans

## 📁 Estructura del Proyecto

```
PROYECTO WaveCast/
├── index.html
├── README.md
└── src/
    ├── imagenes/
    │   ├── Iconos/           # Iconos SVG de la interfaz
    │   ├── Imagens/          # Imágenes de podcasts y portadas
    │   └── Logos/            # Logotipos de la aplicación
    └── style/
        ├── base.css          # Estilos base y variables
        ├── responsivo.css    # Media queries y responsividad
        └── grid-flex/
            ├── index.css     # Layout principal con Grid
            ├── menu.css      # Estilos del menú lateral
            ├── navbar.css    # Barra de navegación móvil
            ├── seccion.css   # Secciones de contenido
            ├── tarjeta.css   # Tarjetas de podcasts
            └── buscador.css  # Interfaz de búsqueda
```

## 🎨 Características de Diseño

### Layout Responsivo
- **Desktop (>1400px)**: Menú lateral completo
- **Tablet (1024px-1399px)**: Menú lateral compacto
- **Mobile (<1024px)**: Navegación inferior, menú oculto

### Paleta de Colores
```css
--color-texto-principal: #ffffff;
--azul-neon: #2BDEFD;
--azul-fondo: #01080E;
--gris-claro: #999;
--gris-oscuro: #666;
--gradiente: linear-gradient(53deg, #072041 0%, #041833 50%, #154580 100%);
```

## 🔧 Instalación y Uso

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/wavecast.git
   cd wavecast
   ```

2. **Abre el proyecto**
   - Abre `index.html` en tu navegador
   - O usa un servidor local como Live Server en VS Code

3. **Desarrollo local**
   ```bash
   # Si tienes Python instalado
   python -m http.server 8000
   
   # Si tienes Node.js instalado
   npx serve .
   ```

## 🎯 Funcionalidades

### Navegación
- **Home**: Página principal con podcasts destacados
- **Buscar**: Sistema de búsqueda con filtros en tiempo real
- **Mi Biblioteca**: Gestión de podcasts guardados
- **Playlists**: Creación y gestión de listas de reproducción

### Búsqueda Avanzada
- Búsqueda en tiempo real mientras escribes
- Filtros por título y categoría
- Resultados visuales con imágenes
- Navegación por teclado (ESC para cerrar)

### Reproductor
- Controles de reproducción intuitivos
- Barra de progreso visual
- Botones de siguiente/anterior

## 📱 Responsividad

El proyecto implementa un diseño completamente responsivo:

- **Grid Layout**: Distribución flexible del contenido
- **Flexbox**: Alineación y distribución de elementos
- **Media Queries**: Adaptación a diferentes tamaños de pantalla
- **Touch-friendly**: Botones y controles optimizados para dispositivos táctiles

## 🎓 Conceptos de CSS Aprendidos

- **CSS Grid Layout**: Grid areas, template columns/rows
- **Flexbox**: Distribución y alineación de elementos
- **Custom Properties**: Variables CSS reutilizables
- **Media Queries**: Diseño responsivo
- **Pseudo-elementos**: Efectos visuales avanzados
- **Transforms y Transitions**: Animaciones CSS

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para contribuir:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Mejoras Futuras

- [ ] Integración con API real de podcasts
- [ ] Sistema de autenticación de usuarios
- [ ] Reproducción de audio funcional
- [ ] Modo oscuro/claro
- [ ] Sincronización en la nube
- [ ] Comentarios y valoraciones
- [ ] Notificaciones push para nuevos episodios

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

**Tu Nombre**
- GitHub: [@Dany1986-dra](https://github.com/Dany1986-dra)
- LinkedIn: [Daniel Rivera Alpízar](https://linkedin.com/in/daniel-rivera-alpízar)

## 🙏 Agradecimientos

- [Oracle ONE](https://www.oracle.com/lad/education/oracle-next-education/) - Programa de educación
- [Alura](https://www.alura.com.br/) - Plataforma de cursos
- [Google Fonts](https://fonts.google.com/) - Tipografías
- Comunidad de desarrolladores por el feedback y sugerencias

---

⭐ **¡Dale una estrella al proyecto si te gustó!** ⭐

![Responsive Design](https://img.shields.io/badge/Responsive-Design-green)
![CSS Grid](https://img.shields.io/badge/CSS-Grid-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
