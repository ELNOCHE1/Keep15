# KeepIt15

**KeepIt15** es una aplicación web de almacenamiento de archivos estilo MediaFire/Google Drive con autenticación mediante Google y una interfaz moderna, clara y adaptable. Ofrece hasta **128 GB simulados** de espacio para subir, ver, descargar y borrar archivos, almacenados localmente en el navegador del usuario.

## 🧰 Tecnologías usadas

- HTML, CSS y JavaScript (puros)
- Firebase Authentication (con Google)
- Almacenamiento simulado vía `localStorage`
- UI con barra de progreso estilo MediaFire
- Íconos con Font Awesome
- Diseño responsivo y accesible

## 🎯 Funcionalidades

- ✅ Autenticación con Google (Firebase)
- ✅ Subida de múltiples archivos
- ✅ Vista previa con íconos para imágenes, videos, PDFs, audios y ZIP
- ✅ Barra de progreso de subida animada
- ✅ Confirmación antes de eliminar archivos
- ✅ Cálculo de espacio usado (máximo 128 GB simulados)
- ✅ Compartir enlaces (simulados)
- ✅ Interfaz tipo menú hamburguesa para dispositivos móviles
- ✅ Pantalla de carga mientras se sube un archivo

## 🧪 Cómo usar

1. Cloná o descargá este repositorio.
2. Abrí el archivo `index.html` en tu navegador.
3. Iniciá sesión con tu cuenta de Google.
4. Subí archivos desde el botón 📁 o desde el menú.
5. Administralos: descargá, compartí o eliminá los qa no querés.

> ⚠️ Importante: Los archivos se guardan en el `localStorage`, así que **no se suben a ningún servidor real** y son visibles solo desde el mismo navegador/dispositivo.

## 🧠 Personalización

- Cambiá el límite de almacenamiento modificando `MAX_STORAGE_MB` en el JavaScript.
- Se pueden cambiar los íconos base64 por íconos personalizados si se desea una apariencia más única.
- El logo y nombre se pueden personalizar fácilmente reemplazando `keepit15-logo.png`.

## 🚀 Próximas mejoras (opcional)

- Almacenamiento real con Firebase Storage o Google Drive API.
- Compartición de archivos con links reales.
- Organización de archivos en carpetas.
- Versión PWA para instalación en móviles.

## 📜 Licencia

Este proyecto es libre para uso personal y educativo.

---

Creado con 💾 por ElNoche12
