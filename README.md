# dockerApt

Este repositório fornece um ambiente de desenvolvimento baseado no Docker. Personalize a lista de servidores espelho editando o arquivo `mirror.list` localizado em `/config`. Para ajustar o intervalo de ressincronização do container com os espelhos, modifique o parâmetro `RESYNC_PERIOD` no arquivo `docker-compose.yml`. O valor padrão é definido para 12 horas.

## Pré-requisitos
Certifique-se de ter o Docker e o Docker Compose instalados em seu sistema.

## Como usar

### Criar e levantar os containers
docker-compose up -d

### Iniciar o container Docker
docker-compose start

### Parar o container Docker
docker-compose stop


## Acesso

### Apache
Visite [http://ipdoservidor](http://ipdoservidor) para acessar o ambiente Apache.

### Portainer
Acesse [http://ipdoservidor:9000](http://ipdoservidor:9000) para usar o Portainer. Durante o primeiro login, crie suas credenciais de acesso.

Esperamos que este ambiente Docker facilite seu desenvolvimento. Sinta-se à vontade para contribuir ou fornecer feedback.
