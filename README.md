# ComfyUI en Google Colab

[![Abrir en Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/I-s-ax/Comfyui_en_colab/blob/main/comfyui_colab_drive.ipynb)

Abre el notebook directamente en Google Colab desde el botón de arriba.

## Qué incluye

- Conexión opcional con Google Drive para conservar ComfyUI y los modelos.
- Instalación o actualización de ComfyUI.
- Formulario para descargar checkpoints, LoRA, VAE y otros archivos de modelos.
- Opción para usar un token de Civitai guardado en **Colab Secrets** como `CIVITAI_API_TOKEN`.
- Listado de modelos descargados.
- Inicio de ComfyUI con enlace temporal: prueba primero LocalTunnel (incluye la contraseña si la página la pide) y usa Cloudflare como alternativa.
- Reutilización de una instancia de ComfyUI ya iniciada para evitar el error de puerto 8188 ocupado.

## Cómo empezar

1. Pulsa **Abrir en Google Colab**.
2. En Colab, abre **Entorno de ejecución → Cambiar tipo de entorno** y selecciona una GPU disponible, por ejemplo T4.
3. Ejecuta las celdas en orden, desde arriba hacia abajo.
4. En la última celda, espera el enlace `https://....loca.lt` y ábrelo. Si LocalTunnel solicita una contraseña, copia la que imprime la celda. Mantén la celda ejecutándose mientras uses ComfyUI. Si LocalTunnel no logra crear el enlace, la celda intentará Cloudflare automáticamente.

## Notas importantes

- La disponibilidad de GPU depende de tu cuenta y de los recursos de Colab; no se garantiza una GPU en todas las sesiones.
- Los modelos grandes consumen mucho almacenamiento y tiempo de descarga.
- Para generar vídeo a partir de imágenes también necesitarás modelos y un workflow de vídeo compatibles con ComfyUI.
- Los enlaces temporales de LocalTunnel y Cloudflare son públicos para quien los conozca. No los compartas si no quieres que otras personas accedan a la sesión. La contraseña de LocalTunnel ayuda a proteger la página intermedia, pero no debe tratarse como una autenticación fuerte.
- Revisa las licencias y condiciones de uso de cada modelo antes de descargarlo o generar contenido.

