# docker-server

Before all, it is important to create the shared data volume that will be used by some projects:

    docker volume create --name=media

Then subfolders can be created in this volume like:

 - Downloads
 - Movies
 - Series

Becareful, these folders should have permissions 755.


TODO

- Ajout htpassword custom pour download private folder
- Ajout de custom pour redirection url ( genre plex et urttornet )
- Ajout de config pour gitlab  

    1517 a client request body is buffered to a temporary file /var/cache/nginx/client_temp/0000000002, error: RPC failed; HTTP 413 curl 22 The requested URL returned error: 413 Request Entity Too Large


