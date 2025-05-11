# ANALISE_TEMPERATURA
Celsius para Fahrenheit com TensorFlow

🔥❄️ Implementação de Rede Neural para Conversão de Temperatura

Este projeto demonstra a implementação de uma rede neural utilizando TensorFlow
para converter temperaturas de Celsius para Fahrenheit.
Ao invés de programar diretamente a fórmula de conversão (F = C × 1.8 + 32),
o modelo aprende essa relação a partir de exemplos de treinamento.
Desenvolvido como parte da disciplina de Redes Neurais e Deep Learning,
este trabalho ilustra conceitos fundamentais de aprendizado de máquina e 
o paradigma de aprendizado por exemplos.

🎯 Objetivos

Construir um modelo preditivo utilizando redes neurais com TensorFlow
Treinar o modelo para descobrir a relação matemática entre Celsius e Fahrenheit
Visualizar o processo de treinamento e avaliar a precisão do modelo
Comparar as previsões do modelo com os valores calculados pela fórmula tradicional

🔧 Funcionalidades

Preparação e visualização dos dados de treinamento
Construção e treinamento de uma rede neural com TensorFlow
Análise do processo de aprendizado (histórico de loss)
Visualizações interativas dos resultados
Tabela comparativa entre valores previstos e reais
Análise de erros e desempenho do modelo

📊 Resultados

O modelo desenvolvido conseguiu aprender a relação entre as escalas Celsius
e Fahrenheit com alta precisão, apresentando:

Erro médio absoluto: ~0.15°F
Erro percentual médio: ~0.32%

As visualizações mostram que o modelo descobriu praticamente a mesma relação 
linear da fórmula tradicional (F = C × 1.8 + 32).

📂 Estrutura do Repositório

├── celsius_fahrenheit_neural_network.ipynb   # Notebook completo do projeto
├── modelo_tensorflow_celsius_fahrenheit.h5   # Modelo treinado salvo
├── visualizacoes/                            # Visualizações e gráficos gerados
│   ├── comparacao_modelo_vs_formula.png
│   ├── estatisticas_treinamento.png
│   └── distribuicao_erro.png
├── README.md                                 # Este arquivo
└── LICENSE   # Licença do projeto


💻 Como Executar

Abra o notebook no Google Colab 
[https://colab.research.google.com/github/seu-usuario/seu-repositorio/blob/main/celsius_fahrenheit_neural_network.ipynb](https://colab.research.google.com/drive/1UTxZTvK6GUUbfi7KKkrNWc3gsYmX73U0)
Execute todas as células do notebook sequencialmente
Experimente com os parâmetros e dados de teste para observar diferentes comportamentos do modelo


🧠 Conceitos Explorados

Arquitetura básica de redes neurais
Preparação de dados para treinamento
Definição e compilação de modelos no TensorFlow
Treinamento e ajuste de hiperparâmetros
Avaliação de desempenho do modelo
Visualização e interpretação de resultados


📈 Aplicações e Extensões

Embora este seja um exemplo simples e didático, os conceitos demonstrados podem ser expandidos para:

Problemas de predição mais complexos
Relações não-lineares entre variáveis
Modelos com múltiplas entradas e saídas
Análise de sensibilidade dos modelos de aprendizado

👨‍💻 Autor
Lucas Ribeiro Nepomuceno - GitHub

📄 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.






























