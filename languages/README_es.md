# LiteCopy

[English](../README.md) | [中文](README_zh.md) | Español | [Deutsch](README_de.md) | [日本語](README_ja.md) | [Français](README_fr.md)

Una extensión ligera para el navegador que restaura la selección de texto nativa, el menú de clic derecho y los atajos de copiar en cualquier sitio web.

> Chrome / Edge / Firefox · Manifest V3 · Copias gratuitas ilimitadas · Reglas de sitios entre dispositivos en Premium

---

## ¿Por qué LiteCopy?

¿Alguna vez has intentado copiar texto de un sitio web pero no podías seleccionarlo, el clic derecho estaba bloqueado o Ctrl+C no hacía nada? LiteCopy soluciona todo esto con un solo clic.

| Ventaja | Detalle |
|---------|--------|
| 🔓 **Activar con un clic** | Restaura la selección de texto nativa al instante — sin necesidad de recargar la página |
| ♾️ **Gratis e ilimitado** | Copia, selecciona y usa el clic derecho todo lo que quieras — sin límite diario ni contador |
| 🔄 **Reglas de sitios entre dispositivos** | Premium sincroniza los sitios que activas mediante la cuenta integrada del navegador (Chrome Sync / Edge Sync) |
| 🔒 **Local por diseño** | El desbloqueo se ejecuta localmente con `activeTab` + `scripting`; el acceso a sitios solo se usa en las páginas que activas |
| ⚡ **Ligera** | Sin frameworks, sin dependencias en tiempo de ejecución |
| 🌍 **6 idiomas** | Inglés, chino, español, alemán, japonés y francés |
| 🚫 **Sin rastreo** | Sin analíticas ni telemetría. El desarrollador no tiene un servidor que guarde tu historial ni tu lista de sitios |
| 🎯 **Interruptor simple** | Abre el popup y pulsa Activar/Desactivar — indicador claro de estado ON/OFF |

---

## Funcionalidades

### 🆓 Gratis — ilimitado

| Funcionalidad | Descripción |
|---------|-------------|
| 🔓 **Restaurar selección de texto** | Restaura la selección de texto por defecto en sitios que la desactivan |
| 🖱️ **Restaurar menú de clic derecho** | Recupera el menú de clic derecho del navegador en sitios restringidos |
| ⌨️ **Restaurar atajos de teclado** | Recupera Ctrl+C, Ctrl+V, Ctrl+A y otros atajos estándar |
| 🛡️ **Corregir interferencia de superposiciones** | Corrige los divs de superposición transparente que interfieren con la selección de texto |
| 🔄 **Interruptor ON/OFF** | Activa/Desactiva desde el popup, la página se recarga al desactivar |
| 🧠 **Sitios recordados** | Los sitios que actives se recuerdan localmente y se activan solos en la próxima visita |
| 💬 **Notificación emergente** | Notificación auto-descartable que muestra el estado de activación |
| 📋 **Copiar información de la página** | Botones en el popup para copiar el título de la página, la URL o ambos |

> Todas las funciones anteriores son gratuitas, sin límite de copias ni reinicio diario.

### ⭐ Premium — reglas de sitios entre dispositivos

| Funcionalidad | Descripción |
|---------|-------------|
| 🔄 **Reglas de sitios entre dispositivos** | Activa un sitio una vez y la regla sigue tu cuenta del navegador, por lo que se activa sola en tus otros dispositivos con la misma cuenta |
| 🔐 **Sincronización con la cuenta del navegador** | La lista la guarda tu navegador en `storage.sync`. Sin cuenta de LiteCopy, sin copia en un servidor del desarrollador y sin acceso para el desarrollador |
| 💻 **Acceso por dispositivo** | Los permisos de sitio del navegador no se sincronizan. En un dispositivo nuevo, pulsa Activar una vez en el sitio sincronizado para conceder acceso; la regla ya está guardada |
| 🧭 **Sincronización manual** | El botón **Sincronizar ahora** de Configuración descarga la lista más reciente de tu cuenta del navegador cuando quieras |

> 💡 Compra única o suscripción mensual. [Obtener licencia →](https://www.annmax1983.com/checkout.html?plugin=litecopy)

---

## Vista previa

<p align="center">
  <img src="../assets/favicon.png" alt="Icono de LiteCopy" width="80">
</p>

---

## Navegadores compatibles

| Navegador | Estado |
|---------|--------|
| Google Chrome | ✅ Totalmente compatible |
| Microsoft Edge | ✅ Totalmente compatible |
| Mozilla Firefox | ✅ Totalmente compatible |
| Otros navegadores basados en Chromium | ✅ Debería funcionar |

> **Nota sobre Firefox:** Las páginas protegidas son las páginas `about:` y addons.mozilla.org. La sincronización entre dispositivos usa Firefox Sync (cuenta de Mozilla). El resto de funciones se comporta igual que en Chrome / Edge.

---

## Instalación

| Tienda | Enlace |
|---|---|
| Chrome Web Store | [Instalar en Chrome](https://chromewebstore.google.com/detail/opckcochfnlfcdoblnmgeebeeggfnilg) |
| Complementos de Microsoft Edge | [Instalar en Edge](https://microsoftedge.microsoft.com/addons/detail/acpfcfipfalphidhmpflecncacgldggl) |
| Complementos de Firefox (AMO) | 🔜 En revisión: el enlace se añadirá al publicarse |

> Instale solo desde las tiendas oficiales de arriba; evite sitios de descarga de terceros.

---

## Uso

1. Visita cualquier sitio web que bloquee la copia o la selección de texto
2. Haz clic en el icono de **LiteCopy** en tu barra de herramientas — se abre el popup
3. Haz clic en **Activar** — la selección de texto se restaura al instante
4. Para desactivar, abre el popup de nuevo y haz clic en **Desactivar** (la página se recarga para restaurar el comportamiento original)

> **Nota:** Algunas páginas restringidas por el navegador (`chrome://`, Chrome Web Store, Microsoft Edge Add-ons y Firefox Add-ons (AMO), etc.) no pueden modificarse. El popup muestra un error.

**Reglas de sitios y sincronización (Premium):**
- Activa un sitio en un dispositivo — la regla se añade al almacenamiento sincronizado de tu cuenta del navegador
- En otro dispositivo con la misma cuenta del navegador, el sitio aparece como regla guardada; pulsa **Activar** una vez para conceder el permiso de sitio de ese dispositivo
- Abre **Configuración** para ver cuántos sitios están sincronizados y usa **Sincronizar ahora** si quieres actualizar de inmediato

**Copiar información de la página:**
- Haz clic en el icono → se abre el popup
- Usa los botones para copiar el título de la página, la URL o ambos

---

## Privacidad

- ✅ **Sin analíticas** — Sin rastreo, sin telemetría
- ✅ **Funciones gratuitas: cero solicitudes de red** — Todo el procesamiento ocurre localmente; no se envía nada a menos que actives Premium
- ✅ **Permisos concretos** — `activeTab` + `scripting` + `storage` ejecutan el desbloqueo, más el acceso a sitios usado únicamente para inyectarlo en las páginas que actives, y el host de la API de licencias
- ✅ **La lista de sitios es local por defecto** — Activar LiteCopy guarda ese dominio en `storage.local`. La lista nunca se envía al desarrollador
- ✅ **La sincronización Premium usa tu cuenta del navegador** — Con una licencia activa, la lista también se refleja en `storage.sync`, la sincronización de cuenta de tu proveedor de navegador. El desarrollador no tiene acceso ni recibe copia. La sincronización se detiene si eliminas la licencia; las reglas locales siguen funcionando
- ✅ **Solo verificación de licencia** — Al activar una licencia Premium se envían un ID de instalación mínimo y tu clave a `api.annmax1983.com` para verificarlos. No se envían datos si no activas una licencia

---

## Aviso de derechos de autor

Esta herramienta solo restaura las capacidades básicas de operación de texto integradas en el navegador para el aprendizaje personal, la referencia y la lectura sin conexión del usuario. Todo el texto, las imágenes y los derechos de autor del contenido del sitio web pertenecen al autor original y al operador del sitio. Los usuarios no deberían utilizar esta herramienta para reproducción comercial, extracción masiva, reimpresión de contenido u otros comportamientos que infrinjan los derechos de autor. Toda responsabilidad legal derivada del uso indebido recaerá exclusivamente sobre el usuario.

---

## Aviso sobre el código fuente

> ⚠️ **Este repositorio no publica código fuente.** Contiene únicamente documentación de uso y recursos de soporte. La extensión se distribuye exclusivamente a través de Chrome Web Store, Microsoft Edge Add-ons y Firefox Add-ons (AMO). No se proporcionan paquetes de instalación sin conexión ni código fuente para usuarios finales.

---

## Política de Privacidad

Consulta la [Política de Privacidad](../privacy-policy.html) completa — las funciones gratuitas funcionan totalmente sin conexión, con cero solicitudes de red.

---

## Licencia

Copyright © 2026 LiteCopy. Todos los derechos reservados.

---

## ❤️ Apoyo

Si te resulta útil LiteCopy, ¡considera apoyar el proyecto!

**[👉 Haz clic aquí para apoyar](https://ko-fi.com/annmax?ref=litecopy)**
