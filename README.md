# 🌪️ Análise e Previsão do Perfil Eólico - Delta do Maranhão

[![UNIFEI](https://img.shields.io/badge/UNIFEI-Institucional-blue)](https://unifei.edu.br/)
[![ANEEL](https://img.shields.io/badge/ANEEL-Parceria-green)](https://www.gov.br/aneel/pt-br)

Estudo abrangente do perfil eólico no Parque Eólico Delta do Maranhão, desenvolvido em parceria com a Universidade Federal de Itajubá (UNIFEI) e a Agência Nacional de Energia Elétrica (ANEEL). Este projeto combina análise exploratória avançada com modelagem preditiva de última geração para compreender e prever o comportamento do vento.

## 📊 Estrutura do Projeto

O estudo está dividido em duas partes complementares:

### [Parte 1: Análise Exploratória de Dados (EDA)](https://github.com/Perebati/EDA_WindProfile)

Investigação detalhada do perfil eólico, revelando:
- Correlação moderada entre velocidade e direção do vento
- Influência significativa da umidade relativa do ar na velocidade do vento
- Padrões cíclicos diários na velocidade do vento
- Definição da janela ideal de análise: 12 horas (72 índices)
- Forte correlação temporal entre t e t-72, validando a escolha da janela de análise

### [Parte 2: Modelo Preditivo](https://github.com/Perebati/Wind-Speed-Forecasting)

Implementação de um modelo de previsão avançado:
- Arquitetura Sequence-to-Sequence (Seq2Seq) com mecanismo de atenção
- Previsão de 6 horas à frente (36 índices)
- Capacidade comprovada de detecção de anomalias

#### Resultados Notáveis
- **MAE**: 0.1589 m/s (erro médio absoluto)
- **MSE**: 0.0447 (erro quadrático médio)
- **RMSE**: 0.2115 m/s (raiz do erro quadrático médio)

## 🎯 Objetivos Alcançados

1. **Compreensão Aprofundada**
   - Identificação de padrões climáticos
   - Correlações entre variáveis meteorológicas
   - Ciclos diários de velocidade do vento

2. **Previsão Precisa**
   - Horizonte de previsão de 6 horas
   - Alta precisão na detecção de anomalias
   - Métricas de erro excepcionalmente baixas

3. **Aplicação Prática**
   - Ferramenta para otimização operacional
   - Suporte à tomada de decisão
   - Monitoramento em tempo real

## 🔧 Como Utilizar

1. Clone o repositório com submódulos:
```bash
git clone --recursive https://github.com/seu-usuario/wind-profile-study.git
```

2. Acesse cada submódulo para instruções específicas:
- `cd EDA_WindProfile` para análise exploratória
- `cd Wind-Speed-Forecasting` para modelo preditivo

## 📚 Documentação

Cada submódulo contém documentação detalhada sobre:
- Metodologia aplicada
- Conjunto de dados utilizados
- Procedimentos de análise/modelagem
- Resultados e interpretações

## 🤝 Parcerias

Este projeto é resultado da colaboração entre:
- **UNIFEI**: Suporte acadêmico e metodológico
- **ANEEL**: Diretrizes regulatórias e aplicação prática
- **Parque Eólico Delta do Maranhão**: Fornecimento de dados e validação

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

*Desenvolvido como parte de uma iniciativa de pesquisa acadêmica em energia renovável, com foco em otimização de parques eólicos.*
