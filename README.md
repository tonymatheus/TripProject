TripProject é uma pequena aplicação Feita em React.js que  utiliza o redux e implementa melhorias em  seu  ambiente de  gerenciamento  de  estados da aplicação  com o auxílio 
do Redux Saga, nessa aplicação é feito um exemplo de reservas de Hotéis para alguns 
pontos turísticos, o cliente solicita uma reserva,tem  acesso a suas reservas e a quantidade de solicitações feita,tabém são  feitas validações simples para o controle dessas reservas,toda a anipulação de estado erotas é feita pelo Redux e Redux-saga.

Essa Aplicação Foi Constrída no Intuíto  de aplicar os conceitos do Redux e Redux-Saga
tais como : anctions,reducers,store, e  outros  conceitos importantes para compreenção
da biblioteca .

Iniciando a Aplicação :

após dar o Git Clone no Repositório execute o comando yarn install para instalar as  dependências necessárias para o funcionamento da aplicação.

Na Aplicação foi utilizada uma API Fake que  retorna fotos e  dados  de pontos turísticos para  rodar  essa api é  necessário instalar o JSON server , para fazer  isso  execute o comando :
    yarn add json-server 

após instalar digite o seguinte comendo  para  executar o  server :
    json-server server.json -p 3333
esse comando  executa o server e roda ele na porta 3333.



