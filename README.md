# RoboAutomacaoSistemaWeb

Este projeto contém um robô UiPath projetado para automatizar interações com um sistema web. Ele provavelmente processa dados de um arquivo Excel (`arquivos/challenge.xlsx`) para realizar tarefas em um site.

## Estrutura do Projeto

*   `Main.xaml`: O arquivo principal do fluxo de trabalho que orquestra o processo de automação.
*   `project.json`: Define os metadados do projeto, dependências e opções de execução.
*   `arquivos/challenge.xlsx`: Um arquivo Excel provavelmente usado como dados de entrada para a automação.

## Pré-requisitos

*   UiPath Studio (recomendado versão 24.10.16.0 ou mais recente)
*   Os seguintes pacotes de atividades do UiPath:
    *   `UiPath.Excel.Activities`
    *   `UiPath.System.Activities`
    *   `UiPath.UIAutomation.Activities`
    *   (Outras dependências listadas em `project.json` serão gerenciadas automaticamente pelo UiPath Studio)

## Como Executar

1.  **Abra o projeto:** Abra `project.json` ou `Main.xaml` no UiPath Studio.
2.  **Certifique-se de que as dependências estão resolvidas:** O UiPath Studio deve restaurar automaticamente quaisquer pacotes de atividades ausentes.
3.  **Configure os dados de entrada:** Verifique se o arquivo `arquivos/challenge.xlsx` contém os dados necessários no formato esperado.
4.  **Execute o fluxo de trabalho:** Clique no botão "Executar" no UiPath Studio para executar a automação.
5.  


Desafio cumprido
![1767646147524](image/README/1767646147524.png)

"RPA criado como desafio do curso Automatize Process com Erimateia"

