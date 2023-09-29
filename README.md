## Créditos
Ainda sem créditos, testando código

## Instruções
### Verificando atualizações da VPS e reiniciando (necessário login ssh após isso)
```bash
sudo apt -y update && apt -y upgrade
sudo reboot
```

### FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):
```bash
sudo apt install -y git && git clone https://github.com/pujoni/instalodordeploy.git && sudo chmod -R 777 instalodordeploy && cd instalodordeploy&& sudo ./install_primaria
```

### ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && rm -rf instalodordeploy && git clone https://github.com/pujoni/instalodordeploy.git && sudo chmod -R 777 instalodordeploy && cd instalodordeploy && sudo ./install_instancia
```

