# Documento de Visão

## Historico de versão

 Data | Versão | Descrição | Autor
 ---- | ------ | --------- | -----
20/10/20 | 1.0 | Abertura do documento | Giovanna

## Introdução 

Este documento tem como objetivo esclarecer o planejamento e o processo Ágil utilizado pelo time do projeto E-conomia. Descreve informações como papéis existentes, ritos do Scrum adotados e planejamento do projeto.

## Papéis na equipe <a name="2"></a>

Esta sessão lista todos os papéis existentes dentro do Time Scrum desse projeto, suas atribuições e as pessoas que os estão exercendo.

### Product Owner <a name="2.1"></a>
**Atribuições**
* Responsável pelo gerenciamento do Backlog do Produto e por garantir o valor do trabalho realizado pelo Time;
* Manter o Backlog do Produto e garante que ele está visível para todos;
* Informar a todos quais itens têm a maior prioridade, de forma que todos sabem em que se irá trabalhar;
* Definir e priorizar os itens do Backlog do Produto;
* Valor de negócio;
* Visão de negócio;

### Scrum Master <a name="2.2"></a>
**Atribuições**
* Ajudar todos do Time Scrum a entenderem a teoria, prática, regras e valores do Scrum.
* Servir ao Product Owner, auxiliando de diversas formas, tais como: gerir de maneira eficiente o Backlog do produto.
* Fazer todos do Time Scrum entenderem ao máximo os ítens do Backlog do Produto.
* Servir a equipe, auxiliando de diversas formas, tais como: remover impedimentos ao progresso de todos da equipe. instrui-lo em auto-organização e a serem multifuncionais.

### Desenvolvedores <a name="2.3"></a>
**Atribuições**

- Entregar os ítens contidos no Backlog da Sprint ao final de cada Sprint.
- Determinar como farão para entregar os ítens do Backlog da Sprint (auto-organização).

## Equipe

A equipe é formada por 5 alunos da Universidade de Brasília:

- Hugo Aragão de Oliveira - 16/0124581 - **Desenvolvedor**
- Giovanna Borges Bottino - 170011267 - **Product Owner** e **Desenvolvedora**
- João Gabriel de Campos de Matos - 180042238 - **Desenvolvedor**
- Vinicius Porto - 150065515 - **Scrum Master** e **Desenvolvedor**
- Luís Fernando Furtado de Araújo - 180042661 - **Desenvolvedor**


## Ritos do Scrum

Abaixo ritos do Scrum que serão realizados pelo Time Scrum desse projeto. Para cada rito está descrito seus objetivos, o tempo máximo de realização deles, os dias e horários em que ocorrerão.

### Sprint

#### Objetivo

- atingir o objetivo para a Sprint definido no Planejamento da Sprint, assim como entregar todos os ítens do Backlog da Sprint
- time box: segunda à domingo [1 semana]

### Planejamento de Sprint

- Reunião realizada com o Time Scrum no início de cada Sprint que tem como objetivo:

- Determinar o que poderá ser entregue na Sprint que se inicia (criação do Backlog da Sprint).
- Isso deve ser negociado entre o Product Owner e restante da equipe, respeitando a capacidade projetada e a performance passada deste estimar o esforço necessário para entregar as histórias do backlog, através da pontuação delas usando o planning poker.
- Antes do início da pontuação de cada história, o Product Owner deve explicá-la e tirar as dúvidas da equipe, para que todos possam ter uma melhor base para a pontuação.
- Cada participante vota, dando os pontos que acham que aquela história vale, tendo como base quantas horas eles imaginam que serão necessárias para completá-la. O voto de todas as pessoas só é revelado quando todos tiverem decidido quantos pontos darão para a história.
- A pontuação dada para cada história deve estar dentro da sequência de Fibonacci, sendo a menor pontuação válida 1
este passo é repetido até que haja consenso de todos os presentes sobre quantos pontos a história em questão vale.
- A equipe passa a pontuar a próxima história, até que todas estejam pontuadas.
- Determinar como a equipe irá se organizar para que haja a entrega prevista para a Sprint

- time box: : 23:00 [2h]

### Daily Meeting

- Reunião diária do Time Scrum que tem como objetivo:
- Cada membro responder as 3 perguntas abaixo, sobre sua participação no andamento da Sprint:
- O que foi feito pelo membro no dia anterior para ajudar a desenvolver na Sprint?
- O que será feito pelo membro no dia atual para ajudar no desenvolvimento na Sprint?
- Houve algum empedimento para o membro que impossibilitou ele ajudar o restante da equipe na Sprint? (gerenciamento de riscos)
- Dailys online: todos os dias começando às 22:00.

## Escopo
Uma aplicação web de finanças pessoais. Tem como objetivo ajudar pessoas físicas a administrar seu dinheiro. Auxiliando no controle de entrada e saída de dinheiro e controle de metas. O programa desenvolvido tem como intuito facilitar o acesso à organização
    financeira pessoal.

## Resultados
<ol>
    <li>Espera-se que o resultado seja um protótipo dessa aplicação web.</li>
    <li>Relatórios da aplicação das técnicas de engenharia de requisitos.</li>
    <li>Relatórios da aplicação das técnicas de engenharia de software.</li>
</ol>

## Requisitos
Análise do problema:

<table border="1">
    <tbody>
        <tr>
            <td>Problema</td>
            <td>Desorganização financeira, falta de ferramentas customizáveis para organização de fluxo de caixa</td>
        </tr>
        <tr>
            <td>Afeta</td>
            <td>Adolescentes e adultos que estão entrando no ambiente de organização financeira</td>
        </tr>
        <tr>
            <td>Impacto</td>
            <td>População com dívidas e muitas preocupações financeiras</td>
        </tr>
        <tr>
            <td>Solução</td>
            <td>Criação de uma aplicação ‘web’ de finanças pessoais com ferramentas de fluxo de caixa customizáveis</td>
        </tr>
    </tbody>
</table><br> Seguindo essa lógica foi decidido os seguintes épicos: <br>

## Épicos

<table border="1">
    <tbody>
        <tr>
            <th>ID</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>EP01</td>
            <td>Aplicação web de finanças pessoais</td>
        </tr>
        <tr>
            <td>EP02</td>
            <td>Fluxo de caixa customizável</td>
        </tr>
        <tr>
            <td>EP03</td>
            <td>Calculadora de despezas</td>
        </tr>
    </tbody>
</table>

## Requisitos

<table border="1">
    <tbody>
        <tr>
            <th>ID</th>
            <th>Épico</th>
            <th>Descrição</th>
            <th>Tipo</th>
        </tr>
        <tr>
            <td>RF01</td>
            <td>EP01</td>
            <td>Permitir cadastrar/fazer login</td>
            <td>Funcional</td>
        </tr>
        <tr>
            <td>RF02</td>
            <td>EP02</td>
            <td>Criar/editar/deletar Label</td>
            <td>Funcional</td>
        </tr>
        <tr>
            <td>RF03</td>
            <td>EP01</td>
            <td>Criar/editar/deletar Transações de entrada e saída</td>
            <td>Funcional</td>
        </tr>
        <tr>
            <td>RF04</td>
            <td>EP03</td>
            <td>Fazer o calculo do gasto total</td>
            <td>Funcional</td>
        </tr>
        <tr>
            <td>RF05</td>
            <td>EP03</td>
            <td>Mostrar o gráfico dos gastos ao longo do tempo</td>
            <td>Funcional</td>
        </tr>
        <tr>
            <td>RF06</td>
            <td>EP03</td>
            <td>Armazenar os dados dos gastos</td>
            <td>Funcional</td>
        </tr>
        <tr>
            <td>RF07</td>
            <td>EP03</td>
            <td>Mostrar o label que gera mais despeza</td>
            <td>Funcional</td>
        </tr>
        <tr>
            <td>NF01</td>
            <td>EP01</td>
            <td>A arquitetura utilizará o padrão de microserviços</td>
            <td>Não Funcional (Implementação)</td>
        </tr>
        <tr>
            <td>RF01</td>
            <td>EP01</td>
            <td>Níveis de segurança em criptografia para autenticação</td>
            <td>Não funcional</td>
        </tr>
        <tr>
            <td>RF08</td>
            <td>EP01</td>
            <td>Layouts responsivos para portabilidade em qualquer dispositivo</td>
            <td>Não funcional</td>
        </tr>
    </tbody>
</table>

## Historias de Usuario

<table border="1">
    <tbody>
        <tr>
            <th>ID</th>
            <th>Eu desejo como usuario</th>
            <th>Para</th>
            <th>Prioridade</th>
            <th>Feature ID</th>
        </tr>
        <tr>
            <td>US01</td>
            <td> fazer login </td>
            <td> alterar/visualizar meus dados </td>
            <td>Alta</td>
            <td>RF01</td>
        </tr>
        <tr>
            <td>US02</td>
            <td>me cadastrar</td>
            <td>meus dados serem salvos pela aplicação</td>
            <td>Alta</td>
            <td>RF01</td>
        </tr>
        <tr>
            <td>US03</td>
            <td>Poder criar labels para as transações </td>
            <td>Poder visualizar mellhor meus gastos</td>
            <td>Alta</td>
            <td>RF02</td>
        </tr>
        <tr>
            <td>US04</td>
            <td>Poder editar labels para as transações </td>
            <td>Poder visualizar mellhor meus gastos</td>
            <td>Alta</td>
            <td>RF02</td>
        </tr>
        <tr>
            <td>US05</td>
            <td>Poder criar transaçoes com as labels que criei</td>
            <td>Poder visualizar mellhor meus gastos</td>
            <td>Alta</td>
            <td>RF03</td>
        </tr>
        <tr>
            <td>US06</td>
            <td>Poder alterar as labels das transações</td>
            <td>Poder visualizar mellhor meus gastos</td>
            <td>Alta</td>
            <td>RF03</td>
        </tr>
        <tr>
            <td>US07</td>
            <td>Poder deletar transações ja cadastradas</td>
            <td>caso ocorrar erros ou não deseje considerar aquela transação</td>
            <td>Alta</td>
            <td>RF03</td>
        </tr>
        <tr>
            <td>US08</td>
            <td>Poder ao abirir a aplicação,saber qual meu total de gastos</td>
            <td>poder organizar meus gastos futuros</td>
            <td>Alta</td>
            <td>RF04</td>
        </tr>
        <tr>
            <td>US09</td>
            <td>Poder, na aplicação, ver um grafico com meus gastos no decorrer no tempo</td>
            <td>poder organizar meus gastos futuros</td>
            <td>Media</td>
            <td>RF05</td>
        </tr>
        <tr>
            <td>US10</td>
            <td>que meus dados fiquem salvos na aplicação</td>
            <td>não ser necessario adicionar tudo sempre quer for usa-la</td>
            <td>Alta</td>
            <td>RF06</td>
        </tr>
        <tr>
            <td>US11</td>
            <td>que a aplicação me permita ver as labels por ordem de quantidade de gastos</td>
            <td>poder organizar meus gastos futuros</td>
            <td>Media</td>
            <td>RF07</td>
        </tr>
    </tbody>
</table>

## Ferramentas
Serão utilizadas as seguintes ferramentas para comunicação e organização do projeto:

<table>
  <tr>
    <th>Ferramenta</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td align="center"><img src="https://i.imgur.com/MbZSwsa.png" width="43" height="43"</td> 
    <td><i>Telegram</i> - Usado para comunicações rápidas entre os membros da equipe.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://i.imgur.com/N1ffmbM.jpg" width="81" height="46"</td>
    <td><i>Microsoft Teams</i> - Usado para reuniões entre os membros da equipe, bem como para a comunicação com o professor da disciplina.</td>
  </tr>
  <tr>
    <td align="center"><img src="https://i.imgur.com/Ft3ePbi.png" width="87" height="46"</td>
    <td><i>GitHub</i> - Usado para produzir os artefatos do projeto e realizar o versionamento do mesmo.</td>
  </tr>
</table>