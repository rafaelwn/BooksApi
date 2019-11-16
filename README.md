# BooksApi set up

# install mongo on ubuntu
https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/

# aspnet core - mongo
https://docs.microsoft.com/pt-br/aspnet/core/tutorials/first-mongo-app?view=aspnetcore-3.0&tabs=visual-studio-code

# aspnet core - swagger
https://docs.microsoft.com/pt-br/aspnet/core/tutorials/getting-started-with-swashbuckle?view=aspnetcore-3.0&tabs=visual-studio

# start mongo
sudo service mongod start

# start webapi
dotnet run

# show Swagger Doc
https://localhost:5001/index.html

# tutorial docker
https://docs.microsoft.com/pt-br/dotnet/core/docker/build-container

# create file Dockerfile
touch Dockerfile

# create image docker ( in directory of Dockerfile )
docker build -t bookapi-image-v2 .

# create and runn container
docker run -d -p 7991:80 --name bookapi-container bookapi-image-v2

# next step, create a microservice ...
https://dotnet.microsoft.com/learn/aspnet/microservice-tutorial/create

