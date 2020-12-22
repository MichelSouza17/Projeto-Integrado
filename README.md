Dupla: Michel Araujo de Souza e Luiz Gustavo Cruz Bastos

DOCUMENTAÇÃO API FAST PARKING:

Funções da API:

GET:

Busca Por todos os veiculos cadastrados no estacionamento e traz em formato JSON.

EXEMPLO em JSON:

    {
        "idVeiculo": "10",
        "nomeCliente": "Felipe Souza",
        "placa": "FJY-5174",
        "Descricao": "HB20 Branco",
        "entrada": "2020-12-18 16:59:29",
        "saida": "2020-12-21 14:32:39"
    }

Exemplo url:

http://localhost/michel/ProjetoJsPhpBd/api/index.php/entrada

POST:

Faz o cadastro de veiculo. Para cadastrar é necessario informar o nome do cliente, placa e descrição assim como mostra o exemplo abaixo, Horario de entrada é gerado automatico.

{
    "nomeCliente": "Celso",
    "placa": "yyy-1111",
    "Descricao": "Corola preto"
}

PUT:
 
Gera somente o horario e data de saida clicando em SEND utilizando o POSTMAN, sem precisar declarar nenhum conteúdo.

Exemplo de url:

http://localhost/michel/ProjetoJsPhpBd/api/index.php/entrada/${id}


DELETE:

Deleta o veiculo cadastrado atravez do id.

Exemplo de url:

http://localhost/michel/ProjetoJsPhpBd/api/index.php/entrada/${id}
