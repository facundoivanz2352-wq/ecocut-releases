# ecocut-releases

Versiones publicadas de Ecocut y los binarios que la app baja la primera vez que los necesita.

- **Actualizaciones de la app**: cada versión trae el instalador firmado y `latest.json`, que la app consulta para actualizarse sola.
- **whisper.cpp con Vulkan** (`whisper-vulkan-*`): el motor de transcripción para placas que no son NVIDIA (AMD, Intel). Se compila acá desde [ggml-org/whisper.cpp](https://github.com/ggml-org/whisper.cpp) (licencia MIT) con `.github/workflows/whisper-vulkan.yml`, porque whisper.cpp no publica esa variante para Windows.

El código de Ecocut no está en este repo.
