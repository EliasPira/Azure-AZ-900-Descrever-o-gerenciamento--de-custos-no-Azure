# ☁️ Azure Cost Management — Guia Completo

<p align="center">
  <img src="https://img.shields.io/badge/Azure-Cost%20Management-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Ativo-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Documentação-Microsoft-blue?style=for-the-badge" />
</p>

---

## 📘 Sobre este Repositório

Este repositório reúne um resumo completo e estruturado do módulo **“Describe Cost Management in Azure”** da Microsoft Learn.  
Aqui você encontrará:

- Como os custos funcionam no Azure  
- Fatores que influenciam o consumo  
- Ferramentas de estimativa e controle  
- Comparação entre Pricing Calculator e TCO Calculator  
- Uso do Microsoft Cost Management  
- Boas práticas de FinOps  

---

## 🧭 Sumário

- [Introdução](#introdução)
- [Fatores que Afetam os Custos](#fatores-que-afetam-os-custos)
- [Calculadoras de Estimativa](#calculadoras-de-estimativa)
- [Ferramentas de Gerenciamento](#ferramentas-de-gerenciamento)
- [Boas Práticas de FinOps](#boas-práticas-de-finops)
- [Recursos Oficiais](#recursos-oficiais)
- [Licença](#licença)

---

## 🟦 Introdução

O Azure oferece um conjunto robusto de ferramentas para **prever, monitorar e otimizar custos**.  
O objetivo deste guia é ajudar você a entender:

- Como os custos são gerados  
- Como estimar gastos antes da implantação  
- Como monitorar e otimizar o consumo real  
- Como aplicar governança financeira (FinOps)  

---

## 🧩 Fatores que Afetam os Custos

Os principais fatores que influenciam os custos no Azure incluem:

### **1. Tipo de Recurso**
- Tamanho da VM  
- Redundância  
- Licenciamento  

### **2. Localização (Região)**
- Preços variam entre regiões  
- Tráfego entre regiões pode gerar custos adicionais  

### **3. Modelo de Consumo**
- Pay-as-you-go  
- Reservas (1 ou 3 anos)  
- Instâncias Spot  

### **4. Manutenção e Governança**
- Recursos inutilizados
- Falta de políticas de tagging  
- Dimensionamento errado 

### **5. Azure Marketplace**
- Softwares de terceiros podem adicionar custos extras  

---

## 💰 Calculadoras de Estimativa

### **Azure Pricing Calculator**
Ferramenta para estimar custos **antes** da implantação.  
Permite simular:

- VMs  
- Banco de dados  
- Storage  
- Rede  
- Arquiteturas completas  

🔗 https://azure.microsoft.com/pricing/calculator/

---

### **TCO Calculator (Aposentada)**
A antiga ferramenta de **Total Cost of Ownership** foi descontinuada pela Microsoft.  
Ela comparava custos **on‑premises vs Azure**.

Hoje, a alternativa recomendada é:

- **Azure Migrate** (inventário + sizing + estimativa de custo)

---

## 📊 Ferramentas de Gerenciamento

### **Microsoft Cost Management + Billing**

Ferramenta nativa para:

- Analisar custos  
- Configurar alertas  
- Exportar dados  
- Identificar anomalias  
- Acompanhar reservas  

#### **Principais recursos**

| Recurso | Descrição |
|--------|-----------|
| **Cost Analysis** | Visualização detalhada por serviço, região, tag, assinatura |
| **Budgets** | Definição de limites de gasto |
| **Alerts** | Notificações automáticas |
| **Exports** | Envio diário para Storage ou Power BI |
| **Cost Allocation** | Distribuição de custos entre equipes/projetos |

---

## 🧠 Boas Práticas de FinOps

### **1. Use Tags**
Exemplos úteis:
- `Environment: Production`
- `CostCenter: MKT001`
- `Owner: jose.silva`

### **2. Crie Orçamentos**
- Mensais, trimestrais ou anuais  
- Alertas automáticos por e-mail ou webhook  

### **3. Analise Recursos Subutilizados**
- VMs superdimensionadas  
- Discos sem anexação  
- IPs públicos ociosos  

### **4. Utilize Reservas**
- Economia de até 72% em workloads previsíveis  

### **5. Automatize**
- Azure Policy  
- Alertas inteligentes  

---

## 📚 Recursos Oficiais

- Introdução ao módulo  
  https://learn.microsoft.com/training/modules/describe-cost-management-azure/1-introduction

- Fatores de custo  
  https://learn.microsoft.com/training/modules/describe-cost-management-azure/2-describe-factors-affect-costs-azure

- Calculadoras de estimativa  
  https://learn.microsoft.com/training/modules/describe-cost-management-azure/3-compare-pricing-total-cost-of-ownership-calculators

- Ferramentas de gerenciamento  
  https://learn.microsoft.com/training/modules/describe-cost-management-azure/6-describe-azure-tool

---

## 📄 Licença

Este repositório contém conteúdo derivado e resumido da documentação pública da Microsoft Learn.  
Consulte os links oficiais para detalhes completos.

---

<p align="center">
  Feito para ajudar você a dominar custos no Azure.
</p>
