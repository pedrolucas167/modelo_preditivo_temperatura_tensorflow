O modelo é alimentado com pares de entrada/saída e aprende a prever os valores corretos.

---

## 🛠️ Tecnologias Utilizadas

- Python 3
- TensorFlow
- Google Colab
- Matplotlib

---

## 📊 Dados de Treinamento

| Celsius | Fahrenheit |
|---------|------------|
| -40     | -40        |
| -10     | 14         |
| 0       | 32         |
| 8       | 46.4       |
| 15      | 59         |
| 22      | 71.6       |
| 38      | 100        |

---

## 🧠 Modelo

- Tipo: Rede Neural Densa (Dense)
- Camadas: 1 camada com 1 neurônio (modelo simples)
- Otimizador: `Adam`
- Função de perda: `mean_squared_error`
- Épocas: 500

O modelo foi treinado para minimizar o erro entre os valores reais e preditos.

---

## 📈 Estatísticas de Treinamento

Um gráfico é gerado mostrando a **função de perda (loss)** ao longo das épocas de treinamento, evidenciando a evolução do modelo e a redução do erro.

---

## 📋 Testes com Novos Valores

Após o treinamento, o modelo foi testado com 10 novos valores em Celsius, gerando a tabela abaixo:

| Celsius | Valor Real (F) | Valor Predito (Modelo) |
|---------|----------------|-------------------------|
| -30     | -22.0          | -21.9                  |
| -20     | -4.0           | -4.2                   |
| 5       | 41.0           | 41.3                   |
| 10      | 50.0           | 50.4                   |
| 18      | 64.4           | 64.6                   |
| 25      | 77.0           | 77.2                   |
| 30      | 86.0           | 86.4                   |
| 40      | 104.0          | 104.1                  |
| 50      | 122.0          | 122.2                  |
| 100     | 212.0          | 212.5                  |

✅ O modelo apresentou excelente desempenho com **erro quase nulo**, provando que a rede neural aprendeu com sucesso a relação entre Celsius e Fahrenheit.

---

## 🚀 Como Executar

1. Acesse o [Google Colab](https://colab.research.google.com/)
2. Faça upload do notebook: `modelo_preditivo_temperatura_tensorflow.ipynb`
3. Execute todas as células do início ao fim
4. Analise os gráficos, predições e comparação de resultados

---

## 🧠 Aprendizado

Esta atividade ilustra como **redes neurais** podem aprender funções matemáticas simples a partir de exemplos, mesmo quando a fórmula é conhecida. É um excelente exercício introdutório para quem está começando com **machine learning e deep learning**.

---
