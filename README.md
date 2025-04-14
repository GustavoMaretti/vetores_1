# Gerenciamento de Quartos de Estudantes

## Funcionalidades
- Criar e gerenciar um sistema de alocação de quartos com as seguintes opções:
  - Registro do nome e email dos estudantes.
  - Escolha do número do quarto a ser alugado.
  - Identificação automática dos quartos ocupados.
- Exibir os dados atualizados dos quartos, incluindo:
  - Número do quarto.
  - Informações do estudante (nome e email).

## Uso
- O programa solicita ao usuário, via console:
  - Quantidade de quartos que serão alugados.
  - Dados dos estudantes (nome e email).
  - Número do quarto escolhido.
- O programa exibe automaticamente a lista de quartos ocupados no formato:
  - `Número do quarto: Nome, Email`.

## Estrutura

### Classe `Estudante`
- **Propriedades**:
  - `Nome`: Nome do estudante.
  - `Email`: Email do estudante.
- **Construtor**:
  - Inicializa os campos com os dados fornecidos pelo usuário.
- **Método `ToString()`**:
  - Retorna uma string formatada com o nome e email do estudante.

### Programa Principal
- **Vetores**:
  - Utilizados para gerenciar os quartos (até 10).
- **Laços de repetição**:
  - Interação com o usuário para alugar os quartos.
- **Validações**:
  - Verifica se o quarto está ocupado antes de alocar um novo estudante.

## Tecnologias
- C#
- .NET 6.0
- Aplicação de console
