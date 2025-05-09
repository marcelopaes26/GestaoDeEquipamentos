# Gestão de Equipamentos

## Descrição
Este projeto é uma aplicação de console desenvolvida em C# para gerenciamento de equipamentos, chamados e fabricantes. Ele permite cadastrar, visualizar, editar e excluir registros de equipamentos, chamados e fabricantes, oferecendo uma interface simples e interativa no console.

## Funcionalidades
- **Controle de Equipamentos**:
  - Cadastro de novos equipamentos, associando-os a fabricantes.
  - Visualização de todos os equipamentos registrados.
  - Edição de registros de equipamentos existentes.
  - Exclusão de equipamentos.
- **Controle de Chamados**:
  - Cadastro de novos chamados associados a equipamentos.
  - Visualização de todos os chamados registrados.
  - Edição de registros de chamados existentes.
  - Exclusão de chamados.
- **Controle de Fabricantes**:
  - Cadastro de novos fabricantes.
  - Visualização de todos os fabricantes registrados.
  - Edição de registros de fabricantes existentes.
  - Exclusão de fabricantes.
- **Menu Interativo**:
  - Menu principal para navegação entre controle de equipamentos, chamados e fabricantes.
  - Opção de sair da aplicação.

## Estrutura do Projeto
O projeto é organizado em módulos e utiliza uma abordagem orientada a objetos:
- **Módulo Equipamento**:
  - `RepositorioEquipamento`: Gerencia os dados dos equipamentos.
  - `TelaEquipamento`: Interface de console para interação com o usuário, integrada com fabricantes.
- **Módulo Chamado**:
  - `RepositorioChamado`: Gerencia os dados dos chamados.
  - `TelaChamado`: Interface de console para interação com o usuário.
- **Módulo Fabricante**:
  - `RepositorioFabricante`: Gerencia os dados dos fabricantes.
  - `TelaFabricante`: Interface de console para interação com o usuário.
- **Program**: Classe principal que inicializa os repositórios, telas e controla o fluxo do programa.

## Como Executar
1. **Pré-requisitos**:
   - .NET SDK instalado (versão compatível com o projeto).
2. **Passos**:
   - Clone o repositório ou copie o código para um diretório local.
   - Abra o terminal no diretório do projeto.
   - Execute o comando:
     ```bash
     dotnet run
     ```
   - Siga as instruções no console para navegar pelo menu e utilizar as funcionalidades.

## Uso
- No menu principal, escolha:
  - `1` para gerenciar equipamentos.
  - `2` para gerenciar chamados.
  - `3` para gerenciar fabricantes.
  - `S` para sair da aplicação.
- Nos submenus de equipamentos, chamados ou fabricantes, escolha:
  - `1` para cadastrar um novo registro.
  - `2` para visualizar registros.
  - `3` para editar um registro existente.
  - `4` para excluir um registro.
  - `S` para voltar ao menu principal.