
---

# 📊 **1. Dataset de Faturamento**

Dataset criado em Python simulando o faturamento mensal de três plantas:

- Paraisópolis — MG  
- Belo Horizonte — MG  
- Pouso Alegre — MG 

### **Período Simulado**
**01/01/2025 a 01/07/2025** (6 meses)

### **Colunas**
| Coluna | Descrição |
|--------|-----------|
| `data` | Data do faturamento |
| `planta` | Planta responsável pela receita |
| `moeda` | BRL ou USD |
| `valor` | Valor faturado |
| `rate` | Taxa de câmbio simulada |

---

# 🚚 **2. Dataset de Fretes**

Segundo dataset gerado via Python, simulando fretes inbound e outbound.

### **Período Simulado**
**01/07/2025 a 30/07/2025**

### **Atributos Gerados**
- Cliente  
- Planta  
- Shipment Type (inbound / outbound)  
- Premium Status (recuperável, não recuperável, pendente)  
- Agente de carga  
- Carrier (DHL, FedEx, UPS, TNT)  
- Processo (aprovado, rejeitado, pendente)  
- Segmento (eletrônico, metal mecânico, plástico, têxtil)  
- Região de origem (LATAM, Europa, NAFTA, PAC)  
- Exume (motivo do frete)  
- Valor do frete  
- Data do frete  

---

# 📈 **3. Painel Power BI – Fretes Premium**

O dashboard desenvolvido permite analisar os dados de maneira dinâmica, com diversos filtros e indicadores.

### **Filtros do painel**
- Ano / Mês  
- Planta (Paraisópolis, Belo Horizonte, Poços de Caldas)  
- Moeda (BRL / USD)  
- Shipment Type (inbound / outbound)

### **Cards principais**
- Faturamento total  
- Gasto total com fretes  
- % do frete sobre o faturamento  
- Total recuperado  
- Total não recuperável

### **Visuais construídos**
- Quantidade de fretes por tipo  
- Gasto por planta  
- Custo por dia  
- Tabela de motivos (Resumo) por valor  
- Distribuição por segmento  
- Análise por carrier e agente de carga  

### **Medidas DAX utilizadas**  
*(A serem Documentadas)*

---

# 🧠 **4. Tecnologias Utilizadas**
- Python (pandas, numpy)  
- Power BI (DAX, modelagem)  
- Excel  
- SQL  
- Git & GitHub para versionamento  

---

# 📌 **5. Objetivo do Projeto**

Este case demonstra a capacidade de:

- Construir datasets do zero via Python  
- Criar um fluxo completo de ETL → transformação → análise  
- Simular cenários logísticos reais  
- Criar dashboards profissionais em Power BI  
- Documentar e versionar todo o processo  
- Entender métricas chave de PCL  (Planejamento e Controle Logístico)

---

# 🏁 **6. Resultados Obtidos**

Com o painel final, tornou-se possível:

- Visualizar custos logísticos por planta, período e moeda  
- Entender o impacto percentual dos fretes no faturamento  
- Identificar motivos recorrentes de gastos premium  
- Avaliar fretes recuperáveis vs. não recuperáveis  
- Observar picos diários de custo  
- Analisar comportamento por segmento, carrier e região  

---

# DataViz
<iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/embed/8SMHUAIs_rg" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen>
</iframe>


**Antonio Marcos**  


---
