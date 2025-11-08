# Spotify Web API

Spotify ofrece una API pública que permite a los desarrolladores acceder a datos sobre canciones, artistas, playlists y usuarios (con autorización).

## Endpoints principales

- GET /v1/me → información del usuario autenticado.
- GET /v1/playlists/{playlist_id} → detalles de una lista de reproducción.
- GET /v1/tracks/{id} → datos de una canción.
## Autenticación

Usa OAuth 2.0, requiriendo un access_token para acceder a datos privados o de usuario.

## Casos de uso

- Crear apps que muestren tu música más escuchada.
- Integrar Spotify con asistentes de voz o sistemas IoT.
