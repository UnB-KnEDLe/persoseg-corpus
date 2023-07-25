# Source

Data extracted from the [Anotações - Atos de Pessoal](https://github.com/UnB-KnEDLe/datasets/blob/master/corpus_2_contratos_licitacoes.md) dataset, using data extracted from the Diário Oficial do Distrito Federal (DODF) using [DODFMiner](https://dodfminer.readthedocs.io/) and manually annotated by volunteers associated with the KnEDLe project.

# Dataset Information

Datasets with info about personnel related acts. The acts serve as sections of the document segmenation. These datasets were validated by members of the KnEDLe project.

## Attribute Information 

|    Attribute  | Description                               | 
|:-------------:|:-----------------------------------------:|
|type_act       | type of the act to which the text belongs |
|text           | text of the annotated act                 |
|n_dodf         | number of the DODF's edition              |
|day            | day the document was published            |
|month          | month the document was published          |
|year           | year the document was published           |

[More information](https://github.com/UnB-KnEDLe/tutorial_anotacao_contratos_licitacoes) about the annotation process and its labels.

# Version 0
**size:** 9058 rows

The acts considered and their respective labels are presented below:

|                   Act                   |              Label              | 
|:---------------------------------------:|:-------------------------------:|
|Abono de Permanênica                     | Ato_Abono_Permanencia           |
|Cessão                                   | Ato_Cessao                      |
|Exoneração Comissionado                  | Ato_Exoneracao_Comissionado     |
|Exoneração Efetivo                       | Ato_Exoneracao_Efetivo          |
|Nomeação Comissionado                    | Ato_Nomeacao_Comissionado       |
|Nomeação Efetivo                         | Ato_Nomeacao_Efetivo            |
|Retificação Comissionado                 | Ato_Retificacao_Comissionado    |
|Retificação Efetivo                      | Ato_Retificacao_Efetivo         |
|Reversão                                 | Ato_Reversao                    |
|Substituição                             | Ato_Substituicao                |
|Tornado Sem Efeito Apo                   | Ato_Tornado_Sem_Efeito_Apo      |
|Tornado Sem Efeito Exo/Nom               | Ato_Tornado_Sem_Efeito_Exo_Nom  |

## Number of Labeled Acts

|    Type                           | Quantity | 
|:---------------------------------:|:--------:|
| Ato_Abono_Permanencia             |       134|
| Ato_Cessao                        |       265|
| Ato_Exoneracao_Comissionado       |      2009|
| Ato_Exoneracao_Efetivo            |       241|
| Ato_Nomeacao_Comissionado         |      2313|
| Ato_Nomeacao_Efetivo              |        46|
| Ato_Retificacao_Comissionado      |       198|
| Ato_Retificacao_Efetivo           |      1214|
| Ato_Reversao                      |        58|
| Ato_Substituicao                  |      2312|
| Ato_Tornado_Sem_Efeito_Apo        |        20|
| Ato_Tornado_Sem_Efeito_Exo_Nom    |       248|
|Total                              |      9058|

## Files
- [CSV (**Public**) ](https://github.com/UnB-KnEDLe/persoseg-corpus/blob/main/data/persoseg_corpus_v0.csv)

# Version 1
**size:** 9058 rows

Difference between version 0 and 1: version 1 has label names in English.

The acts considered and their respective labels are presented below:

|                   Act                                 |                              Label              | 
|:-----------------------------------------------------:|:-----------------------------------------------:|
|Permanence Allowance                                   | Act_Permanence_Allowance                        |
|Cession                                                | Act_Cession                                     |
|Dismissal of Commissioned Position                     | Act_Dismissal_Commissioned                      |
|Dismissal of Effective Position                        | Act_Dismissal_Effective                         |
|Nomination of Commissioned Position                    | Act_Nomination_Commissioned                     |
|Nomination of Effective Position                       | Act_Nomination_Effective                        |
|Rectification of Comissioned Appointment               | Act_Rectification_Comissioned                   |
|Rectification of Effective Appointment                 | Act_Rectification_Effective                     |
|Reversal                                               | Act_Reversal                                    |
|Substitution                                           | Act_Substitution                                |
|Rendered Ineffective Retirement Acts                   | Act_Rendered_Ineffective_Retirement             |
|Rendered Ineffective Dismissal or Nomination Acts      | Act_Rendered_Ineffective_Dismissal_Nomination   |

## Number of Labeled Acts

|    Type                                          | Quantity | 
|:------------------------------------------------:|:--------:|
| Act_Permanence_Allowance                         |       134|
| Act_Cession                                      |       265|
| Act_Dismissal_Commissioned                       |      2009|
| Act_Dismissal_Effective                          |       241|
| Act_Nomination_Commissioned                      |      2313|
| Act_Nomination_Effective                         |        46|
| Act_Rectification_Comissioned                    |       198|
| Act_Rectification_Effective                      |      1214|
| Act_Reversal                                     |        58|
| Act_Substitution                                 |      2312|
| Act_Rendered_Ineffective_Retirement              |        20|
| Act_Rendered_Ineffective_Dismissal_Nomination    |       248|
|Total                                             |      9058|

## Files
- [CSV (**Public**) ](https://github.com/UnB-KnEDLe/persoseg-corpus/blob/main/data/persoseg_corpus_v1.csv)

# Relevant Papers
