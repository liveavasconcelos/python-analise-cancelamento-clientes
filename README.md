# 📊 Análise de Cancelamento de Clientes

Este projeto realiza uma análise detalhada de uma base de dados de clientes, com o objetivo de identificar **padrões de cancelamento** de serviço. A partir da análise, são gerados **gráficos interativos** e **insights práticos** para ajudar a empresa a reduzir o número de cancelamentos por meio de ações estratégicas.

## 🎯 Objetivo

O projeto visa compreender **quem são os clientes que mais cancelam** e **quais características estão associadas ao cancelamento**. A ideia é transformar dados em **informações úteis** para que a empresa possa **agir proativamente**, criando estratégias como:

- Promoções personalizadas
- Alerta de retenção de clientes
- Intervenções do time de cobrança

---

## 🛠 Tecnologias Utilizadas

- Python
- Jupyter Notebook

### 📚 Bibliotecas
- `pandas`
- `openpyxl`
- `numpy`
- `nbformat`
- `plotly`
- `plotly.express`
- `ipykernel`

---

## 📁 Base de Dados

A base de dados foi fornecida no curso da [Hashtag Treinamentos](https://www.hashtagtreinamentos.com/).  
Ela contém os seguintes campos:

- `CustomerID`: ID do cliente  
- `idade`, `sexo`  
- `tempo_como_cliente`  
- `frequencia_uso`, `ligacoes_callcenter`, `dias_atraso`  
- `assinatura`, `duracao_contrato`, `total_gasto`, `meses_ultima_interacao`  
- `cancelou`: se o cliente cancelou ou não

---

## 📈 Principais Análises e Insights

1. **Cancelamento por ligações ao call center**  
   - Clientes que ligaram mais de 4 vezes **cancelaram o serviço**  
   🔔 *Insight:* Criar alerta ao atingir 3 ligações.

2. **Cancelamento por tipo de contrato**  
   - Todos os clientes com contrato **mensal** cancelaram  
   💡 *Insight:* Oferecer **desconto** nos planos anuais.

3. **Cancelamento por atraso de pagamento**  
   - Clientes com mais de 20 dias de atraso **cancelaram**  
   🚨 *Insight:* Alerta ao time de cobrança ao atingir 10 dias de atraso.

---

## ▶️ Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/python-analise-cancelamento-clientes.git
   ```
    
2. **Certifique-se de ter instalada a extensão do Jupyter**

3. **Instale as dependências:**
  ```bash
  pip install pandas openpyxl numpy plotly nbformat ipykernel
```

4. **Abra o arquivo inicial.ipynb**

## 💡 Sobre o Projeto
Este projeto foi desenvolvido durante o curso Imersão Python da Hashtag Treinamentos, com foco em problemas reais e aplicação prática da linguagem Python em Data Analysis.

## ✍️ Autora
Livea Mendes de Vasconcelos


