# Contador de Usuários Únicos em Logs de Acesso
Este é um programa em C# que lê registros de logs de acesso a um site a partir de um arquivo e conta quantos usuários distintos acessaram o site.

### Funcionalidades Principais:
Leitura de registros de log a partir de um arquivo.
Identificação e contagem de usuários únicos com base em seus nomes de usuário.
Uso de sobrescrita dos métodos GetHashCode e Equals na classe LogRecord para garantir a comparação correta dos registros de log.
Motivação:
Este projeto foi desenvolvido como uma solução para o problema de contagem de usuários únicos a partir de registros de log de acesso. Ele demonstra o uso de estruturas de dados e métodos especiais de comparação em C#.
### Problema Exemplo:
![Captura de tela 2023-08-17 152418](https://github.com/RafaelSantana03/Contador-de-Usuarios-Unicos-em-Logs-de-Acesso/assets/131009931/f443ae60-d357-4774-8b5b-c39026c1046a)



## Como Usar:
Clone este repositório para o seu ambiente local.
Abra o projeto em sua IDE preferida que suporte C#.
Certifique-se de que você possui o .NET SDK instalado em seu ambiente.
Execute o programa e siga as instruções para inserir o caminho completo do arquivo de log.
O programa lerá o arquivo de log, identificará os usuários únicos e exibirá o total.
## Classe LogRecord:
A classe LogRecord é responsável por representar cada registro de log de acesso. Ela possui duas propriedades:

### Username: 
O nome do usuário.
### Instant: 
O momento em que o usuário acessou o site.
A classe também sobrescreve os métodos GetHashCode e Equals para garantir a comparação correta dos registros de log, com foco na comparação dos nomes de usuário.

## Observação:
Este projeto é um exercício de aprendizado e prática em C# e manipulação de estruturas de dados. Fique à vontade para explorar, estudar e melhorar o código conforme suas necessidades.
