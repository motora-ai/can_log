# CAN LOG

Para executar o programa, execute o seguinte comando a seguir via terminal:

```bash
python robotell-python/usb-can.py -s VELOCIDADE -p PORTA -i ARQUIVO_LOG
```

substituindo os seguintes trechos:

- VELOCIDADE: Velocidade de funcionamento do adaptador CAN (geralmente utilizamos 500000).
- PORTA: Porta USB utilizada (geralmente vai ser uma /dev/ttyACMX, onde X é um número).
- ARQUIVO_LOG: O arquivo da CAN (veja a pasta [logs](./logs)).

## OBSERVAÇÕES

1. Para descobrir qual a porta USB utilizada, utilize o comando abaixo:

```bash
sudo dmesg
```

2. Caso o USB morra por causa do adaptador e script, utilize o comando abaixo:

```bash
sudo ./reset_usb_controller.sh
```
