# Código do Arduino

Código em C/C++ que controla o CBA:

- recebe os comandos do aplicativo pelo módulo Bluetooth;
- gira o micro servo motor para liberar a ração;
- liga a bomba de água para encher o pote;
- lê os sensores de peso e envia as quantidades para o aplicativo.

## Como enviar para a placa

1. Instale a [Arduino IDE](https://www.arduino.cc/en/software).
2. Abra o arquivo `.ino` desta pasta.
3. Em **Ferramentas → Placa**, escolha o modelo do Arduino usado.
4. Em **Ferramentas → Porta**, escolha a porta em que a placa está ligada.
5. Clique em **Carregar** (a seta →).
