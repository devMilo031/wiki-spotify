# Sistema de reproducción de Spotify

El motor de reproducción de Spotify combina buffering, caché local y comunicación con servidores para ofrecer música sin interrupciones.

## Funcionamiento

1. El cliente solicita la canción al servidor.
1. Spotify descarga en fragmentos (chunks) el audio en formato Ogg Vorbis.
1. Los fragmentos se reproducen en streaming mientras se descargan.
## Control

- Los clientes envían comandos de play/pause/next a través del Spotify Connect Protocol.
- Se puede reproducir música en diferentes dispositivos sincronizados con la misma cuenta.
## Optimización

- Spotify ajusta el bitrate automáticamente según la red.
- Usa caché local para evitar retransmisiones innecesarias.
