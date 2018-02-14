<!-- Template do Documento de análise de viabilidade e riscos versão em Markdown-->
\<Nome do Projeto\>
===================

*[Observação: O template a seguir é adaptado a partir das normas ISO 15504 e ISO 12207, para uso dentro do processo de software da DroidFoundry. Todo texto escrito na seção 1 do documento inclusive o exibido entre colchetes e em itálico durante toda a extensão do documento foi incluído para orientar o autor e não deve ser usado na estruturação da Issue. Os tópicos existentes na seção 2 deverão ser utilizados da forma que melhor se adeque a solicitação de mudança.]*

Índice Analítico
----------------

* 1. [Introdução](#1-introdução)
* 2. [Análise de viabilidade e riscos](#2-análise-de-viabilidade-e-riscos)
    * 2.1 [Análise para código fonte](#21-análise-para-código-fonte)
    * 2.2 [Análise para documentação](#22-análise-para-documentação)
    * 2.3 [Análise para questões de projeto](#23-análise-para-questões-de-projeto)
* 3. [Análise de impacto](#3-análise-de-impacto)

Documento de Viabilidade e Riscos
--------------------------------------

## 1. Introdução

*[Uma análise de viabilidade e riscos oferece uma visão geral de um problema/melhoria reportada por meio de issues do GitHub. Ela inclui a forma utilizada na avaliação bem como as técnicas e etapas utilizadas para a sua correção. A análise de vialibilidade e riscos é elaborada em um comentário na mesma* *issue* *de solicitação de mudança.]*

## 2. Análise de viabilidade e riscos

*[A classificação de viabilidade verifica a viabilidade de uma mudança com base em atributos previamente estabelecidos, cada atributo possui um critério de avaliação que é utilizado para a adequação, o valor estipulado para a realização da mudança definido no [waffle.io](http://waffle.io/gabrielaimeeg/DroidMetronome) (parâmetro "Size") é obtido com uma métrica aonde no final o ****produto**** entre os atributos será definido como ***viável***, ***parcialmente viável***, ***Dificilmente viável*** e ***inviável***.]*

### 2.1. Análise para código fonte

#### Atributo 1: Áreas do produto afetadas

*[OBS.: Não será necessário realizar o resto da análise de viabilidade caso a mudança requerida seja classificada como OPCIONAL pois ela já será considerada ****VIÁVEL****.]*

| Atributo quanto ao risco no produto | Definição | Valor |
|-------------------------------------|-----------|-------|
| Mudança em funções **essenciais**   | Componente de software cuja existência é de vital importância para o produto | 3 |
| Mudança em funções **secundárias**  | Componente cuja existência é importante para o produto porém a sua falta não afeta a qualidade do sistema | 2 |
| Mudança em funções **opcionais**    | Uma modificação que afeta áreas triviais no produto | 2 |

##### Resultado estipulado ao atributo "Áreas do produto afetadas": *`[Escreva aqui o número que corresponde ao tipo da funcionalidade a ser modificada.]`*

#### Atributo 2: Tipo de mudança

| Atributo quanto ao tipo de mudança                           | Valor da medida |
|--------------------------------------------------------------|-----------------|
| Correção (A funcionalidade não funciona conforme o esperado) |        3        |
| Melhoria (A funcionalidade será otimizada)                   |        2        |
| Acréscimo (Uma nova funcionalidade será implementada)        |        1        |

##### Resultado estipulado ao atributo "Tipo de mudança": *`[Escreva aqui o número que corresponde ao tipo da mudança.]`*

#### Atributo 3: Tempo necessário

| Atributo quanto ao tempo necessário | Critério de avaliação | Valor da medida |
|-------------------------------------|-----------------------|-----------------|
|    Curto                            | Entre 1 e 3 horas     |        4        |
|    Médio                            | Entre 4 e 7 horas     |        3        |
|    Longo                            | Acima de 7 horas      |        2        |
|    Atrasado                         | Tempo expirado        |        1        |

##### Resultado estipulado ao atributo "Tempo necessário": *`[Escreva aqui o número que corresponde ao tempo gasto para a modificação.]`*

#### Atributo 4: Custo financeiro

| Custo financeiro da mudança | Critério de avaliação                      | Valor total |
|-----------------------------|------------------------------------------- |-------------|
| Sem custo                   | 0 R$                                       |      4      |
| Baixo custo                 | Entre de 1 R$ e 1000 R$                    |      3      |
| Médio custo                 | Entre de 1000 R$ e 1500 R$                 |      2      |
| Alto custo                  | Entre de 1500 R$ e 20% do custo do projeto |      1      |
| Altíssimo custo             | Acima de 20% do custo do projeto           |      0      |

##### Resultado estipulado ao atributo "Custo financeiro": *`[Escreva aqui o número que corresponde ao tempo gasto para a modificação.]`*

#### Classificação final

*[Se o Atributo 1 (Áreas do produto afetadas) teve como resultado "mudança em funções **opcionais**", use o seguinte texto abaixo, retirando as aspas e os asteriscos:*

*"Como a mudança solicitada afeta áreas triviais do produto de software, a mudança é considerada **Viável**."*

*Caso contrário, use o texto abaixo:]*

A classificação final da Análise de Viabilidade e Riscos é dada pelo produto dos resultados obtidos nos atributos acima, conforme a tabela abaixo:

| Classificação       | Valor total  |
|---------------------|--------------|
| Viável              |   81 - 144   |
| Parcialmente Viável |   48 - 80    |
| Dificilmente Viável |   24 - 47    |
| Inviável            | abaixo de 24 |  

##### Resultado da Análise de Viabilidade e Risco: *`[Resultado final obtido pela seguinte operação: Áreas do produto afetadas X Tipo de mudança X Tempo necessário X Custo financeiro.]`*

### 2.2. Análise para documentação

#### Atributo 1: Artefatos do projeto afetados

*[OBS.: Não será necessário realizar o resto da análise de viabilidade caso a mudança requerida seja classificada como OPCIONAL pois ela já será considerada ****VIÁVEL****.]*

| Atributo quanto ao risco no produto  | Definição | Valor  |
|--------------------------------------|-----------|--------|
| Mudança em artefatos **essenciais**  | Artefatos cuja existência é de vital importância para o processo (ex. planos gerenciais) | 3 |
| Mudança em artefatos **secundárias** | Artefatos cuja existência para o processo é especificado por artefatos essenciais (ex. tabelas, artefatos de processos, diagramas) | 2 |
| Mudança em artefatos **opcionais**   | Uma modificação que afeta áreas triviais no processo (ex. Ata de reunião) | 2 |

##### Resultado estipulado ao atributo "Artefatos do projeto afetados": *`[Escreva aqui o número que corresponde ao tipo do artefato a ser modificado.]`*

#### Atributo 2: Tipo de retificação

| Atributo quanto ao tipo de modificação | Valor da medida |
|----------------------------------------|---------|
| Correção (O artefato não está de acordo com normas e/ou PDS, ou apresenta erros graves) | 2 |
| Otimização (O artefato será melhorado) |    1    |

##### Resultado do atributo "Tipo de retificação": *`[O número que corresponde ao tipo da mudança.]`*

#### Atributo 3: Tempo necessário

| Atributo quanto ao tempo necessário | Critério de avaliação | Valor da medida |
|-------------------------------------|-----------------------|-----------------|
| Curto                               | Entre 1 e 3 horas     |        4        |
| Médio                               | Entre 4 e 7 horas     |        3        |
| Longo                               | Acima de 7 horas      |        2        |
| Atrasado                            | Tempo expirado        |        1        |

##### Resultado estipulado ao atributo "Tempo necessário": *`[O número que corresponde ao tempo gasto para a modificação.]`*

#### Classificação final

A classificação final é dada pelo produto dos resultados obtidos nos atributos acima, conforme a tabela abaixo:

| Tipo de viabilidade | Valor total |
|---------------------|-------------|
| Viável              |   12 - 24   |
| Parcialmente Viável |   4 - 11    |
| Inviável            | abaixo de 4 |  

##### Resultado de viabilidade: *`[Resultado final obtido pela seguinte operação: Artefatos do projeto afetados X Tipo de retificação X Tempo necessário.]`*

### 2.3. Análise para questões de projeto

*[Esta análise será feita para assuntos recorrentes ao projeto, entretanto que não possuam ligações diretas com artefatos produzidos no processo e/ou produto. Como por exemplo a entrada ou saída de um membro na equipe.]*

*[Será feita uma breve análise informal a respeito das áreas e artefatos que serão afetados. Em seguida essa análise será descrita juntamente com o tópico "Descrição da manutenção" presente na seção 3 "Análise de impacto".]*

## 3. Análise de impacto

### Descrição da manutenção:

*[Mudanças que deverão ser realizadas para solucionar a mudança solicitada.]*

### Áreas modificadas:

*[Áreas que serão afetadas diretamente pela mudança.]*

### Outras áreas afetadas:

*[Áreas que fazem referência as áreas modificadas.]*  
