# 📊 Análise de Desempenho Educacional no Brasil

## 🎯 Objetivo
Realizar uma análise exploratória de dados educacionais com foco em aprovação escolar e desempenho acadêmico (SAEB), transformando dados brutos em insights e automatizando a entrega de relatórios.

---

## ⚙️ Tecnologias Utilizadas
- Python (Pandas)
- Google Colab / Jupyter Notebook
- Selenium (automação web)
- SMTP (envio de email)

---

## 📁 Estrutura do Projeto

---

## 🔍 Etapas do Projeto

### 1. Coleta de Dados
- Importação de dados via Google Drive
- Leitura de arquivos CSV com Pandas

---

### 2. Limpeza e Tratamento
- Remoção de valores nulos e duplicados
- Padronização de colunas categóricas
- Conversão de tipos de dados
- Feature engineering:
  - Separação de `anos_escolares` em:
    - categoria (iniciais, finais, etc.)
    - faixa (ex: 1-5)

---

### 3. Análise Exploratória (EDA)

#### 📈 Evolução da taxa de aprovação
Identificação de tendências ao longo dos anos.

#### 🎓 Comparação entre níveis de ensino
Diferença estrutural entre ensino fundamental e médio.

#### 📚 Desempenho por disciplina
Análise comparativa entre matemática e língua portuguesa.

---

## 📊 Principais Insights

- A taxa de aprovação apresenta tendência de crescimento ao longo do tempo
- O ensino médio possui desempenho inferior ao fundamental
- Matemática apresenta desempenho mais baixo em relação à língua portuguesa

---

## 🤖 Automação de Relatórios

O projeto implementa duas abordagens:

### 🔹 SMTP (produção)
- Envio rápido e confiável
- Baixo consumo de recursos
- Ideal para pipelines automatizados

### 🔹 Selenium (RPA)
- Automação de interface web (Gmail)
- Simulação de comportamento humano
- Demonstração prática de automação

---

## ⚖️ Comparação das Abordagens

| Método    | Uso recomendado | Vantagens | Limitações |
|----------|---------------|----------|-----------|
| SMTP     | Produção      | Rápido, confiável | Limite de envio, configuração |
| Selenium | Demonstração  | Visual, flexível | Frágil, depende da interface |

---

## 🔐 Segurança

- Uso de senha de aplicativo para envio de email
- Recomenda-se uso de variáveis de ambiente para credenciais

---

## 💡 Conclusão

O projeto demonstra a capacidade de:
- Manipular e tratar dados reais
- Extrair insights relevantes
- Automatizar processos de ponta a ponta

---

## 📬 Contato

- GitHub: (coloque aqui)
