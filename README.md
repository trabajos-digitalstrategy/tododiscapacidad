# Todo Discapacidad

Sitio web especializado en servicios jurídicos para personas con discapacidad.

## 🚀 Características

- **Diseño responsivo** optimizado para todos los dispositivos
- **Rendimiento optimizado** sin librerías de scroll pesadas
- **SEO optimizado** con metadatos estructurados
- **CMS integrado** con Decap CMS para gestión de contenido
- **Animaciones suaves** con GSAP
- **Accesibilidad** siguiendo estándares WCAG

## 🛠️ Tecnologías

- **Eleventy** - Generador de sitios estáticos
- **Nunjucks** - Motor de plantillas
- **SASS** - Preprocesador CSS
- **GSAP** - Librería de animaciones
- **Decap CMS** - Sistema de gestión de contenido
- **Netlify** - Hosting y despliegue

## 📦 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/trabajos-digitalstrategy/tododiscapacidad.git

# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm start
```

## 🚀 Scripts disponibles

```bash
# Desarrollo
npm start              # Inicia servidor de desarrollo con hot reload

# Construcción
npm run build          # Construye el sitio para producción
npm run build:eleventy # Construye solo Eleventy
npm run build:sass     # Compila SASS

# Utilidades
npm run debug          # Modo debug de Eleventy
```

## 📁 Estructura del proyecto

```
src/
├── _data/              # Datos globales del sitio
├── _includes/          # Plantillas y componentes
│   ├── components/     # Componentes reutilizables
│   ├── layout/         # Layouts principales
│   ├── pages/          # Plantillas de páginas
│   └── templates_md/   # Templates para markdown
├── assets/             # Recursos estáticos
│   ├── css/           # CSS compilado
│   ├── js/            # JavaScript
│   ├── sass/          # Archivos SASS
│   └── static/        # Imágenes, fuentes, etc.
├── blog/              # Contenido del blog
└── pages/             # Páginas del sitio
```

## 🎨 Personalización

### Colores y tema
Los colores del sitio se pueden personalizar en `src/assets/sass/_theme.scss`:

```scss
:root {
  --c-accent: #color-principal;
  --c-primary: #color-secundario;
  --c-secondary: #color-terciario;
}
```

### Contenido
El contenido se gestiona a través de:
- **Páginas**: Archivos `.md` en `src/pages/`
- **Blog**: Archivos `.md` en `src/blog/`
- **Datos globales**: `src/_data/global_index.json`

## 📱 CMS

El sitio incluye Decap CMS para gestión de contenido. Accede a `/admin/` para gestionar:
- Páginas del sitio
- Entradas del blog
- Configuración global

## 🚀 Despliegue

El sitio está configurado para desplegarse automáticamente en Netlify:

1. Conecta el repositorio a Netlify
2. Configura las variables de entorno si es necesario
3. El despliegue se realizará automáticamente en cada push

## 📄 Licencia

MIT License - ver [LICENSE](LICENSE) para más detalles.

## 🤝 Contribución

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📞 Contacto

Digital Strategy - [@trabajos-digitalstrategy](https://github.com/trabajos-digitalstrategy)

Proyecto: [https://github.com/trabajos-digitalstrategy/tododiscapacidad](https://github.com/trabajos-digitalstrategy/tododiscapacidad)