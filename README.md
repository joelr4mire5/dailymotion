# Dailymotion

## Esquema de archivos

C:
├───archivos_procesados
└───archivos_sin_procesar
    ├───users
    └───videos
    
    
## Información sobre el contenido:

1. archivos_procesados:
  a. userid_allusers: contiene la información unificada de los 10 archivos que muestran la información del usuario.
  b. videos_processed: contiene la información unificada de los videos y usuarios.
2. archivos_sinprocesar:
  a. videos: la carpeta con tiene información sobre los videos de la plataforma.
  b. users: contiene información sobre los usuarios a quienes pertenecen los videos.
  
  ## Índice:
  
  page: número de página de los resultados que la API proporciona.
  limit: el límite de resultados que se muestran por página.
  total: número de resultados a los que hay acceso.
  has_more: TRUE ---> indica que sí hay más resultados por mostrar. FALSE ---> indica que no hay más resultados por mostrar.
  list_id: identificador único de la lista de reproducción.
  list_title: título del video.
  list_channel: título del canal.
  list_owner: identificador único del usuario.
  screenname: nombre del usuario.
  city: ciudad del usuario.
  country: país del usuario.
  gender: género del usuario.
  playlists_total: número de playlists que el usuario posee.
  description: descripción del usuario.
  
