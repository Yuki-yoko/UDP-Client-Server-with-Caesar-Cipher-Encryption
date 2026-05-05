# UDP-Client-Server-with-Caesar-Cipher-Encryption
Este projeto implementa um sistema de comunicação cliente-servidor utilizando o protocolo UDP, com aplicação de criptografia simples baseada na Cifra de César.

O objetivo é demonstrar o funcionamento de comunicação via sockets em Java, aliado a um mecanismo básico de segurança para transformação de mensagens durante a transmissão.

## Como funciona

O sistema é composto por dois componentes:

### Servidor (UDP)
- Escuta conexões na porta 9876
- Recebe mensagens em texto claro enviadas pelo cliente
- Aplica a Cifra de César com deslocamento de 3 posições
- Retorna a mensagem criptografada ao cliente

### Cliente (UDP)
- Lê uma mensagem digitada pelo usuário
- Envia a mensagem para o servidor
- Recebe a versão criptografada
- Exibe o resultado na tela

## Tecnologias utilizadas
- Java
- Sockets UDP (DatagramSocket, DatagramPacket)
- Programação de redes
