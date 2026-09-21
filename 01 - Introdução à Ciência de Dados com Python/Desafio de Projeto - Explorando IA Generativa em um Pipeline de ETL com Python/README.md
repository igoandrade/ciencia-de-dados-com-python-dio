# Explorando IA Generativa em um Pipeline de ETL com Python
---
## Desafio de Projeto - Módulo 01

* **Contexto**: Originalmente, o desafio de projeto compreendia o _consumo_ de uma API (_API da Santander Dev Week_) criada e disponibilizada para a atividade. Entretanto, tal API encontra-se indisponível no momento de exexução deste desafio. Considerando que o objetivo geral do desafio é o apresndizado do fluxo **ETL - _Extraction_ - (Extração), _Transformation_ (Transformação) e _Load_ (Carregamento)**, optou-se de utilizar outra API para desenvolvimento da atividade. 
* **Etapas** 

```
NASA API / JSON
      │
      ▼
   EXTRACT
      │
      ▼
     JSON
      │
      ▼
  TRANSFORM
      │
      ├── converter para DataFrame
      ├── corrigir tipos
      ├── tratar valores ausentes
      ├── criar latitude/longitude
      └── outras transformações
      │
      ▼
     LOAD
      │
      ├── 
      ├── 
      ├── 
      ├── CSV
      └── CSV
```