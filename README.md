# Dailymotion

## Esquema de archivos

C:.
├───archivos_procesados
└───archivos_sin_procesar
    ├───users
    └───videos
    
    
## Informacion sobre el contenido

1. archivos_procesados:
  a. userid_allusers: contiene la informacion unificada de los 10 archivos que muestran la informacion del usuario
  b. videos_processed: con tiene la information unificada de los videos y usuarios
2. archivos_sinprocesar:
  a. video: La carpeta con tiene informacion sobre los videos de la plataforma 
  b. users: contiene informatcion sobre los usuarios a quienes pertenecen los videos
  
  ## Indice
  
  page: numero de pagina de los resultados que la API proporciona
  limit: el limite de resultados que se muestran por pagina
  total: numero de resultados a los que hay acceso
  has_more: TRUE ---> indica si que hay mas resultados por mostrar FALSE ---> indica  que no hay mas resultados por mostrar
  list_id: identificador unico de la lista de reproduccion
  list_title: titulo del video
  list_channel: titulo del canal
  list_owner: identificador unico del usuario
  screenname: nombre del usuario
  city: ciudad del usuario
  country: pais del usuario
  gender: genero del usuario
  playlists_total: numero de playlisys
  description: descripcion del usuario
  
