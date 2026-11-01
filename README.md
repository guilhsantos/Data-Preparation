# Preparação de dados para modelagem

Pipeline em Python que limpa, enriquece e integra três bases de projetos, campanhas e apoiadores em uma tabela única, pronta para modelos preditivos.

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guilhsantos/Data-Preparation/blob/main/DataPreparationPratica.ipynb)

## Problema

Os dados de projetos, campanhas e investimentos estavam em três arquivos separados, com tipos inconsistentes, colunas sem uso e valores faltando. Assim, nenhum modelo pode ser treinado.

## Solução

Um notebook que carrega `DataPrepFinal.csv`, `campaign.csv` e `invested.csv`, padroniza cada um e os une em um único conjunto consistente.

## Resultado

Uma base única e limpa, com tipos corretos, sem colunas intermediárias e com atributos novos, como a duração de cada projeto (`time_range`).

## Como fiz

1. **Limpeza:** remoção de colunas irrelevantes, ajuste de tipos e tratamento de nulos.
2. **Enriquecimento:** criação de atributos derivados, como `time_range`.
3. **Integração:** merge das campanhas e dos apoiadores na tabela de projetos.
4. **Ajustes finais:** remoção de colunas intermediárias e checagem de consistência.

Feito na aula de Data Preparation da formação Cientista de Dados (DNC).

## Stack

Python · pandas · Google Colab

---

Feito por [Guilherme Santos](https://portifolio-guilherme-santos.vercel.app) · [LinkedIn](https://www.linkedin.com/in/guilherme-santos-dataeng)
