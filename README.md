# Trading in the World

## 📋 Descripción del Proyecto

**Trading in the World** es un sitio web educativo informativo sobre trading financiero, diseñado para explicar conceptos fundamentales, tipos de trading, y las herramientas necesarias para operar en mercados financieros. El proyecto está desarrollado con tecnologías web estándar (HTML5, CSS3) y sigue principios de diseño responsive para garantizar accesibilidad en diversos dispositivos.

---

## 🎯 Objetivos del Proyecto

- Proporcionar formación teórica sobre trading y sus riesgos
- Explicar los diferentes tipos de trading según horizonte temporal
- Detallar las herramientas y requisitos necesarios para operar
- Ofrecer contenido especializado sobre **Scalping** como estrategia de alta frecuencia

---

## 🏗️ Arquitectura del Proyecto

### Estructura de Directorios
trading-in-the-world/
├── pages/
│ ├── index.html # Página principal: conceptos de trading
│ ├── scalping.html # Página especializada en Scalping
│ └── form.html # Formulario de registro (Formulary Origin)
├── styles/
│ ├── global.css # Estilos globales y reset
│ ├── index.css # Estilos específicos de la página principal
│ ├── scalping.css # Estilos específicos de la página de Scalping
│ └── formulario.css # Estilos del formulario
├── assets/
│ └── image/
│ └── imag-trading.png # Logo/imagen del proyecto
└── README.md


### Tecnologías Utilizadas

| Categoría | Tecnología | Versión |
|-----------|------------|---------|
| **Frontend** | HTML5 | - |
| **Estilos** | CSS3 | - |
| **Fonts** | Google Fonts (Poppins, Roboto) | - |
| **Iconos** | IonIcons | 7.1.0 |
| **Videos** | YouTube Embed | - |

---

## 📄 Descripción de Páginas

### 1. **index.html** - Página Principal
Secciones incluidas:
- **¿Qué es el trading**: Definición, requisitos para operar, y riesgos
- **Fundamentos**: Consideraciones antes de empezar, selección de broker
- **Tipos de Trading**: Scalping, Day Trading, Swing Trading, Trading tendencial, Largo plazo
- **Herramientas**: Ordenador/tablet/smartphone, Internet, broker, cuenta y plataforma de trading

### 2. **scalping.html** - Página Especializada
Contenido detallado sobre Scalping:
- Concepto y definición
- Cuándo hacer Scalping (volatilidad vs. tranquilidad)
- Mejores mercados (acciones, índices, divisas, materias primas)
- Técnicas de Scalping (medias móviles, RSI, SAR parabólico)

### 3. **form.html** - Formulario de Registro
Campos del formulario:
- Nombre de usuario
- Nombres y apellido(s)
- Contraseña (min. 8 caracteres)
- Correo electrónico

---

## 🎨 Características de Diseño

### Principios de UI/UX
- **Diseño Responsive**: Adaptable a móviles (≤480px), tablets (≤768px), y desktop (>768px)
- **Fixed Navigation**: Menú fixed con backdrop-filter para experiencia moderna
- **Color Palette**: 
  - Fondo principal: `rgba(238, 16, 16, 0.6)` (rojo semitransparente)
  - Acentos: `#2dc7c7` (cyan) para hover y focus
  - Dark mode: `rgba(2, 2, 2, 0.8-0.9)` para formularios y footer
- **Tipografía**: Poppins (body) + Roboto (títulos h2)

### Componentes Clave
- **Hamburger Menu**: Implementado con `<details>`/`<summary>` para navegación móvil
- **Social Icons**: IonIcons con animación hover (transform translateY)
- **Video Embeds**: YouTube iframe responsivo con aspect-ratio 16/9
- **Form Inputs**: Dark theme con focus outline cyan (#2dc7c7)

---

## 🔧 Configuración del Entorno

### Requisitos
- Navegador moderno con soporte para CSS3 y HTML5
- Conexión a Internet para cargar CDN (IonIcons, Google Fonts)

### Instalación
1. Clonar el repositorio:
```bash
git clone https://github.com/ibarcaubet/trading-in-the-world.git
```

2. Navegar al directorio:
```bash
cd trading-in-the-world
```

3. Abrir `pages/index.html` en el navegador o usar un servidor local:
```bash
# Con Node.js
npx serve

# Con Python 3
python3 -m http.server 8000
```

---

## 📱 Responsive Breakpoints

| Dispositivo | Breakpoint | Comportamiento |
|-------------|------------|----------------|
| Mobile | ≤480px | Menú derecho oculto, article margin 0.5rem |
| Tablet | ≤768px | container-tipos en columna, margin 1rem |
| Desktop | >768px | Layout horizontal completo, margin 3rem |

---

## 🚀 Próximas Mejoras (Roadmap)

- [ ] Integración con React para componentes reutilizables
- [ ] API backend con Node.js/Express para validar formulario
- [ ] MongoDB para almacenar datos de usuarios
- [ ] Chart.js para gráficos de trading interactivos
- [ ] Authentication con JWT
- [ ] Dark/Light mode toggle
- [ ] SEO optimización (meta tags, sitemap)

---

## 📚 Recursos y Referencias

- **Contenido**: Basado en material de Esade (Carlo Sala, Departamento de Economía, Finanzas y Contabilidad)
- **Regulación**: Referencias a CNMV (Comisión Nacional del Mercado de Valores) y ESMA (Autoridad Europea de Valores y Mercados)
- **Fuentes**: 
  - [IonIcons](https://unpkg.com/ionicons@7.1.0/)
  - [Google Fonts](https://fonts.googleapis.com)

---

## 👨💻 Autor

**Ibar Caubet**  
Full Stack Web Developer | React + Node.js + MongoDB  
📍 Pilar, Buenos Aires, AR  
🔗 [GitHub](https://github.com/ibarcaubet)

---

## 📄 Licencia

Este proyecto está bajo la licencia **MIT**. VéÄ© LICENSE para más detalles.

---

## 🤝 Contribuyendo

1. Fork el proyecto
2. Crear branch para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push al branch (`git push origin feature/AmazingFeature`)
5. Abrir Pull Request

---

**⚠️ Nota Importante**: Este sitio es **educativo**. El trading conlleva riesgos elevados. Según estadísticas, el 90% de traders no sofisticados pierden 90% de su dinero en los primeros 90 días. Siempre forma te antes de operar.

---

`Made with ☕ by Ibar Caubet | ©2024 Trading in the World`
