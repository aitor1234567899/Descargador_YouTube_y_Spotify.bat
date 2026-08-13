# 🎵 Descargador Multimedia (YouTube y Spotify)

Este es un script en Batch (`.bat`) para Windows que unifica la descarga de audio y video desde **YouTube** y **Spotify** en una sola interfaz de consola sencilla.

---

## 🚀 Características

* **Menú de entrada directo:** Elige entre descargar de YouTube o Spotify al iniciar.
* **YouTube Downloader (`yt-dlp`):**
  * Descarga de videos en máxima calidad (MP4).
  * Descarga de audio en MP3.
  * Extracción automática de carátulas y metadatos.
* **Spotify Downloader (`spotDL`):**
  * Descarga canciones, álbumes, playlists o artistas completos.
  * Asignación automática de portada y etiquetas ID3.
  * Carpeta por defecto en el Escritorio.
* **Gestión de dependencias:** Actualiza o comprueba herramientas necesarias automáticamente al iniciar cada opción.

---

## 📋 Requisitos Previos

Para que el script funcione correctamente necesitas tener instalado en tu sistema:

1. **Windows 10 / 11**
2. **Python 3.x** (asegúrate de marcar la opción *"Add Python to PATH"* durante la instalación).
3. **FFmpeg** (el script intentará instalarlo mediante `winget` si no lo detecta).

---

## 🛠️ Instalación y Uso

1. **Descargar el archivo:**
   Guarda el código como `Descargador_YouTube_y_Spotify.bat`.

2. **Ejecutar:**
   Haz doble clic sobre el archivo `.bat` para abrir la consola.

3. **Navegar por el menú:**
   * Pulsa **`1`** para abrir las herramientas de **YouTube**.
   * Pulsa **`2`** para abrir las herramientas de **Spotify**.
   * Sigue las instrucciones en pantalla (pegar enlace y definir carpeta de destino).

---

## ❓ Solución de Problemas

* **Errores al descargar o la descarga no avanza:**
  * Si la descarga falla, no inicia o da errores de conexión/bloqueo de IP, **utiliza una VPN**.
  * Al cambiar tu ubicación geográfica a través de una VPN, evitarás los bloqueos regionales o restricciones temporales que algunas plataformas imponen a tu conexión.
* **FFmpeg o Python no detectado:**
  * Reinicia la consola de comandos o la ventana del terminal para que Windows reconozca las variables de entorno recién instaladas.

---

## ⚙️ Herramientas Utilizadas

* [yt-dlp](https://github.com/yt-dlp/yt-dlp)
* [spotDL](https://github.com/spotDL/spotify-downloader)
* [FFmpeg](https://ffmpeg.org/)
