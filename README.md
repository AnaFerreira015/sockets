# Socket em Python
Utilização da biblioteca socket para realizar a comunicação entre processos via socket. 

## Visão geral (funcionalidades)
Nesta aplicação será possível enviar mensagens de um (ou mais) cliente para um servidor usando os protocolos TCP (protocolo orientado a conexão), UDP (protocolo orientado a data gramas) e usando threads (fluxos de processos). Para que mais de um cliente envie mensagens para o servidor, será necessário usar o conteúdo que está em **/src/thread**.

## Pré-requisitos
- Python3

## Instruções de execução UDP
Acesse o diretório **/src/udp**
1. Abra o terminal (prompt de comando) e execute o servidor UDP:
<br />`python server_udp.py`
2. Abra um novo terminal (prompt de comando) e execute o cliente UDP: 
<br />`python client_udp.py`
<br />Digite as mensagens no cliente e observe-as chegando no servidor. Para sair pressione CTRL+X.

## Instruções de execução TCP
Acesse o diretório **/src/tcp**
1. Abra o terminal (prompt de comando) e execute o servidor TCP:
<br />`python server_tcp.py`
2. Abra um novo terminal (prompt de comando) e execute o cliente TCP: 
<br />`python client_tcp.py`
<br />Digite as mensagens no cliente e observe-as chegando no servidor. Para sair pressione CTRL+X.

## Instruções de execução THREAD
Acesse o diretório **/src/thread**
1. Abra o terminal (prompt de comando) e execute o servidor thread:
<br />`python server_thread_tcp.py`
2. Abra um novo terminal (prompt de comando) e execute o cliente thread: 
<br />`python client_tcp.py`
<br />Digite as mensagens no cliente e observe-as chegando no servidor. Para sair pressione CTRL+X.

Nas execuções TCP e UDP, apenas um cliente pode se conectar ao servidor por vez. Para o exemplo com Thread, porém, conecte mais de um cliente ao mesmo tempo, para visualizar o funcionamento da thread.

# Referências
[Socket Programming in Python](https://realpython.com/python-sockets/)
