# Cortador de Clips

Herramienta web para cortar un video largo en clips de 10 s, 15 s, 20 s, 30 s, 40 s, 1 min, 2 min o 5 min (o el largo que quieras) y descargar solo los clips elegidos.

- El video no se sube a ningún servidor: se procesa en el navegador con [ffmpeg.wasm](https://github.com/ffmpegwasm/ffmpeg.wasm).
- Modo **Rápido**: corta sin recodificar (segundos por clip, sin pérdida de calidad; el inicio se ajusta al fotograma clave más cercano).
- Modo **Preciso**: recodifica para cortar al segundo exacto (más lento).
- Funciona mejor en Chrome o Edge de escritorio. La primera vez descarga el motor de corte (~30 MB).

Es un solo archivo (`index.html`), sin build ni dependencias que instalar.
