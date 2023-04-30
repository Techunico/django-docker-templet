- to create a app named app in container
`docker-compose run web django-admin startproject app .` 
- by default app will be created as root.
- to change the permission 
`sudo chown -R $USER:$USER .`