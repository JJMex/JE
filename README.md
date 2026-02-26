# 👁️ Expediente Epstein | Global Intelligence Node

> **STATUS:** UNREGISTERED NODE ACTIVO  
> **NIVEL DE ACCESO:** CLASIFICADO / PÚBLICO  
> **VERSIÓN:** 1.0.0 (Top-Tier HUD Interface)

## 📌 Descripción del Proyecto

Este repositorio contiene el código fuente de una interfaz web de inteligencia y análisis forense, diseñada para actuar como un nodo central de acceso a los documentos, correos y archivos audiovisuales desclasificados del caso Jeffrey Epstein.

La página no es un sitio web tradicional; está construida bajo una **arquitectura de inmersión táctica (HUD)**, utilizando psicología de diseño, micro-interacciones y telemetría en tiempo real para ofrecer una experiencia de "terminal de inteligencia filtrada".

## ⚙️ Capacidades del Sistema (Características Técnicas)

El código es 100% Vanilla (HTML5, CSS3, JavaScript puro) y no requiere bases de datos ni frameworks pesados. Todo se ejecuta en el lado del cliente con un rendimiento optimizado.

* **Secuencia de Arranque (Boot Sequence):** Simulación de terminal de desencriptación al cargar el nodo.
* **HUD Táctico de 4 Esquinas:** Diseño responsivo que simula una cámara de vigilancia / monitor CCTV. En móviles, se adapta a una vista de "Visor Escáner" (Buzón).
* **Telemetría en Vivo (API Integradas):**
  * Rastreo dinámico de **Dirección IP** y **Geolocalización** (Ciudad/País) del visitante.
  * Lector de **Batería** (Estado de carga y porcentaje).
  * Identificador de **Sistema Operativo** y reloj local exacto.
* **Micro-interacciones Forenses:**
  * Texto censurado dinámico que se revela mediante evento táctil/hover.
  * Interfaz de Audio Sintetizado (API Web Audio): Sonido de clic mecánico generado por código (sin archivos mp3 externos).
  * Retraso intencional de conexión (1000ms) para simular enrutamiento seguro.
* **Seguridad Psicológica:**
  * Síndrome de Pestaña Abandonada: El título cambia a `⚠️ ALERTA: RASTREO ACTIVO` si el usuario cambia de ventana.
  * "Archivo Fantasma": Mensaje de advertencia clasificado impreso directamente en la consola de desarrollador para evitar el *reverse-engineering*.
* **Generación QR Local:** Generación de códigos QR en Canvas nativo mediante `qrious.js` para evitar caídas de servidores externos.

## 🗄️ Estructura de Enlaces (Base de Datos)

El nodo redirige actualmente a los siguientes repositorios descentralizados:
1. **Registro Federal [DOJ]:** Documentos del Departamento de Justicia de EE.UU.
2. **Interfaz J-Mail:** Interfaz de búsqueda comunitaria de correos.
3. **Registros Audiovisuales:** Videoteca de cateos e interrogatorios.
4. **Directorio Raw:** Documentos originales sin filtro redaccional.
5. **Comunidad Cifrada:** Acceso a grupo privado para análisis en tiempo real.

## 🛠️ Despliegue e Instalación

No se requiere `npm`, `node` ni configuraciones de backend. 

1. Clona este repositorio:
   `git clone https://github.com/TU_USUARIO/TU_REPOSITORIO.git`
2. Abre el archivo `index.html` en cualquier navegador moderno.
3. **Para despliegue en producción:** Sube los archivos directamente a GitHub Pages, Vercel o Netlify. El sitio funcionará inmediatamente.

## 🔧 Configuración Rápida (Variables)

Para modificar las rutas de la evidencia o actualizar el enlace del grupo, no es necesario buscar entre cientos de líneas de código HTML. Ve al final del archivo `index.html`, dentro de la etiqueta `<script>`, y edita el objeto `CONFIG`:

    const CONFIG = {
        link_oficial:   "https://www.justice.gov/epstein",
        link_jmail:     "https://jmail.world",
        link_jefftube:  "https://jmail.world/jefftube",
        link_raw:       "https://tommycarstensen.com/epstein/",
        link_whatsapp:  "https://chat.whatsapp.com/TU_NUEVO_ENLACE_AQUI"
    };

*(Nota: El código QR del sitio se actualizará de forma automática basándose en la variable `link_whatsapp`)*.

## ⚠️ Descargo de Responsabilidad (Disclaimer)

Este repositorio y el sitio web resultante tienen fines puramente informativos, periodísticos y de preservación histórica. Los desarrolladores y contribuyentes de este código no alojan los archivos originales ni se hacen responsables por el contenido de terceros enlazado en el directorio. 

> *"No confíes en lo que se redacta. Busca los nombres borrados."*
