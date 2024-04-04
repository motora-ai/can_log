# CAN LOG

Para executar o programa, execute o seguinte comando a seguir via terminal:

`python robotell-python/usb-can.py -s VELOCIDADE -p PORTA -i ARQUIVO_LOG`

substituindo os seguintes trechos:

- VELOCIDADE: Velocidade de funcionamento do adaptador CAN (geralmente utilizamos 500000).
- PORTA: Porta USB utilizada (geralmente vai ser uma tty/ACMX, onde X é um número).
- ARQUIVO_LOG: O arquivo da CAN (veja a pasta [logs](./logs)).
