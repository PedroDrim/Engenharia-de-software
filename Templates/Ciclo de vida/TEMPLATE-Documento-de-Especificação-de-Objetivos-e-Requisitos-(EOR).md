<!-- Template de Documento de Especificação de requisitos de Software versão em Markdown-->
\<Nome do Projeto\>
===================

Índice Analítico
-----------------

Incluir índice de conteúdo do documento que estiver sendo elaborado
* 1. [Introdução](#1-introdução)	
    * 1.1 [Objetivos](#11-objetivos)	
    * 1.2 [Público Alvo](#12-público-alvo)	
    * 1.3 [Organização do documento](#13-organização-do-documento)	
    * 1.4 [Definição de Siglas e Nomenclaturas](#14-definição-de-siglas-e-nomenclaturas)	
* 2. [Descrição do problema e do sistema](#2-descrição-do-problema-e-do-sistema)
    * 2.1 [Identificação e missão do Sistema](#21-identificação-e-missão-do-sistema)	
    * 2.2 [Domínio do problema e contexto de sua aplicação](#22-domínio-do-problema-e-contexto-de-sua-aplicação)	
    * 2.3 [Descrição dos interessados do sistema](#23-descrição-dos-interessados-do-sistema)	
* 3. [Requisitos e restrições não funcionais](#3-requisitos-e-restrições-não-funcionais)
    * 3.1 [Requisitos e Restrições de Usabilidade (RUS)](#31-requisitos-e-restrições-de-usabilidade-rus)	
    * 3.2 [Requisitos e Restrições de Interface Homem-Computador (RHIC)](#32-requisitos-e-restrições-de-interface-homem-computador-rhic)	
    * 3.3 [Requisitos e Restrições de Interface Externa (RIEX)](#33-requisitos-e-restrições-de-interface-externa-riex)	
    * 3.4 [Requisitos e Restrições de Plataforma de Hardware (RPHW)](#34-requisitos-e-restrições-de-plataforma-de-hardware-rphw)	
    * 3.5 [Requisitos e Restrições de Plataforma de Software (RPSW)](#35-requisitos-e-restrições-de-plataforma-de-software-rpsw)	
    * 3.6 [Requisitos e Restrições de Desempenho (RDES)](#36-requisitos-e-restrições-de-desempenho-rdes)	
    * 3.7 [Requisitos e restrições de disponibilidade (RDIS)](#37-requisitos-e-restrições-de-disponibilidade-rdis)	
    * 3.8 [Requisitos e Restrições de Segurança (RSEG)](#38-requisitos-e-restrições-de-segurança-rseg)	
    * 3.9 [Requisitos e Restrições de Manutenibilidade (RMAN)](#39-requisitos-e-restrições-de-manutenibilidade-rman)	
    * 3.10 [Requisitos e Restrições de Documentação (RDOC)](#310-requisitos-e-restrições-de-documentação-rdoc)
* 4. [Casos de Uso e Requisitos Funcionais](#4-casos-de-uso-e-requisitos-funcionais)	
    * 4.1 [Diagramas de Caso de Uso e Lista de casos de uso](#41-diagramas-de-caso-de-uso-e-lista-de-casos-de-uso)	
    * 4.2 [Descrição de Casos de Uso](#42-descrição-de-casos-de-uso)	
* 5. [Requisitos Futuros (RFUT)](#5-requisitos-futuros-rfut)	
* 6. [Referências cruzadas complementares](#6-referências-cruzadas-complementares)	
* 7. [Aprovação Formal](#7-aprovação-formal)	
* 8. [Bibliografia](#8-bibliografia)	
* 9. [Anexos](#9-anexos)	

## 1. Introdução

[_Esta seção deverá apresentar o documento ao leitor. O objetivo principal da introdução é descrever o documento e não o sistema, embora deva ser mencionado qual é o sistema e para qual empresa ou mercado ele será construído. O conteúdo a ser coberto na introdução está descrito nas subseções seguintes._]

### 1.1 Objetivos

[_Definir os objetivos do documento._

_Exemplo:_
_Este documento tem os seguintes objetivos:_

•	_Definir os interessados no sistema e as suas necessidades que devem ser satisfeitas pelo sistema a ser desenvolvido;_

•	_Derivar os casos de uso e requisitos do sistema de forma a orientar a equipe de que será responsável pelo seu desenvolvimento;_	

•	_Estabelecer um contrato para negociação e concordância entre todos os interessados;_	

•	_Reduzir retrabalho com projeto, codificação e teste através da especificação rigorosa e completa dos requisitos;_	

•	_Prover uma base para avaliação de prazos e custos de desenvolvimento;_

•	_Facilitar a transferência dos produtos do desenvolvimento para novos usuários, novos clientes, novos ambientes operacionais e novas equipes de desenvolvimento e manutenção;_

•	_Prover uma base para a evolução futura do sistema a partir de uma versão aprovada (linha de base) deste documento._
]

### 1.2 Público Alvo

[_Identificar o público alvo do documento, isto é, todos os perfis de pessoas que terão interesse na sua leitura. Os interesses de cada perfil na leitura do documento também devem ser descritos._]

### 1.3 Organização do documento

[_Descrever suscintamente a organização do documento em seções e o conteúdo de cada seção. Não há necessidade de descer ao nível de subseções._]

### 1.4 Definição de Siglas e Nomenclaturas

[_Definir e explicar sucintamente siglas e nomencalturas utilizadas neste documento._]

## 2. Descrição do problema e do sistema
-----------------------------------------

[_Nesta seção o sistema objeto da especificação de requisitos deve ser descrito. O domínio do problema que deverá ser resolvido pelo sistema deve ser explicado e também as características específicas do problema no contexto da empresa em que o sistema deverá ser utilizado._

_As subseções seguintes podem ser colocadas no documento EOR para separar cada conteúdo específico, mas também pode ser usado um estilo de texto sem separação de subseções desde que todo o conteúdo seja coberto._]

### 2.1 Identificação e missão do Sistema

[_Identificar o sistema objeto da especificação de requisitos e definir em poucas palavras qual é a missão do sistema que está sendo considerado neste documento._]

### 2.2 Domínio do problema e contexto de sua aplicação

[_A descrição do domínio do problema deve complementar e detalhar a visão geral do domínio do problema identificando o contexto deste problema no ambiente alvo (ambiente do cliente alvo)._]

_Exemplo:_

_Suponha que o domínio do problema seja a venda de produtos em um comércio varejista. Esta seção deverá explicar em que consiste o problema de vender produtos em uma empresa que atua no comércio varejista, ou seja, descrever genericamente quais são os processos de negócio envolvidos e seus objetivos. Além disso, o problema deve ser contextualizado mostrando as características específicas do problema na empresa alvo._]

### 2.3 Descrição dos interessados do sistema

[_Descrever os perfis de cada interessado envolvido com o sistema._]

| [_Interessado(s)_] | Descrição |
|--------------------|-----------|
| [_Nome do perfil do interessado. Por exemplo: (cliente, atendente, vendedor, gerente comercial, etc.)_] | [_Descrever o perfil do interessado e como se espera que seja sua interação com o sistema direta ou indiretamente. Por exemplo, o vendedor da loja é a pessoa que atende os clientes e registra as vendas que são feitas._] |

## 3. Requisitos e restrições não funcionais 
--------------------------------------------

[_Elaborar uma lista de todos os requisitos não funcionais. Considerar requisitos de informação, de interface, de projeto, de arquitetura de software, de plataforma de hardware, de plataforma de software, de plataforma de comunicação, de desempenho, de disponibilidade, de segurança, de manutenibilidade, de portabilidade e de documentação._

_A lista poderá ser dividida por tipo de requisito, mas é importante que os requisitos tenham uma identificação única para que possam ser referenciados sem ambigüidades no futuro._]

### 3.1 Requisitos e Restrições de Usabilidade (RUS)

[_Elaborar uma lista de todas as necessidades de informação que o software não pode deixar de atender. Esta lista deverá ser classificada em informações cadastrais e informações gerenciais. Por exemplo, para um software de vendas existem, entre outras, as seguintes necessidades de informação:_

_Exemplo:_

| Ref. | Descrição | Caso de Uso |
|------|-----------|-------------|
| [_RINFx_] | [_Descrição do requisito RINFx_]  | [_CSUy, CSUm ..._]  |

[_Estes requisitos de informação são importantes para verificar a qualidade da modelagem de dados que for feita._]

### 3.2	Requisitos e Restrições de Interface Homem-Computador (RHIC)

[_Definir os aspectos de Interface Homem Computador (IHC) como: conteúdo de informações, fatores ergonômicos, dispositivos de interação, formato de apresentação, tipo de diálogo, e mecanismos de ajuda alocados a cada perfil/grupo/tarefa de usuário._

_Descrever, em particular, os requisitos de usabilidade para cada perfil/grupo/tarefa de usuário. Por exemplo, pode-se definir como requisito que as opções de menu do sistema tenham teclas de atalho associadas._

_Exemplo:_

| Ref. | Descrição | Caso de Uso |
|------|-----------|-------------|
| [_RIHCx_] | [_Descrição do requisito RIHCx_] | [_CSUy, CSUm ..._] |

### 3.3 Requisitos e Restrições de Interface Externa (RIEX)

[_Identificar e descrever as interfaces com outros softwares/sistemas que o software deverá prover. Por exemplo, um software comercial deve gerar informações para o Sistema de Arrecadação da Secretaria da Fazenda Estadual._

_O formato dessas informações e o protocolo de envio são definidos pela própria secretaria, e atender essas definições é um requisito do software._

_Exemplo:_

| Ref. | Descrição | Caso de Uso |
|------|-----------|-------------|
| [_RIEXx_] | [_Descrição do requisito RIEXx_] | [_CSUy, CSUm ..._] |

### 3.4 Requisitos e Restrições de Plataforma de Hardware (RPHW)

[_Identificar e descrever requisitos e restrições relacionadas com a plataforma de hardware que será utilizada pelo software:_]

_Exemplo:_

| Ref. | Descrição | Caso de Uso |
|------|-----------|-------------|
| [_RPHWx_] | [_Descrição do requisito RPHWx_] | [_CSUy, CSUm ..._] |

### 3.5 Requisitos e Restrições de Plataforma de Software (RPSW)

[_Se o software tiver que ser executado em plataformas de software específicas, essas plataformas de software deverão ser definidas:_

1. [_Sistema Operacional: identificar e descrever o sistema operacional em que o software deverá ser executado;_]

2. [_Softwares Básicos: identificar SGBD, linguagem de programação, ferramentas CASE e outros.
Se houver mais de uma plataforma de software, deve-se especificar qual a plataforma principal e em que situações as outras plataformas podem ser utilizadas._]

_Exemplo:_

| Ref. | Descrição | Caso de Uso |
|------|-----------|-------------|
| [_RPSWx_] | [_Descrição do requisito RSPWx_] | [_CSUy, CSUm ..._] |

### 3.6 Requisitos e Restrições de Desempenho (RDES)

[_Identificar e descrever os requisitos e restrições de desempenho do software._

_Exemplo:_

| Ref. | Descrição | Caso de Uso |
|------|-----------|-------------|
| [_RDESx_] | [_Descrição do requisito RDESx_] | [_CSUy, CSUm ..._] |

### 3.7 Requisitos e restrições de disponibilidade (RDIS).

[_Especificar os requisitos de disponibilidade necessários para o software de uma forma global:

1. [_Período de disponibilidade: horário comercial, 24 horas por dia, etc._]

2. [_Período máximo para recuperação do software em caso de falha._]

[_Devem ser definidos os tipos de falha e a tolerância aceitável para cada tipo de falha. Os tipos de falha podem ser definidos em função dos requisitos funcionais e de dados, mas não se restringem a estes._ 

_Por exemplo: a função “Registrar Venda” deve ter um tempo para recuperação de falha de no máximo uma hora (o que significa que esta função não poderá ficar mais do que uma hora indisponível para o usuário em nenhuma circunstância)._]

_Exemplo:_

| Ref. | Descrição | Caso de Uso |
|------|-----------|-------------|
| [_RDISx_] | [_Descrição do requisito RDISx_] | [_CSUy, CSUm ..._] |

### 3.8 Requisitos e Restrições de Segurança (RSEG)

[_Especificar os requisitos de segurança necessários para controle de acesso ao software. Definir a necessidade, por exemplo, de:_

1. _Verificação de senha;_

2. _Criptografia de dados;_

3. _Registro das operações efetuadas;_

4. _Habilitação de funções por perfil de usuário;_

5. _Acesso seletivo aos dados e funções._

_Exemplo:_

| Ref. | Descrição | Caso de Uso |
|------|-----------|-------------|
| [_RSEGx_] | [_Descrição do requisito RSEGx_] | [_CSUy, CSUm ..._] |

### 3.9 Requisitos e Restrições de Manutenibilidade (RMAN)

[_Especificar os requisitos que visam facilitar a manutenção posterior do software, tais como:_

1. _Requisitos de reutilização (exemplo: uso de implementação orientada a objetos; bibliotecas de classes e padrões de projeto);_

2. _Requisitos de modularização (exemplo: valores para métricas de acoplamento entre módulos; máximo de pontos de função por módulo);_

3. _Requisitos de configuração (exemplo: regras para controle de versões);_

4. _Requisitos de documentação (exemplo: documentação de programa)_

_Exemplo:_

| Ref. | Descrição | Caso de Uso |
|------|-----------|-------------|
| [_RMANx_] | [_Descrição do requisito RMANx_] | [_CSUy, CSUm ..._] |

### 3.10 Requisitos e Restrições de Documentação (RDOC)

[_Especificar os requisitos de documentação do produto de software que será desenvolvido._

_Exemplo:_

| Ref. | Descrição | Caso de Uso |
|------|-----------|-------------|
| [_RDOCx_] | [_Descrição do requisito RDOCx_] | [_CSUy, CSUm ..._] |

## 4. Casos de Uso e Requisitos Funcionais
---------------------------------

### 4.1 Diagramas de Caso de Uso e Lista de casos de uso

![](http://postimg.org/image/skrz04i6x/)

### 4.2 Descrição de Casos de Uso

**CSUx**- [_Nome do caso de uso_]
	Ator(es): [_Usuário_]
	Descrição: [_Breve descriçao do caso de uso_]
	Requisitos Funcionais:

| Ref. | Descrição | Categoria | Prioridade |
|------|-----------|-----------|------------|
| [_RFUNx_] | [_Descrição do requisito funcional_] | [_Evidente | Alta_] |

## 5. Requisitos Futuros (RFUT)
---------------------------------

[_Este espaço é reservado para o surgimento de futuros requisitos._

| Ref. | Descrição | Caso de Uso |
|------|-----------|-------------|
| [_RFUTx_] | [_Descrição do requisito RFUTx_] | [_CSUy, CSUm ..._] |

## 6. Referências cruzadas complementares 
---------------------------------------------

[_Nesta seção são colocadas algumas referências cruzadas que podem ajudar o rastreamento futuro dos requisitos. Estes mapeamentos podem ser feitos em forma de matrizes de rastreabilidade como mostram os exemplos a seguir:_

| Requisitos Funcionais | Requisitos Não-Funcionais |
|-----------------------|---------------------------|
| [_Colocar identificação do requisito funcional_] | [_Colocar a identificação do requisito não funcional vinculado_] |

| Requisitos Funcionais | Origem do Requisito |
|-----------------------|---------------------|
| [_Colocar identificação dos requisitos funcionais_] | [_Colocar a origem do requisito. Pode ser uma entrevista, um questionário, ou outra técnica qualquer de elicitação de requisito aplicada._] |

| Requisitos Não-Funcionais | Origem do Requisito |
|---------------------------|---------------------|
| [_Colocar identificação dos requisitos não-funcionais_] | [_Colocar a origem do requisito. Pode ser uma entrevista, um questionário, ou outra técnica qualquer de elicitação de requisito aplicada._] |

| Casos de Uso | Origem do Caso de Uso |
|--------------|-----------------------|
| [_Colocar a identificação do requisito funcional_] | [_Colocar a origem do caso de uso. Pode ser uma entrevista, um questionário, ou outra técnica  qualquer de elicitação de requisito aplicada._] |

## 7. Aprovação Formal 
---------------------------------------------

[_Exemplo:_

_Por meio deste documento, confirmo que os requisitos aqui presentes abordam todas as áreas do sistema a ser desenvolvido e de requisitos futuros (sejam elas melhorias ou novas funcionalidades), de forma a desenvolver um software com qualidade e segurança. Confirmo também que este documento aborda todos os requisitos e funcionalidades de forma correta e clara ao que foi solicitado e ao que foi dito e pedido nas entrevistas, etnografias e questionários. Confirmo também que não há requisitos extras neste documento, todos os requisitos aqui citados foram requeridos e atendem à alguma funcionalidade necessária._]