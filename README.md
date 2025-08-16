# ZooConnect: Sistema de Gerenciamento de Zoológico

## 1\. Visão Geral do Projeto

**ZooConnect** é uma aplicação em Python desenvolvida como projeto final para a disciplina de Programação Orientada a Objetos. O objetivo principal é criar um sistema robusto para o controle e gerenciamento de animais e das tarefas de seus tratadores em um zoológico.

A aplicação foi projetada para aplicar e demonstrar os principais conceitos de POO, como classes, herança, polimorfismo, encapsulamento, manipulação de arquivos, e tratamento de exceções.

## 2\. Contexto

O sistema simula o ambiente de um zoológico, onde é crucial gerenciar os cuidados com os animais, incluindo alimentação, limpeza, tratamento e banho de sol em horários específicos. Além disso, o projeto contempla a gestão dos tratadores e a supervisão de suas atividades por um administrador, que precisa de relatórios precisos sobre as tarefas executadas.

## 3\. Funcionalidades

O sistema é dividido em dois módulos principais de interação: Tarefas do Tratador e Tarefas do Administrador.

### Tarefas do Tratador

Os tratadores são responsáveis pela execução das seguintes atividades diárias:

  * **Tratar Animais:** Fornecer cuidados específicos de acordo com a necessidade de cada espécie.
  * **Alimentar Animais:** Garantir que os animais sejam alimentados nos horários corretos e com a dieta apropriada.
  * **Limpar Recintos:** Realizar a limpeza dos recintos dos animais conforme a programação.
  * **Banho de Sol:** Levar os animais para tomar banho de sol diariamente, conforme a necessidade.

### Tarefas do Administrador

O administrador possui uma visão geral e de controle sobre as operações do zoológico:

  * **Rastrear Atividades:** Monitorar e gerar relatórios sobre quantos animais foram cuidados e qual tratador realizou cada tarefa.

## 4\. Estrutura Técnica e Conceitos Aplicados

O projeto foi estruturado utilizando uma arquitetura orientada a objetos para garantir um código modular, reutilizável e de fácil manutenção.

  * **Classes e Herança:**
      * Os animais são representados por classes que derivam de uma classe base `Animal`, cada uma com comportamentos específicos de alimentação e tratamento.
      * Os tratadores também são classes derivadas de uma classe base `Tratador`.
  * **Polimorfismo:** Permite que diferentes tipos de animais respondam à mesma chamada de método (como `alimentar()` ou `tratar()`) de maneiras distintas.
  * **Encapsulamento:** Protege os dados sensíveis das classes, expondo apenas as informações e métodos necessários para a interação.
  * **Manipulação de Arquivos:** O sistema implementa a lógica para incluir e ler dados de arquivos, garantindo a persistência das informações dos animais e tratadores.
  * **Estruturas de Dados:** Utiliza listas, filas e dicionários para gerenciar os animais, as tarefas e os cronogramas dos tratadores. 
  * **Interface com o Usuário:** A interação com o sistema é feita através de um menu de opções no console.

## 5\. Como Executar o Projeto

Para executar a aplicação em um ambiente Python, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/nathanvgarrett/Zoo-Connect.git
    ```
2.  **Navegue até o diretório do projeto:**
    ```bash
    cd Zoo-Connect
    ```
3.  **Execute o arquivo principal:**
    ```bash
    python main.py
    ```

-----
