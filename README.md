![image](https://github.com/user-attachments/assets/5988aea5-557f-4fc3-8ffd-a1e13f683fa4)
📌 Visão Geral
O projeto utiliza dados de vendas de quatro lojas diferentes para gerar insights estratégicos. Através de análise exploratória e visualização de dados, identificamos:

Faturamento por loja

Custo médio de frete

Avaliação dos clientes

Produtos mais vendidos

Categorias com melhor desempenho

Objetivo principal: Determinar qual loja tem o pior desempenho e justificar por que ela deve ser vendida, enquanto as outras são mantidas.

📊 Principais Resultados
1. Comparativo Geral entre Lojas
Métrica	Loja 1	Loja 2	Loja 3	Loja 4 (Melhor)
Faturamento	Médio	Baixo	Alto	Melhor
Frete Médio	Alto	Médio	Baixo	Baixo
Avaliação	4.5 ⭐	4.2 ⭐	4.7 ⭐	4.8 ⭐
Produto Top	Eletrônicos	Livros	Moda	Eletrônicos
Categoria	Tecnologia	Educação	Vestuário	Tecnologia
2. Conclusão da Análise
Loja 4 é a melhor em desempenho geral (faturamento, avaliação e frete baixo).

Loja 2 tem o pior desempenho (menor faturamento, avaliação mais baixa e categoria menos lucrativa).

Recomendação: Vender a Loja 2 e reinvestir nas demais, especialmente na Loja 4.

🛠 Como Executar o Projeto
Pré-requisitos
Google Colab ou Jupyter Notebook

Bibliotecas Python: pandas, matplotlib, numpy

Passo a Passo
Abrir o Notebook no Google Colab:

Basta clicar no link do arquivo .ipynb no GitHub e selecionar "Abrir no Colab".

Instalar Dependências (se necessário):

python
!pip install pandas matplotlib numpy
Executar as Células:

O notebook está dividido em:

Carga dos dados (CSV das lojas)

Análise exploratória (faturamento, avaliações, fretes)

Visualização (gráficos comparativos)

Conclusões e recomendações

Gerar Novos Gráficos (Opcional):

Modifique as variáveis ou adicione novas visualizações conforme necessário.

📂 Estrutura do Repositório
📁 projeto-lojas/
├── 📄 analise_lojas.ipynb          # Notebook principal (Google Colab/Jupyter)
├── 📄 README.md                    # Este arquivo
├── 📁 dados/                       # Dados brutos (CSV)
│   ├── loja_1.csv
│   ├── loja_2.csv
│   ├── loja_3.csv
│   └── loja_4.csv
└── 📁 graficos/                    # Imagens geradas (opcional)
📌 Insights para Tomada de Decisão
Loja 4 → Mantida e expandida (melhor desempenho em tudo).

Loja 2 → Vendida (justificativa: baixo faturamento e avaliação inferior).

Lojas 1 e 3 → Otimizadas (melhorar frete da Loja 1 e estoque da Loja 3).

🔍 Próximos Passos
Adicionar análise sazonal (vendas por mês).

Implementar dashboard interativo (Streamlit/Power BI).

Desenvolver modelo de previsão de demanda.
