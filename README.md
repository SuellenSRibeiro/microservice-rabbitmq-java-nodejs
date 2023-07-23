# Comunicação de Microserviços com RabbitMQ
Este projeto o RabbitMQ como um intermediador de mensagens para a comunicação entre diferentes componentes. A arquitetura consiste em um produtor de mensagens, que é um servidor de API responsável por lidar com as solicitações de atualização de estoque e preço feitas pelos usuários. Além disso, existem dois consumidores de mensagens, um desenvolvido em Java com Spring e outro em Node.js, que consomem mensagens da fila RabbitMQ e as processam conforme necessário.
<p> 
    <img width="600" height="300" src="src/map.png" >
</p>


## Visão Geral do RabbitMQ em Ação: Consumidores Processando Mensagens

<p> 
    <img width="700" height="300" src="src/rabbitmq.png" >
</p>
