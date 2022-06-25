# EB-2022-1-CC50
Trabajo Final del curso de Administración de la Información

# Objetivo del proyecto
El objetivo es realizar un proyecto de data science que nos permita determinar las tendencias, gustos, categorías y mejor valorados tipos de videos y canales de Youtube Francia. A través de un modelado de datos se conservará o añadirá información relevante que permita poder resolver alguna imperfección de los mismos para que nuestro análisis final pueda ser el más óptimo.

# Integrantes:
  - Nander Emanuel Melendez Huamanchumo (u201922331)
  - Luis Roberto Arroyo Bonifaz (u201716094)

# Breve descripción del conjunto de datos
Se tienen 2 conjuntos de datos, uno es un archivo de tipo csv que contendrá toda la información respecto a los vídeos tendencia de Youtube Francia, el otro archivo es un tipo json que tiene la información respecto a las categorías de videos disponibles.

## Respecto al archivo de información de los videos se tiene lo siguiente:

 - Video_id: Identificador único de un video.
 - Trending_date: Fecha en la que este video se ubicó en tendencia en su país.
 - Title: Titulo del video.
 - Channel_title: Nombre del canal desde el que fue subido el video.
 - Category_id: Id del tipo de categoría en el que se encuentra el video.
 - Publish_time: Fecha de publicación del video.
 - Tags: Etiquetas puestas en los videos para su búsqueda.
 - Views: Cantidad de visitas del video en la fecha de tendencia.
 - Likes: Cantidad de likes del video en la fecha de tendencia.
 - Dislikes: Cantidad de dislikes del video en la fecha de tendencia.
 - Comment_count: Cantidad de comentarios del video en la fecha de tendencia.
 - Thumbnail_link: Link de la imagen de miniatura del video.
 - Comments_disabled: Estado de los comentarios, si están o no activados.
 - Ratings_disabled: Estado de visualización de los likes y dislikes, si están o no activados.
 - Video_error_or_removed: Indica si el video ha sido a o no removido.
 - Description: Descripción del video.
 - State: Estado desde el que fue subido el video.
 - Lat: Latitud desde la que fue subido el video.
 - Lon: Longitud desde la que fue subido el video.
 - Geometry: Coordenada desde la que fue subido el video.

## Respecto al archivo de información de las categorías:
 - Kind: Tipo de información.
 - Etag: Link que incluye este tipo de categoría.
 - Id: identificador del tipo de categoría.
 - Snippet: Información respecto de la categoría que contiene lo siguiente:
	- ChannelId: Identificador del canal que incluye los videos de dicha categoría.
	- Title: Título del tipo de categoría.
	- Assignable: Indica si se puede asignar tal categoría de video.

# Conclusiones
# Licencia de uso
Para este trabajo, hemos decidido hacer el uso de la licencia [Atribución-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es)
