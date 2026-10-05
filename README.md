### Hola, soy Alan

Construyo sistemas que se mantienen solos. Me interesan los servidores pequeños, la
automatización que no necesita que estés mirando, y el código que alguien más pueda auditar.

### Lo que hago

- **Servidores domésticos que no gastan nada.** El proyecto del que más presumo es
  [ezarr-stack](https://github.com/MadManJohnSmith/ezarr-stack): un servidor completo de
  medios y *arr corriendo **dentro de un teléfono Android muerto**. Chroot sobre TWRP,
  sin Docker y sin systemd, 7 GB de RAM, consumo eléctrico ridículo.
- **Software de escritorio.** [Syncify](https://github.com/MadManJohnSmith/Syncify) es una
  app Tauri (Rust + Vue) para tener tu música en máxima calidad y bajo tu control:
  importar, migrar y descargar tu catálogo desde Qobuz, Tidal, Spotify, Deezer y SoundCloud.
- **Auditoría automática.** [Improvement](https://github.com/MadManJohnSmith/Improvement)
  revisa un repositorio y repara lo que encuentra, con hallazgos verificados contra tus
  propias pruebas en vez de suposiciones.

### Proyectos

| | |
|---|---|
| [ezarr-stack](https://github.com/MadManJohnSmith/ezarr-stack) | Servidor de medios y *arr en Android con chroot. Instalable en un solo comando. |
| [Syncify](https://github.com/MadManJohnSmith/Syncify) | Gestor de música FLAC en Rust + Vue + Tauri. |
| [Improvement](https://github.com/MadManJohnSmith/Improvement) | Auditoría y reparación de repositorios con agentes locales. |
| [oci-a1-capacity](https://github.com/MadManJohnSmith/oci-a1-capacity) | Instancia OCI Always Free que se recupera sola. |
| [RehabWeb](https://github.com/MadManJohnSmith/RehabWeb-WebApp) · [API](https://github.com/MadManJohnSmith/RehabWeb-Api) | Proyecto de tesis: fisioterapia en web (Django + TypeScript). |

### Cómo trabajo

Un par de reglas que se notan en el código:

- **Nada de estado oculto.** Los servicios se manejan con scripts explícitos, no con un
  supervisor que nadie puede inspeccionar cuando algo falla a las 3 de la mañana.
- **Un fallo se avisa solo.** Si el servidor está caído, me entero por el móvil, no por
  un cliente quejándose.
- **El plan de recuperación se escribe antes de necesitarlo.** Cada proyecto tiene un
  runbook con el triaje paso a paso.

### El teléfono ya no arranca Android, y aun así sirve

El Poco X3 Pro que hace de servidor murió de **muerte súbita**, un fallo conocido de ese
modelo: ya no arranca el sistema operativo. Lo que sí arranca es el recovery, y ahí vive
todo el stack. No es un experimento de laboratorio: sirve medios y gestiona descargas a diario,
con respaldos cifrados fuera del dispositivo.

La lección no es que los teléfonos sean mejores servidores. Es que **un teléfono que ya
no da boot puede seguir siendo un servidor, con el suficiente cuidado** — y que el plan
de recuperación se escribe antes de necesitarlo, no después.

### Abierto a

Trabajo en sistemas, open source y automatización. Si tienes un proyecto donde importe que
las cosas se reparen solas, escríbeme.

<!-- LastFM Scrobbles -->
[![Last.fm](https://lastfm-recently-played.vercel.app/api?user=MadManJohnSmith&count=5&width=512&loved=true&show_user=header&header_style=normal_stats&bg_color=000000)](https://www.last.fm/user/MadManJohnSmith)
<!-- Spotify Stuff -->
[![spotify-github-profile](https://spotify-github-profile.kittinanx.com/api/view?uid=12127984853&cover_image=true&theme=novatorem&show_offline=false&background_color=121212&interchange=false&bar_color=53b14f&bar_color_cover=true)](https://www.spotify-github-profile.kittinanx.com/api/view?uid=12127984853&redirect=true)
