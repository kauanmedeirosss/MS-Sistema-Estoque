# Sobre o Docker Compose
Nele ocorrerá a definição de cada serviço que será levantado para o sistema.
## Docker Hub
Link para acesso: https://hub.docker.com
Para saber a referência de imagem de um serviço, acessamos o docker hub e pesquisamos pelo serviço desejado.  
Os resultados dessas pesquisas são os repositórios com referencias dessa imagem pesquisada.  
É possível diferenciar imagens oficiais e não oficiais.
## Portas de Comunicação
* Ex: 5672:5672
  - Na esquerda é a porta da máquina, na direita a porta do docker. Esse é o processo de espelhar portas.
   - O mesmo vale para o values, esquerdo é a pasta do pc, direito é a do docker (achamos essa informação na página do serviço no docker hub, geralmente com nome `database dir`).

# Comandos Docker
<img width="793" height="455" alt="image" src="https://github.com/user-attachments/assets/ba2c99cf-c7a4-433c-b764-b6744180de6b" />
* Basicamente, navega até a pasta do projeto/sistema e roda o comando docker lá
