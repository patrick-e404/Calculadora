# Calculadora C#

Este é um projeto de calculadora simples desenvolvido em C# usando Windows Forms. Ele permite realizar as quatro operações aritméticas básicas: adição, subtração, multiplicação e divisão.

## Visão Geral

O projeto é estruturado seguindo o padrão Model-View-Controller (MVC) para separar as responsabilidades e facilitar a manutenção e os testes.

## Estrutura do Projeto

* **Calculadora/:** Pasta do projeto principal.
    * **Properties/:** Contém configurações e recursos do projeto.
        * **AssemblyInfo.cs:** Informações sobre o assembly.
        * **Resources.resx:** Arquivo de recursos para strings e imagens.
        * **Settings.settings:** Configurações do aplicativo.
    * **Referências/:** Bibliotecas e dependências externas.
    * **app.config:** Arquivo de configuração do aplicativo.
    * **CalculadoraController.cs:** Lógica de controle que interage entre a View e o Model.
    * **CalculadoraModel.cs:** Modelo de dados e lógica de negócios da calculadora.
    * **CalculadoraView.cs:** Interface gráfica do usuário (GUI) construída com Windows Forms.
    * **Operacoes.cs:** Classe que encapsula as operações aritméticas.
    * **Program.cs:** Ponto de entrada principal do aplicativo.

## Funcionalidades

* Interface gráfica intuitiva com campos para inserir os valores e botões para as operações.
* Realiza as quatro operações aritméticas básicas.
* Exibe o resultado na interface.

## Tecnologias Utilizadas

* C#
* Windows Forms
* .NET Framework
