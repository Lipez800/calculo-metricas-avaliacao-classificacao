# Cálculo de Métricas de Avaliação de Classificação

## 🎯 Descrição do Projeto
Este projeto implementa o cálculo das principais métricas de avaliação para modelos de classificação de machine learning: Acurácia, Sensibilidade (Recall), Especificidade, Precisão e F-score. Parte do desafio de Avaliação de Modelos da Digital Innovation One (DIO).

## 🚀 Tecnologias Utilizadas
- Python 3.x
- NumPy para cálculos matemáticos
- Tabulate para formatação de tabelas (opcional)

## 📊 Funcionalidades Implementadas
- **Cálculo de Métricas**: Acurácia, Sensibilidade, Especificidade, Precisão e F-score
- **Matriz de Confusão**: Visualização dos valores VP, VN, FP, FN
- **Formatação Profissional**: Tabelas formatadas para fácil leitura
- **Tratamento de Erros**: Prevenção de divisão por zero
- **Testes com Diferentes Cenários**: Comparação de desempenho de modelos


## 🎓 Projeto Desenvolvido para Digital Innovation One (DIO)
Parte do desafio de Cálculo de Métricas de Avaliação de Aprendizado

## 📚 Métricas Calculadas

| Métrica | Fórmula | Descrição |
|---------|---------|-----------|
| **Acurácia** | (VP + VN) / N | Proporção de predições corretas |
| **Sensibilidade** | VP / (VP + FN) | Capacidade de detectar positivos |
| **Especificidade** | VN / (FP + VN) | Capacidade de detectar negativos |
| **Precisão** | VP / (VP + FP) | Confiabilidade das predições positivas |
| **F-score** | 2 × (P × S) / (P + S) | Média harmônica de Precisão e Sensibilidade |

## 🌟 **Sobre o Projeto:**

Este é um projeto educacional focado em ensinar como calcular e interpretar métricas de avaliação de modelos de classificação. Perfeito para iniciantes em machine learning que querem entender como avaliar a performance dos seus modelos.

O código é auto-contido em um único arquivo, tornando-o fácil de executar e entender!

## 🎯 Exemplo de Uso
```python
confusion_matrix = {
    'VP': 100,  # Verdadeiros Positivos
    'VN': 90,   # Verdadeiros Negativos  
    'FP': 10,   # Falsos Positivos
    'FN': 5     # Falsos Negativos
}

metrics = calculate_metrics(confusion_matrix) 
# Resultados: Acurácia=92.68%, Sensibilidade=95.24%, etc.
