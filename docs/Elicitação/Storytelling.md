# Storytelling (Histórias)

## Introdução

_Storytelling_ são histórias narrativas sobre usuários. O objetivo dessa técnica é providenciar um exemplo mais claro das exigências e necessidades do usuário. Em uma narrativa, é mais fácil para a equipe de desenvolvimento entender as preferências e motivações de um usuário na utilização do software.

### Vantagens

- Participação ativa do cliente no processo de definição de requisitos.
- Contextualização dos requisitos em necessidades e objetivos reais dos usuários finais.
- Conteúdo criativo.

### Desvantagens

- Pode ser custoso e exigir tempo.
- Se a história não tiver uma situação ou personagens verossímeis, pode parecer forçada e conseguir o efeito contrário. 

## Metodologia

Para o desenvolvimento e realização do _storytelling_, foram utilizados clientes reais do Consumidor.gov, que aceitaram serem gravados ao contar suas histórias. Por fim, elencamos alguns dos requisitos.

## Storytelling

### O LED que não quer ligar

&emsp;&emsp; Mateus Vieira, estudante de Engenharia de Software, realizou a compra de um teclado no site Mercado Livre. A mercadoria chegou no prazo, porém o teclado veio com um defeito de fábrica no LED.Ao se deparar com esse defeito, Mateus tentou entrar em contato com a loja para que pudesse ser resolvida essa situação.

&emsp;&emsp; Mas mesmo assim, a equipe de suporte não respondeu suas tentativas de contato. Com isso,  Mateus viu o Consumidor.gov como uma esperança para resolver seu problema e fez uma reclamação no aplicativo. 

&emsp;&emsp; Depois de alguns dias, a loja respondeu o Mateus e propôs para que o produto fosse trocado por um novo, Mateus aceitou prontamente a proposta e depois de alguns dias seu teclado novo chegou e finalmente ele pôde utilizar ele para estudar (e jogar seu League of Legends).

A <i>Tabela 1</i> a seguir informa os dados do primeiro Storytelling, bem como a gravação do processo feito pelo usuário.

| Participante | Avaliador | Data | Horário | Local |
| :----------: | :-------: | :--: | :-----: | :---: |
| Mateus Vieira | Matheus Ferreira | 16/04/2024 | 19:17 | Microsoft Teams |

<figcaption align='center'> Tabela 1: Dados do StoryTelling 1 (Autor: MEISTER, Guilherme 2024)</figcaption>

<iframe width="750" height="422" src="https://youtube.com/embed/YSzEU-EsOt8" title="StoryTelling 1 Grupo 8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Vídeo 2: gravação do StoryTelling 2 (Autor: MEISTER, Guilherme 2024).

### A memória RAM com marcas de uso

&emsp;&emsp; Matheus Menezes Rodrigues, estudante de Engenharia de Software e entusiasta de jogos de FPS, gostaria de melhorar sua máquina para pode jogar Counter-Strike 2, jogo desenvolvido pela valve. Por isso, Matheus logo abriu o site da Magalu e fez o pedido de uma memória RAM ddr 4 de 8GB da marca HyperX. Mas após o produto chegar em sua casa, Matheus percebeu que estava com algumas marcas.

&emsp;&emsp; Mas mesmo assim, preferiu testar antes de fazer qualquer reclamação, dito e feito, a memória RAM não funcionava. Matheus entrou em contato com o SAC do Magalu, mas obteve dias sem respostas que fizessem ele achar que algo fosse ser resolvido. Desta forma, Matheus decidiu baixar e utilizar o Consuimidor.gov.

&emsp;&emsp; Então, Matheus verificou se a loja participava do app e logo fez suas reclamações, anexando fotos, vídeos e mostrando que o seu produto veio com defeito. Após isso, ele ficou acompanhando seu processo durante algumas semanas, o que resultou em uma resposta positiva da empresa em trocar seu produto. E hoje Matheus segue a vida com seu computador que roda Couter-Strike 2.

A <i>Tabela 2</i> a seguir informa os dados do segundo Storytelling, bem como a gravação do processo feito pelo usuário.

| Participante | Avaliador | Data | Horário | Local |
| :----------: | :-------: | :--: | :-----: | :---: |
| Matheus Menezes | Guilherme Meister | 16/04/2024 | 22:24 | Microsoft Teams |

<figcaption align='center'> Tabela 2: Dados do StoryTelling 2 (Autor: MEISTER, Guilherme 2024)</figcaption>

<iframe width="750" height="422" src="https://youtube.com/embed/Pls15d-WQQc" title="StoryTelling 2 Grupo 8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Vídeo 2: gravação do StoryTelling 2 (Autor: MEISTER, Guilherme 2024).


## Requisitos Elicitados

&emsp;&emsp;Com base nas histórias contadas no storytelling, foram elicitados os requisitos presentes na tabela 3:


| Identificador | Descrição                                                                          | Tipo | Implementado | Usuário |
| ------------- | ---------------------------------------------------------------------------------- | ---- | ------------ | ------- |
|       ST01    |   Eu, como usuário, gostaria de fazer reclamações acerca de um produto específico.                                |  RF  | Sim          | Todas |
| ST02          | Eu, como usuário, gostaria de acompanhar do status da reclamação.                      | RF   | Sim          | Todas |
| ST03          | Eu, como usuário, gostaria de resolver os conflitos pelo aplicativo.             | RF   | Sim          | Todas |
| ST04          | Eu, como usuário, gostaria de visualizar o histórico de reclamações de uma empresa.     | RF   | Não          | Todas |
| ST05          | Eu, como usuário, gostaria de visualizar uma avaliação de empresas.                    | RF   | Sim          | Matheus Menezes |
| ST06          | Eu, como usuário, gostaria de tempos de resposta rápidos para garantir uma experiência de usuário satisfatória.                       | RNF   | Não          | Mateus Vieira |
| ST07          | Eu, como usuário, gostaria de anexar arquivos nas reclamações.        | RF  | Sim          | Todas |
| ST08          | Eu, como usuário, gostaria de uma interface acessível com contraste de cor .                                | RNF   | Sim          | Matheus Menezes|
| ST09          | Eu, como usuário, gostaria de que o aplicativo tenha suporte ao usuário. | RNF | Não          | Mateus Vieira |
| ST10          | Eu, como usuário, gostaria de que o aplicativo tenha tutorial.                | RF   | Não          | Mateus Vieira |
| ST11          | Eu, como usuário, gostaria de que o aplicativo seja facilmente acessível.                              | RNF   | Sim          | Todas |
| ST12          | Eu, como usuário, gostaria de realizar registro/login em uma conta.                                       | RF   | Sim          | Todas |

<div style="text-align: center">
<p> Tabela 3: Requisitos elicitados com o Storytelling (Autor: MEISTER, Guilherme 2024).</p>
</div>

**Legenda:**

- ST: Requisitos de <span>_Storytelling_</span>
- RF: Requisitos <span>Funcionais</span>
- RNF: Requisitos não <span>Funcionais</span>

## Bibliografia

[1] Santos, V. G., Daher N., UTILIZAÇÃO DE STORYTELLING COMO FERRAMENTA DE AQUISIÇÃO DE REQUISITOS EM PROCESSO DE DESENVOLVIMENTO DE SOFTWARE APOIADOS EM MODELOS ÁGEIS: O USO APOIADO NO EXTREME PROGRAMMING, Belo Horizonte, 2008. 14 p., Artigo (Análise de Sistemas), e-tec UNI-BH

[2] Storytelling do Grupo VLC de 2022.1. Disponível em: <https://github.com/Requisitos-de-Software/2023.1-VLC/>. Acesso em: 15 de abril de 2024.

[3] Guia Facetado de Engenharia de Requisitos REtraining. Disponível em: <https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-historias-de-usuario>. Acesso em : 22 de abril de 2024. 

## Histórico de Versão
| Versão | Data          | Descrição           | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 04/04/2024 | Criação do documento | [Guilherme Meister](https://github.com/gmeister18) e [Matheus Ferreira](https://github.com/matferreira1) | [Henrique Galdino](https://github.com/hgaldino05) e [Rodrigo ](https://github.com/rodrigogontijoo) |
| `1.1`  | 17/04/2024 | Mudança nas histórias | [Guilherme Meister](https://github.com/gmeister18) e [Matheus Ferreira](https://github.com/matferreira1) | [Henrique Galdino](https://github.com/hgaldino05) e [Rodrigo ](https://github.com/rodrigogontijoo) |
| `1.2`  | 22/04/2024 | Ajustes gerais | [Guilherme Meister](https://github.com/gmeister18) e [Matheus Ferreira](https://github.com/matferreira1) | [Henrique Galdino](https://github.com/hgaldino05) e [Rodrigo ](https://github.com/rodrigogontijoo) |
