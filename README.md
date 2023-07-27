# Avaliacao4Distribuidos
Comandos antes de iniciar a aplicação:

docker-compose up -d

pip install -r requirements.txt

npm install

Detalhes da aplicação:
É uma continuação da aplicação disponível no link: https://github.com/lucaslm45/Avaliacao3Distribuidos. Porém, cliente e servidor precisam estar em linguagens de programação diferentes.

Não precisa mais assinar as mensagens de lance.

Para prover a comunicação entre os processos deve-se utilizar REST ou gRPC e não mais Pyro.

Para o envio das notificações de eventos, vocês vão utilizar o SSE (Server-Sent Events).

Resumindo:
- Duas linguagens de programação diferentes;
- Uso de REST ou gRPC para comunicação entre clientes e servidor;
- Uso do SSE para envio das notificações do servidor para os clientes.
