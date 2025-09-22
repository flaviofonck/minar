# Generador Automático de Búsquedas - Versión GitHub Pages

Esta es la versión estática de la aplicación Flask que funciona completamente en el navegador sin necesidad de un servidor backend.

## 🚀 Características

- **100% Frontend**: Funciona sin servidor backend
- **GitHub Pages Compatible**: Perfecto para hosting gratuito
- **Misma funcionalidad**: Replica toda la funcionalidad de la versión Flask
- **Responsive**: Funciona en dispositivos móviles y escritorio
- **Sin dependencias externas críticas**: Solo usa CDNs públicos para Bootstrap y FontAwesome

## 📋 Funcionalidades

- ✅ Generación automática de frases de búsqueda
- ✅ Control de repeticiones y tiempo de espera
- ✅ Botones de pausa/reanudar y detener
- ✅ Barra de progreso en tiempo real
- ✅ Log de actividad con iconos y colores
- ✅ Apertura automática de pestañas de búsqueda en Bing
- ✅ Interfaz moderna y atractiva
- ✅ Base de datos local de palabras (no depende de APIs externas)

## 🛠️ Cómo usar

1. Abre el archivo `index.html` en cualquier navegador web moderno
2. Configura el número de repeticiones y tiempo de espera
3. Haz clic en "Iniciar Búsqueda"
4. La aplicación abrirá automáticamente pestañas con búsquedas generadas aleatoriamente
5. Usa los controles para pausar, reanudar o detener el proceso

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

## ⚙️ Diferencias con la versión Flask

### Lo que se mantiene igual:
- Interfaz de usuario idéntica
- Misma lógica de generación de frases
- Controles de pausa/stop/progreso
- Log de actividad con colores e iconos
- Apertura automática de pestañas

### Lo que cambió:
- **No requiere servidor**: Todo funciona en el navegador
- **Base de datos local**: Las palabras están embebidas en el JavaScript
- **Sesiones en memoria**: Se usan objetos JavaScript en lugar de sesiones del servidor
- **Sin Flask**: Pure HTML/CSS/JavaScript

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

## 🎨 Créditos

- **Desarrollador**: Flaviofonck
- **Diseño**: Interfaz moderna con gradientes y efectos visuales
- **Framework CSS**: Bootstrap 5.1.3
- **Iconos**: Font Awesome 6.4.0

## 📄 Licencia

Este proyecto es de uso libre. Puedes modificarlo y distribuirlo como desees.

---

**¡Disfruta generando búsquedas automáticas sin complicaciones de servidor!** 🚀