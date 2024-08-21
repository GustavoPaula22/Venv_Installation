# Venv_Installation

 - instalação e configuração ambiente venv primeiro instala o venv
 * sudo apt install python3-venv

 - agora pode ser feito a criação e ativação do venv
 * python3 -m venv .venv
 * source .venv/bin/activate

--------------------------------------------------
 - Configurando SQL Server 
 * sudo apt update
 * sudo apt install unixodbc unixodbc-dev

 * sudo su
 * curl https://packages.microsoft.com/keys/microsoft.asc | apt-key add -
 * curl https://packages.microsoft.com/config/ubuntu/20.04/prod.list > /etc/apt/sources.list.d/mssql-release.list
 * exit

 * sudo apt update
 * sudo ACCEPT_EULA=Y apt install msodbcsql17

--------------------------------------------------
 - pode ser criado um diretorio para suas aplicações
 * mkdir ~/Aplicações

 - clonar algum projeto do git
 * git clone https://github.com/GustavoPaula22/Python_ContratoLicitacoesETL.git

 - ou remover algum arquivo
 * rm -r ~/Aplicações/Python_ContratoLicitacoesETL

 - para abrir o projeto no vscode pode ser utilizado o comando
 * code .
