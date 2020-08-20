# Inicialização do Docker

Para iniciar o container do Strapi no Mongo o comando é:
	
	 dokcer run -itd --name Strapi -p 1337:1337 -v /home/letsdelfino/BlueTech:/srv/app --restart always strapi/strapi
	
Para iniciar o container do MongoDB o comando é: 
	Na pasta /home/letsdelfino/BlueTech digite 
		
		 docker-compose -f mongodb.yml up
		
