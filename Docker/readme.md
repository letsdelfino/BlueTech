# Inicialização do Docker

Para iniciar o container do Strapi no Mongo o comando é:
	
	 dokcer run -itd --name Strapi -p 1337:1337 -v /home/letsdelfino/BlueTech:/srv/app --restart always strapi/strapi
	
Para iniciar o container do MongoDB o comando é: 
	Na pasta /home/letsdelfino/BlueTech digite 
		
		 docker-compose -f mongodb.yml up
		 
A máquina virtual que se encontra nesta pasta contém os containers do MongoDB e Strapi. Eles estarão funcionando assim que a máquina virtual for ligada. Caso isso não ocorra, digite o seguinte comando no terminar com a permissão sudo anexado ao e-mail enviado com o link deste repositório: 
	
	docker start mongo
	docker start Strapi
	
Senha e usuário strapi:

	usuário: Admin
	senha: AdminStrapi88
