# Autenticación en Spotify

Spotify utiliza OAuth 2.0 para autorizar el acceso a la API.

## Flujo de autorización

1. El usuario inicia sesión con su cuenta de Spotify.
1. La aplicación recibe un authorization_code.
1. El backend intercambia ese código por un access_token.
1. El token permite realizar peticiones en nombre del usuario.
## Tipos de permisos (scopes)

- user-read-private
- playlist-read-private
- user-top-read
Estos determinan el nivel de acceso que la app tendrá.

