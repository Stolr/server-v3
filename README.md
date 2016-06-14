# docker-server

Before all, it is important to create the shared data volume that will be used by some projects:

    docker volume create --name=media

Then subfolders can be created in this volume like:

 - Downloads
 - Movies
 - Series

Becareful, these folders should have permissions 755.


TODO

-- Ajout htpassword custom pour download private folder
-- Ajout de custom pour redirection url ( genre plex et urttornet )
