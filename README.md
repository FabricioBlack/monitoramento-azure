# monitoramento-azure
Meus aprendizados sobre monitoramento de VMs no Azure, reunidos como parte do desafio da trilha AZ-104.


# 📊 Monitoramento de Máquinas Virtuais no Azure

Este repositório faz parte do desafio proposto na trilha AZ-104 da DIO. Aqui compartilho meus aprendizados sobre como configurar e gerenciar o monitoramento de recursos no Microsoft Azure, com foco em máquinas virtuais (VMs).

---

## 🧠 O que aprendi

### ✅ Ativação de Diagnóstico
- Ativei logs e métricas de diagnóstico nas VMs.
- Entendi como o Azure Monitor coleta dados sobre desempenho, integridade e alertas.

### ✅ Alertas e Ações Automatizadas
- Configurei alertas com base em condições como uso de CPU acima de 80%.
- Criei ações automáticas (como e-mail ou webhook) quando um alerta é disparado.

### ✅ Log Analytics
- Vinculei a VM a um workspace do **Log Analytics**.
- Realizei consultas com **Kusto Query Language (KQL)** para análise avançada.

### ✅ Azure Monitor + Insights
- Usei o **Azure Monitor** para criar painéis e visualizações personalizadas.
- Ativei o **Insights de VM**, que fornece dados detalhados sobre disco, rede e processos.

---

## 💡 Dicas Pessoais

- **Sempre configure alertas** para monitorar o estado da VM e evitar surpresas com falhas.
- Use o **Auto-shutdown** junto com alertas para VMs de teste, economizando recursos.
- Vincule suas VMs ao **Log Analytics** mesmo que não use no momento — isso permite análises históricas quando necessário.
- Explore o **Azure Workbooks** para criar relatórios visuais com dados do Azure Monitor.

---

## 📸 Capturas de Tela (opcional)

Você pode criar uma pasta `/imagens` com prints como:
- Configuração do diagnóstico
- Tela de criação de alerta
- Painel do Log Analytics com consulta KQL

---

## 📚 Referências

- [Configurar o monitoramento de máquinas virtuais no Azure – Microsoft Learn](https://learn.microsoft.com/pt-br/azure/azure-monitor/vm/vminsights-overview)
- [Documentação oficial do Azure Monitor](https://learn.microsoft.com/pt-br/azure/azure-monitor/)

---

## 👨‍💻 Sobre mim

Meu nome é Fabrício e este repositório é parte da minha jornada rumo à certificação AZ-104. Gosto de compartilhar conhecimento e acredito que aprender ensinando é uma das formas mais eficazes de evolução técnica. 🚀

---

⭐ Se este conteúdo te ajudou, sinta-se à vontade para dar uma estrela no repositório!
