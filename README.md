# InfraestruturaComoCodigo
Meu primeiro projeto que provisiona uma infraestrutura via terraform 

Este código faz:
- Provisiona uma instância na AWS utilizando uma imagem do Linux, via Terraform.</br>
- Instala as dependencias de um projeto Python com Django, via Ansible
- Roda um Sell script dentro do arquivo settings.py para configurar os IPS que podem acessar o servidor
- Sobe o servidor do Djando dentro da EC2 na AWS.

Para rodar o projeto execute os seguintes comandos: 
- terraform init
- terraform plan
- terraform apply 

*Lembre-se de configurar suas credenciais da AWS na sua máquina local 😃👍
