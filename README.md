# 🔍 Generador Automático de Búsquedas - Versión GitHub Pages

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-brightgreen)](https://tu-usuario.github.io/tu-repositorio)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**Sistema inteligente para generar búsquedas automáticas en Bing** - Versión estática que funciona completamente en el navegador sin necesidad de servidor backend.

## ✨ Características Principales

- 🚀 **Auto-inicio inteligente**: Inicia automáticamente después de 5 segundos
- 🎯 **100% Frontend**: Funciona sin servidor backend
- 📱 **GitHub Pages Compatible**: Perfecto para hosting gratuito
- 🔄 **Misma funcionalidad**: Replica toda la funcionalidad de la versión Flask
- 📱 **Responsive**: Funciona en dispositivos móviles y escritorio
- ⚡ **Sin dependencias críticas**: Solo usa CDNs públicos para Bootstrap y FontAwesome

## �️ Funcionalidades Completas

| Característica | Estado | Descripción |
|---------------|--------|-------------|
| ✅ Generación automática | Activa | Frases de búsqueda inteligentes |
| ✅ Auto-inicio | **NUEVO** | Inicia automáticamente en 5 segundos |
| ✅ Control de repeticiones | Activa | Configurable (por defecto: 25) |
| ✅ Tiempo de espera | Activa | Configurable (por defecto: 6s) |
| ✅ Botones de control | Activa | Pausa/Reanudar/Detener |
| ✅ Barra de progreso | Activa | Actualización en tiempo real |
| ✅ Log de actividad | Activa | Con iconos y colores |
| ✅ Apertura automática | Activa | Pestañas de búsqueda en Bing |
| ✅ Interfaz moderna | Activa | Diseño atractivo y profesional |
| ✅ Base de datos local | Activa | 100+ palabras embebidas |

## 🚀 Inicio Rápido

### Demo en Vivo
Puedes probar la aplicación directamente desde GitHub Pages: [Ver Demo](https://tu-usuario.github.io/tu-repositorio)

### Uso Local
1. Descarga el archivo `index.html`
2. Ábrelo en cualquier navegador web moderno
3. **¡Listo!** La aplicación iniciará automáticamente en 5 segundos

### Configuración Personalizada
- **Repeticiones**: Por defecto 25 (modificable en la interfaz)
- **Intervalo**: Por defecto 6 segundos (modificable en la interfaz)
- **Auto-inicio**: Configurable con switch on/off
- **Auto-refresh**: Intervalos personalizados desde 1 minuto hasta 1 semana

## 🕐 Intervalos de Auto-actualización

### ⏰ Configuración Flexible
- **Horas**: 0-168 (hasta 1 semana)
- **Minutos**: 0-59
- **Mínimo total**: 1 minuto
- **Máximo total**: 168 horas (1 semana)

### 🎯 Botones de Intervalos Sugeridos
| Botón | Tiempo | Uso Recomendado |
|-------|--------|-----------------|
| 30 min | 30 minutos | Pruebas y desarrollo |
| 1 hora | 1 hora | Uso frecuente |
| 6 horas | 6 horas | Uso regular |
| 24 horas | 24 horas | Uso estándar |

### 💡 Ejemplos de Configuración
- **Desarrollo**: 30 minutos (para pruebas)
- **Trabajo diario**: 2 horas
- **Uso personal**: 6-12 horas  
- **Fin de semana**: 24-48 horas
- **Vacaciones**: 1 semana (168 horas)

## � Cómo usar

### 🎯 Uso Básico (Auto-inicio)

1. **Abre la aplicación**: Simplemente abre `index.html` en tu navegador
2. **¡Relájate!**: La aplicación iniciará automáticamente en 5 segundos
3. **Observa**: Verás un countdown: "⏳ Auto-inicio en X segundos..."
4. **Automático**: Se ejecutarán 25 búsquedas con 6 segundos de intervalo
5. **Controla**: Usa los botones para pausar, reanudar o detener

### ⚙️ Uso Personalizado

1. **Configura antes del auto-inicio**: Cambia las repeticiones y tiempo antes de los 5 segundos
2. **Uso manual**: Haz clic en "Iniciar Búsqueda" para usar tus configuraciones
3. **Control total**: Pausa, reanuda o detén el proceso cuando quieras

### 🚨 Importante

- **Permitir ventanas emergentes**: Tu navegador debe permitir pop-ups
- **Límite de pestañas**: Algunos navegadores limitan pestañas automáticas
- **Internet estable**: Necesitas conexión para las búsquedas en Bing

## 🌐 Desplegar en GitHub Pages

### Opción 1: Subir a un repositorio existente

1. Sube el archivo `index.html` a la carpeta raíz de tu repositorio
2. Ve a Settings > Pages en tu repositorio
3. Selecciona la rama desde donde quieres servir (generalmente `main` o `master`)
4. Guarda los cambios
5. Tu aplicación estará disponible en `https://tuusuario.github.io/tunombrerepo/`

### Opción 2: Crear un nuevo repositorio

1. Crea un nuevo repositorio en GitHub
2. Sube el archivo `index.html`
3. Activa GitHub Pages desde Settings > Pages
4. Tu aplicación estará disponible en `https://tuusuario.github.io/nombre-repositorio/`

### Opción 3: Repositorio con nombre especial

1. Crea un repositorio con el nombre `tuusuario.github.io`
2. Sube el archivo `index.html`
3. La aplicación estará disponible directamente en `https://tuusuario.github.io/`

## 🆕 Nuevas Características (Versión 3.0)

### 🚀 Auto-inicio Configurable
- ⏰ **Control total**: Activar/desactivar inicio automático con switch
- ⏳ **Countdown inteligente**: Solo muestra countdown si está habilitado
- 🎯 **Configuración persistente**: Recuerda tu preferencia
- 📱 **Experiencia personalizable**: Tú decides si quieres auto-inicio o control manual

### ⏰ Auto-refresh Ultra Personalizable
- 🕐 **Intervalos precisos**: Configuración en horas Y minutos
- 🎯 **Botones rápidos**: 30min, 1h, 6h, 24h con un clic
- 📊 **Rango flexible**: Desde 1 minuto hasta 168 horas (1 semana)
- 🔄 **Actualización inteligente**: Recalcula automáticamente al cambiar
- ⚠️ **Validación automática**: Previene configuraciones inválidas

### � Persistencia Total
- 📋 **Auto-guardado**: Todas las configuraciones se guardan automáticamente
- 🔄 **Restauración**: Al recargar, mantiene todos tus ajustes
- 📅 **Historial**: Muestra cuándo fue la última configuración
- 🎛️ **Estado completo**: Switches, valores y timestamps persistentes

### 🔧 Mejoras de Interfaz
- 🎨 **Sección de configuraciones avanzadas**: Panel dedicado para ajustes
- � **Layout responsivo**: Botones sugeridos organizados elegantemente
- 💬 **Mensajes mejorados**: Feedback claro en tiempo real
- ⚡ **Validación en vivo**: Correcciones automáticas de valores

## ⚙️ Diferencias con la versión Flask

### Lo que se mantiene igual

- Interfaz de usuario idéntica
- Misma lógica de generación de frases
- Controles de pausa/stop/progreso
- Log de actividad con colores e iconos
- Apertura automática de pestañas

### Lo que cambió

- **No requiere servidor**: Todo funciona en el navegador
- **Auto-inicio**: Nueva funcionalidad de inicio automático
- **Base de datos local**: Las palabras están embebidas en el JavaScript
- **Sesiones en memoria**: Se usan objetos JavaScript en lugar de sesiones del servidor
- **Sin Flask**: Pure HTML/CSS/JavaScript
- **Configuración optimizada**: Valores por defecto más eficientes

## 🔧 Personalización

### Añadir más palabras
Edita el array `palabrasBase` en la función `obtenerPalabras()` para añadir más términos de búsqueda.

### Cambiar plantillas de frases
Modifica el array `plantillas` en la función `generarFraseAleatoria()` para personalizar los patrones de frases.

### Ajustar estilos
Modifica las variables CSS en `:root` para cambiar los colores y temas.

## 📱 Compatibilidad

- ✅ Chrome (recomendado)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ Internet Explorer no soportado

## ⚠️ Notas importantes

1. **Bloqueadores de ventanas emergentes**: Asegúrate de permitir ventanas emergentes para que la apertura automática de pestañas funcione
2. **Límites del navegador**: Algunos navegadores pueden limitar el número de pestañas que se pueden abrir automáticamente
3. **Sin persistencia**: Los datos de sesión se pierden al recargar la página (esto es normal en una aplicación frontend)

## 🎨 Créditos y Información

### 👨‍💻 Desarrollo
- **Desarrollador Principal**: [Flaviofonck](https://github.com/flaviofonck)
- **Versión**: 2.0 - GitHub Pages Edition
- **Fecha**: Octubre 2024
- **Licencia**: MIT - Uso libre

### 🎨 Tecnologías Utilizadas
- **Frontend**: HTML5, CSS3, JavaScript ES6+
- **Framework CSS**: [Bootstrap 5.1.3](https://getbootstrap.com/)
- **Iconos**: [Font Awesome 6.4.0](https://fontawesome.com/)
- **Hosting**: Compatible con GitHub Pages
- **Diseño**: Interfaz moderna con gradientes y efectos visuales

### 📈 Estadísticas del Proyecto
- 📁 **Archivos**: 2 (index.html + README.md)
- 📝 **Líneas de código**: ~1100+ líneas (creciendo)
- 🔤 **Palabras base**: 100+ términos
- 📋 **Plantillas de frases**: 20+ patrones
- 🌐 **Compatibilidad**: Todos los navegadores modernos
- ⚙️ **Configuraciones**: 6 ajustes personalizables
- 🎯 **Intervalos sugeridos**: 4 botones rápidos
- ⏰ **Rango de auto-refresh**: 1 minuto - 1 semana

## 🤝 Contribuciones

¿Quieres mejorar el proyecto? ¡Las contribuciones son bienvenidas!

1. 🍴 Fork el repositorio
2. 🌿 Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push a la rama (`git push origin feature/AmazingFeature`)
5. 🔄 Abre un Pull Request

### 💡 Ideas para contribuir
- 🎯 Nuevas plantillas de frases
- 🌍 Soporte multiidioma
- 🎨 Temas de color adicionales
- 📱 Mejoras de responsive
- ⚡ Optimizaciones de rendimiento

---

**¡Disfruta generando búsquedas automáticas sin complicaciones de servidor!** 🚀

> **Tip**: ⭐ ¡No olvides darle una estrella al repositorio si te resultó útil!