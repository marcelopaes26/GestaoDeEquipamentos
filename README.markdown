# Gestão de Equipamentos

## Descrição
Este projeto é uma aplicação de console desenvolvida em C# para gerenciamento de equipamentos e chamados. Ele permite cadastrar, visualizar, editar e excluir registros de equipamentos e chamados, oferecendo uma interface simples e interativa no console.

## Funcionalidades
- **Controle de Equipamentos**:
  - Cadastro de novos equipamentos.
  - Visualização de todos os equipamentos registrados.
  - Edição de registros de equipamentos existentes.
  - Exclusão de equipamentos.
- **Controle de Chamados**:
  - Cadastro de novos chamados associados a equipamentos.
  - Visualização de todos os chamados registrados.
  - Edição de registros de chamados existentes.
  - Exclusão de chamados.
- **Menu Interativo**:
  - Menu principal para navegação entre controle de equipamentos e chamados.
  - Opção de sair da aplicação.

## Estrutura do Projeto
O projeto é organizado em módulos e utiliza uma abordagem orientada a objetos:
- **Módulo Equipamento**:
  - `RepositorioEquipamento`: Gerencia os dados dos equipamentos.
  - `TelaEquipamento`: Interface de console para interação com o usuário.
- **Módulo Chamado**:
  - `RepositorioChamado`: Gerencia os dados dos chamados.
  - `TelaChamado`: Interface de console para interação com o usuário.
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
  - `S` para sair da aplicação.
- Nos submenus de equipamentos ou chamados, escolha:
  - `1` para cadastrar um novo registro.
  - `2` para visualizar registros.
  - `3` para editar um registro existente.
  - `4` para excluir um registro.
  - `S` para voltar ao menu principal.
