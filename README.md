# ⚽ Futsal Pro Manager

**Futsal Pro Manager** es una herramienta digital profesional para entrenadores de fútbol sala. Permite gestionar plantillas, generar convocatorias automáticas para WhatsApp y calcular rotaciones equitativas de minutos para asegurar que todos los jugadores participen por igual (Fair Play).

## 🚀 Características Principales

* **Gestión de Plantillas:** Crea múltiples equipos y gestiona los datos de tus jugadores (dorsal, posición principal y secundaria).
* **Convocatorias Inteligentes:** Genera mensajes de WhatsApp profesionales con un solo clic, incluyendo fecha, hora, rival y ubicación mediante Google Maps.
* **Algoritmo Fair Play:** Genera un PDF con una tabla de cambios automática. El sistema calcula los minutos basándose en la duración del partido y asegura que nadie juegue más que otros, respetando posiciones tácticas.
* **Reglas de Exclusión:** Permite configurar que ciertos jugadores no coincidan nunca en el campo para evitar conflictos tácticos.
* **PWA (App Instalable):** Funciona como una aplicación nativa en tu móvil (Android e iOS). Puedes instalarla en tu pantalla de inicio para acceder sin usar el navegador.
* **Privacidad Total:** Los datos se guardan localmente en tu dispositivo (`localStorage`), sin necesidad de bases de datos externas ni registros.

## 🛠️ Tecnologías Utilizadas

* **Frontend:** HTML5, CSS3 (Bootstrap 5) e Inter Fonts.
* **Lógica:** JavaScript (Vanilla JS).
* **Generación de PDF:** [jsPDF](https://github.com/parallax/jsPDF) y [jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable).
* **PWA:** Service Workers y Manifest JSON.

## 📱 Instalación

Para instalar la aplicación en tu dispositivo móvil:

1.  **Android:** Abre el enlace en Chrome. Aparecerá un botón de "INSTALAR APP" en la parte superior o una barra inferior invitándote a añadirla a la pantalla de inicio.
2.  **iOS (iPhone/iPad):** Abre el enlace en Safari. Pulsa el botón "Compartir" (cuadrado con flecha) y selecciona "Añadir a la pantalla de inicio".

## 💻 Desarrollo Local

Si deseas realizar modificaciones:

1.  Clona este repositorio o descarga los archivos.
2.  Asegúrate de que los archivos `index.html`, `manifest.json`, `sw.js` y `logo.png` estén en la misma carpeta.
3.  Para las funciones de PWA, se requiere un servidor con HTTPS (puedes usar Netlify o GitHub Pages para despliegue gratuito).

---
*Desarrollado para entrenadores que aman el 40x20.*
