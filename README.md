# 📊 Estudo de Caso: Qualidade de Dados & Suporte à Decisão

> 🚧 Projeto real com dados confidenciais anonimizados  
> ✅ Foco em análise, validação e padronização de dados para relatórios corporativos

---

## ⚡ Resumo do Projeto

Um cliente corporativo enfrentava dificuldades recorrentes com a qualidade dos dados em seus relatórios de preços, o que impactava diretamente a tomada de decisão. Os principais problemas incluíam erros de digitação, produtos incorretos, atrasos constantes e não conformidade com diretrizes mínimas de análise (como número de amostras por item).

Este projeto teve como foco **sanar essas falhas**, através de:
- **Validação automática dos dados** com SQL,
- **Padronização de nomes e preços improváveis**,
- **Monitoramento em tempo real da coleta**, usando Power BI,
- E **redução significativa de retrabalho**.

O resultado foi uma base confiável, prazos respeitados e maior confiança do cliente nos relatórios entregues.

---

## 🧠 Contexto do Projeto

Este estudo de caso trata de uma situação real enfrentada por um cliente corporativo, que relatava **problemas recorrentes com a qualidade dos dados** fornecidos em relatórios de preços. As falhas comprometiam a **tomada de decisão**, causavam **atrasos** e **desalinhamentos com diretrizes internas** de análise.

---

## ❗ Principais Problemas Identificados

### 🔹 1. Inconsistência nos Dados
- Erros de digitação em valores (ex: preços absurdos ou inválidos)
- Produtos incorretamente nomeados ou categorizados
- Dificuldade para comparar preços de produtos semelhantes

### 🔹 2. Atrasos nas Entregas
- Reprocessamento frequente dos dados
- Alterações constantes nos prazos
- Impacto negativo na agilidade de decisão do cliente

### 🔹 3. Não Conformidade com Diretrizes Internas
- Exigência de amostragem mínima (ex: 5 amostras por produto) não era cumprida
- Falta de acompanhamento em tempo real da entrada de dados
- Produtos com excesso de amostras e outros com ausência total

---

## 🎯 Objetivos do Projeto

✅ Melhorar a **precisão dos dados**  
✅ Reduzir o **retrabalho e atrasos nas entregas**  
✅ Implementar o **monitoramento automático de amostras**  
✅ Entregar **insights confiáveis para decisões estratégicas**

---

## 🧪 Soluções Aplicadas

✅ Criação de um script SQL para identificar:
- Preços fora de faixa aceitável por categoria de produto
- Produtos com nome divergente do padrão
- Linhas com campos obrigatórios ausentes

✅ Regra de bloqueio para registros com:
- Preços que estejam **40% acima ou 40% abaixo da mediana** do valor esperado por produto
- Valores nulos em campos obrigatórios
- Nomes genéricos (ex: “produto 1”, “teste”, etc.)

✅ Implementação de um dashboard no Power BI para:
- Visualizar em tempo real o volume de amostras por produto
- Sinalizar produtos fora do intervalo amostral ideal
- Acompanhar taxa de retrabalho e devolução de amostras

✅ Comunicação direta com o time de coleta para correções preventivas antes da etapa de análise

---

## 🛠️ Ferramentas Utilizadas

| Tecnologia | Aplicação |
|------------|-----------|
| **Power BI** | Dashboards interativos para monitoramento |
| **SQL** | Validação e tratamento dos dados |

---

## 🏁 Resultado

Como resultado das estratégias aplicadas:

- A entrega dos dados tornou-se mais limpa e confiável;
- Os dados utilizados pelo cliente passaram a ser realmente úteis para a tomada de decisão;
- O clima de tensão entre cliente e fornecedor foi solucionado;
- O projeto evoluiu, e o relacionamento com o cliente se fortaleceu consideravelmente.

---

## 🗂️ Estrutura do Repositório

.
├── README.md
├── dados/
│ └── base-anonimizada.csv
├── dashboards/
│ └── dashboard-preview.png
├── scripts/
│ └── validacao-precos.sql
├── relatorios/
│ └── resumo-executivo.pdf


---

## 👨‍💻 Autor

**André Romoaldo**  
Especialista em Análise de Dados & Business Intelligence  
📍 [LinkedIn](https://www.linkedin.com/in/andreromoaldo)

---
