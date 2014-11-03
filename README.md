TDA PARA GENERACION DE ARCHIVOS JSON
==================

# FUNCIONES DISPONIBLES
* Crear un nuevo nodo JSON (en adelante nJson)
* Asignarle nombre al nJson.
* Asignarle contenido* al nJson.
* Cambiarle el contenido* al nJson.
* Agregar nuevo nJson a un nJson existente.
* Agregar un nuevo elemento al Array almacenado en nJson.

# CONTENIDOS POSIBLES DE LOS NODOS
1. nJson.
2. Cualquier tipo de dato punto flotante.
3. Cualquier tipo de dato entero.
4. Strings.
5. Arrays de cualquier tipo entre 1 y 4.

NOTA: Solo un tipo de dato a la vez.

# EXAMPLE

{
  "size": "0 bytes",
  "hash": "37eb1ba1849d4b0fb0b28caf7ef3af52",
  "bytes": 0,
  "thumb_exists": false,
  "rev": "714f029684fe",
  "modified": "Wed, 27 Apr 2011 22:18:51 +0000",
  "path": "/Photos",
  "is_dir": true,
  "icon": "folder",
  "root": "dropbox",
  "contents": [
    {
      "size": "2.3 MB",
      "rev": "38af1b183490",
      "thumb_exists": true,
      "bytes": 2453963,
      "modified": "Mon, 07 Apr 2014 23:13:16 +0000",
      "client_mtime": "Thu, 29 Aug 2013 01:12:02 +0000",
      "path": "/Photos/flower.jpg",
      "photo_info": {
        "lat_long": [
          37.77256666666666,
          -122.45934166666667
        ],
        "time_taken": "Wed, 28 Aug 2013 18:12:02 +0000"
      },
      "is_dir": false,
      "icon": "page_white_picture",
      "root": "dropbox",
      "mime_type": "image/jpeg",
      "revision": 14511
    }
  ],
  "revision": 29007
}
