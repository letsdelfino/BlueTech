# Inicialização do Docker

Para iniciar o container do Strapi no Mongo o comando é:
	dokcer run -itd --name Strapi -p 1337:1337 -v /home/.../Blue Tech:/home/data/db --restart alwayss strapi
	
Para iniciar o container do MongoDB o comando é: 
	Na pasta /home/.../Blue Tech digite 
		docker-compose -f mongodb.yml up