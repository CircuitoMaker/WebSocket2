Uma API de WebSocket usa um protocolo de comunicação bidirecional que permite uma conexão contínua e de baixa latência entre um cliente e um servidor. Diferentemente do HTTP tradicional, que é baseado em solicitação e resposta, o WebSocket mantém uma conexão persistente, possibilitando a troca de dados em tempo real.

 Alguns exemplos de uso de uma API WebSocket:

1. **Chat em tempo real**: Para criar salas de bate-papo interativas onde os usuários podem trocar mensagens instantaneamente (WhatsApp por ex).

2. **Jogos online**: Para permitir jogos multiplayer em tempo real com baixa latência.

3. **Monitoramento em tempo real**: Usado para atualizar constantemente dados em painéis de controle, como métricas de IoT (essa é a minha intenção).

4. **Notificações push**: Para enviar alertas e atualizações instantâneas a clientes, como notificações de mensagens ou eventos (Notificações de Apps por ex).
 

**Testando**: Uma versão de testes esta hospedado em um servidor online e para acessa-lo você deve Seguir os seguintes passos:

- Baixe o programa "Insomnia". 
- Crie uma conexão do tipo "Web Socket Request".
- Adicione a seguinte URL "wss:/websocket2-reles.up.railway.app".  
- Click em "Conectar".
- O a API deve retornar "Seja bem vindo ao servidor WebSocket!".
- Escreva algum texto e click em "send".
- O servidor deve retornar a frase "Voce disse" seguido do texto que você enviou.


![Insomnia](https://github.com/CircuitoMaker/WebSocket2/assets/3664249/0ee2a183-0d05-4de1-b919-fce4cddee0d2)

