# 📊 Análise de Desempenho - Alura Store

Este projeto realiza uma análise comparativa do desempenho de 4 lojas da rede Alura Store, identificando qual unidade apresenta os piores indicadores e deveria ser considerada para venda.

## 🔍 Objetivo da Análise

Avaliar o desempenho das lojas com base em:
- Faturamento total e evolução temporal
- Satisfação dos clientes (avaliação média)
- Eficiência operacional (custos logísticos)
- Desempenho por categoria de produtos
- Retenção de clientes por cohort analysis

## 🛠 Tecnologias Utilizadas

- **Python** (Análise de dados)
- **Pandas** (Manipulação de dados)
- **Matplotlib/Seaborn** (Visualização)
- **Jupyter Notebook** (Análise interativa)

## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/alura-store-analysis.git

2. Instale as dependências:   
pip install -r requirements.txt

3. jupyter notebook AluraStore_Analise_Final.ipynb

## 📌 Principais Conclusões

**Recomendação:** Venda da **Loja 1**

**Motivos:**
- 🚨 **Maior custo operacional**: Frete 10.9% acima da média (R$34,69 vs R$33,14)
- 👎 **Pior satisfação**: Avaliação 3.98 (média de 4.02)
- 📉 **Baixa retenção**: 18% abaixo da Loja 3
- 📍 **Concentração geográfica**: 72% das vendas em SP (alto custo)

## 📈 Insights Chave

1. **Faturamento**:
   - Loja 1 lidera em volume (R$1.53M) mas com alta volatilidade
   - Loja 4 mostra crescimento consistente (+15% último trimestre)

2. **Satisfação**:
   - Loja 3 tem melhor avaliação (4.05)
   - Loja 1 com 25% mais reclamações que a média

3. **Categorias**:
   - Móveis lideram em todas as lojas (499 unidades na Loja 3)
   - Eletrônicos com sazonalidade acentuada (Q4 +20%)

## 📝 Meus Próximos Passos seriam:
1. Auditoria detalhada dos custos fixos da Loja 1

2. Pesquisa qualitativa com clientes da unidade

3. Modelagem de cenários pós-venda

4. Plano de migração para outras lojas