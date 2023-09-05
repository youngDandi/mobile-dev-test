Descrição:

O tratamento dos dados foi feito por meio de uma base de dados não relacional, desenvolvido em json.



passos para rodar o projecto:

1-Deve baixar primeiro todas as dependências, executando o "npm install".


2-Deve verificar se o ip colocado nas funções handleCadastro (que está no componente cadastro da view), handleEliminar (que está no componente Apresentação da view) e no package.json nos scripts o "task": "json-server --watch ./backend/db.json --host 192.168.1.7 --port 3001"  é o mesmo que o da sua máquina.


ip:192.168.1.7

NOTA: se não for o mesmo basta trocar o ip para o da sua máquina


3-Para executar o backend basta rodar o comando "npm run task"


4-Para executar o frontend basta rodar o comando "npm start"


Obrigado pela atenção!!


