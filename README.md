# Ranking de municípios para receber empreendimentos

Análise fatorial que classifica os municípios brasileiros de acordo com o preparo para receber novos empreendimentos, com base em indicadores socioeconômicos e no tempo de abertura de empresas.

## Pergunta

Quais municípios oferecem as melhores condições para a abertura de novos negócios, considerando ao mesmo tempo o porte do município e a agilidade dos processos de registro?

## Dados

Base consolidada de indicadores municipais, incluindo:
- população do município
- tempo médio das etapas de abertura de empresas (viabilidade de localização, viabilidade de nome, cadastro e registro)
- indicadores socioeconômicos selecionados

## Método

1. Padronização das variáveis quantitativas (`StandardScaler`)
2. Redução de dimensionalidade com Análise de Componentes Principais (PCA)
3. Pontuação geral de cada município a partir dos componentes principais
4. Ranking dos municípios e visualização dos 20 mais e dos 20 menos preparados

## Tecnologias

Python · Pandas · NumPy · scikit-learn · Matplotlib · Google Colab

## Estrutura

```
analise_fatorial_municipios.ipynb   notebook com a análise completa
```

## Autora

Rita Farias · [LinkedIn](https://www.linkedin.com/in/rita-farias-b24a33232/)
