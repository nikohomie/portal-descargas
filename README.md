# 🚀 Portal de Descargas - Herramientas de Desarrollo

Portal web profesional para descarga centralizada de herramientas de desarrollo esenciales. Desarrollado por **GESSOF**.

![GESSOF Banner](./assets/Banner_Linkedin.jpg)

## 📋 Descripción

Portal de descargas diseñado para facilitar el acceso a herramientas fundamentales de desarrollo de software. Interfaz moderna, responsive y profesional con diseño inspirado en tecnologías actuales.

## 🛠️ Herramientas Incluidas

### ☕ Java JDK 21 LTS
- Kit de desarrollo oficial de Java
- Versión Long Term Support (LTS)
- Incluye compilador, herramientas y bibliotecas
- Ideal para desarrollo empresarial

### 💡 IntelliJ IDEA Community Edition
- IDE inteligente y potente
- Soporte para Java, Kotlin y más
- Gratuito y de código abierto
- Características avanzadas de productividad

### 🔮 Postman
- Plataforma completa para testing de APIs
- Soporte para REST, GraphQL y SOAP
- Interfaz intuitiva y colaborativa
- Herramientas de documentación integradas

### 💬 Discord
- Comunicación en tiempo real
- Canales de voz, texto y video
- Ideal para equipos de desarrollo
- Colaboración efectiva

## ✨ Características

- 🔒 **Seguro y Confiable**: Todas las descargas de fuentes oficiales verificadas
- ⚡ **Actualizaciones Constantes**: Últimas versiones estables
- 📦 **Centralizado**: Todo en un solo lugar
- 🎨 **Diseño Profesional**: Interfaz moderna y responsive
- 🌐 **Open Source**: Código disponible para la comunidad

## 🚀 Inicio Rápido

### Instalación Local

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/portal-descargas.git
cd portal-descargas
```

2. Crea la estructura de carpetas:
```bash
mkdir instaladores assets
```

3. Coloca los instaladores en la carpeta `instaladores/`:
   - `jdk-21.exe`
   - `ideaIC.exe`
   - `Postman-win64-Setup.exe`
   - `DiscordSetup.exe`

4. Abre `index.html` en tu navegador

### Despliegue en GitHub Pages

1. Ve a Settings > Pages
2. Selecciona la rama `main` y carpeta `/root`
3. Guarda y espera unos minutos
4. Tu portal estará disponible en: `https://tu-usuario.github.io/portal-descargas`

## 📁 Estructura del Proyecto

```
portal-descargas/
│
├── index.html              # Página principal
├── README.md              # Este archivo
│
├── assets/                # Recursos estáticos
│   └── Banner_Linkedin.jpg
│
└── instaladores/          # Archivos de instalación
    ├── jdk-21.exe
    ├── ideaIC.exe
    ├── Postman-win64-Setup.exe
    └── DiscordSetup.exe
```

## 🎨 Tecnologías Utilizadas

- HTML5
- CSS3 (Variables CSS, Grid, Flexbox, Animations)
- JavaScript (ES6+)
- Google Fonts (Inter)
- Diseño Responsive

## 🌟 Características del Diseño

- **Gradientes Modernos**: Colores corporativos y profesionales
- **Animaciones Suaves**: Transiciones y efectos hover
- **Cards Interactivas**: Feedback visual al usuario
- **Tipografía Profesional**: Google Fonts Inter
- **Mobile First**: Totalmente responsive
- **Accesibilidad**: Siguiendo mejores prácticas

## 🔧 Personalización

### Cambiar Colores

Modifica las variables CSS en `:root`:

```css
:root {
    --primary-color: #0a1929;
    --secondary-color: #1e88e5;
    --accent-color: #00bcd4;
    /* ... más variables */
}
```

### Agregar Nuevas Herramientas

Copia la estructura de una card existente:

```html
<div class="card">
    <span class="card-icon">🔧</span>
    <h2>Nueva Herramienta</h2>
    <span class="tag">Categoría</span>
    <p>Descripción de la herramienta</p>
    <div class="version-info">
        <strong>Información de Versión</strong>
        <span>Detalles adicionales</span>
    </div>
    <a href="./instaladores/archivo.exe" class="download-btn" download>
        Descargar
    </a>
</div>
```

## 📝 Notas Importantes

⚠️ **Archivos de Instalación**: Los archivos `.exe` no se incluyen en el repositorio por su tamaño. Descárgalos de las fuentes oficiales:
- [Java JDK 21](https://www.oracle.com/java/technologies/downloads/)
- [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
- [Postman](https://www.postman.com/downloads/)
- [Discord](https://discord.com/download)

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la Licencia MIT.

## 👨‍💻 Autor

**GESSOF** - Integramos Tecnología para agregar valor a tu negocio

- Website: [gessof.cl](https://gessof.cl)
- Email: info@gessof.cl

## 🙏 Agradecimientos

- Diseño inspirado en interfaces modernas de desarrollo
- Iconos emoji para mantener simplicidad
- Comunidad open source

---

⭐ Si este proyecto te resulta útil, considera darle una estrella en GitHub

**Última actualización**: Noviembre 2025
