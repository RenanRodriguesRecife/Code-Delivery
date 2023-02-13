# Code-Delivery

Estudo de caso Code Delivery - Microsserviços - Imersão Full Stack &amp;&amp; Full Cycle - Fev 2023 (ON GOING)


- Sistema de entregas que permite visualizr em tempo real o veículo do entregador

- Há a possibilidade de multiplos entregadores simultâneos

- Serviços simulador que enviará a posição em tempo real de cada entregador

- Os dados de cada entrega, bem como as posições serão armazenadas no Elasticsearch para futuras análises.


Alguns desafios

- Para evitar perda de informações caso o serviço backend fique indisponível por alguns momentos, NÃO, trabalharemos com REST.

Solução: Trabalharemos com o Apache kafka para o envio e recebimento de dados entre os sistemas
