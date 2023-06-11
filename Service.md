# Exemplo de serviço simples

```
[Unit]
Description=servico
StartLimitIntervalSec=0
[Service]
Type=simple
Restart=always
RestartSec=1
User=root
ExecStart=caminho/servico.sh

[Install]
WantedBy=multi-user.target
```
