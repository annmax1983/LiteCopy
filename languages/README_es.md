# LiteCopy

[English](../README.md) | [中文](README_zh.md) | Español | [Deutsch](README_de.md) | [日本語](README_ja.md) | [Français](README_fr.md)

Una extensión ligera para el navegador que restaura la selección de texto nativa, el menú de clic derecho y los atajos de copiar en cualquier sitio web.

> Basada en Chromium · Manifest V3 · Permisos mínimos · Niveles gratuito y Premium

---

## ¿Por qué LiteCopy?

¿Alguna vez has intentado copiar texto de un sitio web pero no podías seleccionarlo, el clic derecho estaba bloqueado o Ctrl+C no hacía nada? LiteCopy soluciona todo esto con un solo clic.

| Ventaja | Detalle |
|---------|--------|
| 🔓 **Activar con un clic** | Restaura la selección de texto nativa al instante — sin necesidad de recargar la página |
| 🔒 **Permisos mínimos** | `activeTab` + `scripting` + `storage` — nada más allá de lo que la funcionalidad necesita |
| ⚡ **Ligera** | Sin frameworks, sin dependencias en tiempo de ejecución |
| 🌍 **6 idiomas** | Inglés, chino, español, alemán, japonés y francés |
| 🚫 **Sin rastreo** | Sin analíticas, sin telemetría. El nivel gratuito no envía ningún dato; la activación Premium verifica solo un ID de dispositivo + tu clave contra api.annmax1983.com |
| 🎯 **Interruptor simple** | Abre el popup y pulsa Activar/Desactivar — indicador claro de estado ON/OFF |

---

## Funcionalidades

### 🆓 Gratis (100 copias/día)

| Funcionalidad | Descripción |
|---------|-------------|
| 🔓 **Restaurar selección de texto** | Restaura la selección de texto por defecto en sitios que la desactivan |
| 🖱️ **Restaurar menú de clic derecho** | Recupera el menú de clic derecho del navegador en sitios restringidos |
| ⌨️ **Restaurar atajos de teclado** | Recupera Ctrl+C, Ctrl+V, Ctrl+A y otros atajos estándar |
| 🛡️ **Corregir interferencia de superposiciones** | Corrige los divs de superposición transparente que interfieren con la selección de texto |
| 🔄 **Interruptor ON/OFF** | Activa/Desactiva desde el popup, la página se recarga al desactivar |
| 💬 **Notificación emergente** | Notificación auto-descartable que muestra el estado de activación |
| 📋 **Copiar información de la página** | Botones en el popup para copiar el título de la página, la URL o ambos |

> **Límite del nivel gratuito:** 100 copias por día. La activación siempre es gratuita — cada copia que hagas en una página activada cuenta para el límite diario. El contador se reinicia a medianoche (hora local). Los botones de Copiar información de la página (título/URL) son siempre gratuitos y no cuentan.

### ⭐ Premium (Requiere licencia — Ilimitado)

| Funcionalidad | Descripción |
|---------|-------------|
| ♾️ **Copias ilimitadas** | Sin límite diario — copia todo lo que quieras |
| 📤 **Exportar/Importar configuración** | Haz una copia de seguridad y restaura tus preferencias (próximamente) |

> 💡 Compra única o suscripción mensual. [Obtener licencia →](https://www.annmax1983.com/checkout.html?plugin=litecopy)

---

## Precios

| Plan | Precio | Detalles |
|------|-------|---------|
| Gratis | $0 | 100 copias/día, todas las funcionalidades principales |
| Herramienta individual mensual | $2.99/mes | Copias ilimitadas para LiteCopy |
| Herramienta individual de por vida | $9.99 | Pago único, acceso permanente |
| Suite completa mensual | $3.99/mes | Todas las extensiones VKT, ilimitado |
| Suite completa de por vida | $19.99 | Todas las extensiones VKT, permanente |

Consulta [VKT Pricing](https://www.annmax1983.com/pricing.html) para más detalles.

---

## Vista previa

<p align="center">
  <img src="icons/icon128.png" alt="Icono de LiteCopy" width="80">
</p>

---

## Navegadores compatibles

| Navegador | Estado |
|---------|--------|
| Google Chrome | ✅ Totalmente compatible |
| Microsoft Edge | ✅ Totalmente compatible |
| Otros navegadores basados en Chromium | ✅ Debería funcionar |

---

## Instalación

1. Abre la página de extensiones de tu navegador:
   - **Chrome**: `chrome://extensions/`
   - **Edge**: `edge://extensions/`
2. Activa el **modo de desarrollador** (interruptor arriba a la derecha)
3. Haz clic en **Cargar descomprimida** y selecciona la carpeta `lite-copy`
4. El icono de LiteCopy aparecerá en tu barra de herramientas

---

## Uso

1. Visita cualquier sitio web que bloquee la copia o la selección de texto
2. Haz clic en el icono de **LiteCopy** en tu barra de herramientas — se abre el popup
3. Haz clic en **Activar** — la selección de texto se restaura al instante
4. Para desactivar, abre el popup de nuevo y haz clic en **Desactivar** (la página se recarga para restaurar el comportamiento original)

> **Nota:** Algunas páginas restringidas por el navegador (`chrome://`, Chrome Web Store, etc.) no pueden modificarse. El popup muestra un error.

**Copiar información de la página:**
- Haz clic en el icono → se abre el popup
- Usa los botones para copiar el título de la página, la URL o ambos

**Consultar uso:**
- La barra de uso en la parte superior muestra tu conteo de copias diarias
- Usuarios gratuitos: 100 copias/día, se reinicia a medianoche
- Usuarios Premium: ⭐ Ilimitado

---

## Privacidad

- ✅ **Sin analíticas** — Sin rastreo, sin telemetría
- ✅ **Nivel gratuito: cero solicitudes de red** — Todo el procesamiento ocurre localmente; no se envía nada a menos que actives Premium
- ✅ **Permisos mínimos** — `activeTab` + `scripting` + `storage`, más el host de la API de licencias
- ✅ **Sin memoria de sitios** — Sin lista negra/blanca, sin preferencias de sitio almacenadas
- ✅ **Solo verificación de licencia** — Si activas una licencia Premium, un ID de dispositivo mínimo y tu clave de licencia se envían a `api.annmax1983.com` para verificación. No se envían datos si no activas una licencia.

---

## Aviso de derechos de autor

Esta herramienta solo restaura las capacidades básicas de operación de texto integradas en el navegador para el aprendizaje personal, la referencia y la lectura sin conexión del usuario. Todo el texto, las imágenes y los derechos de autor del contenido del sitio web pertenecen al autor original y al operador del sitio. Los usuarios no deberían utilizar esta herramienta para reproducción comercial, extracción masiva, reimpresión de contenido u otros comportamientos que infrinjan los derechos de autor. Toda responsabilidad legal derivada del uso indebido recaerá exclusivamente sobre el usuario.

---

## Aviso sobre el código fuente

> ⚠️ **Este repositorio no publica código fuente.** Contiene únicamente documentación de uso, notas de lanzamiento y recursos de soporte. La extensión se distribuye exclusivamente a través de Chrome Web Store. No se proporcionan paquetes de instalación sin conexión ni código fuente para usuarios finales.

---

## Licencia

Copyright © 2026 LiteCopy. Todos los derechos reservados.

---

## ❤️ Apoyo

Si te resulta útil LiteCopy, ¡considera apoyar el proyecto!

**[👉 Haz clic aquí para apoyar](https://ko-fi.com/annmax?ref=litecopy)**
