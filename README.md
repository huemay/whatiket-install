CRIAR SUBDOMINIO E APONTAR PARA O IP DA SUA VPS
FRONTEND_URL:Meudomio.com
BACKEND_URL: meudominio.com

teste de dominio https://dnschecker.org/

Passos 1
```bash
sudo su root
````
Passo 2
```bash
cd ~
````
Passo 3
```bash
apt install mysql-server
mysql --version
sudo systemctl status mysql
````


FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/Andresilvia/autoinstaladorsaas.git && sudo chmod -R 777 autoinstaladorsaas && cd autoinstaladorsaas && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd ./autoinstaladorsaas && sudo ./install_instancia
```



