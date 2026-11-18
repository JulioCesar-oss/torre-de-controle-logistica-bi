# Torre de Controle Logística & BI de Análise Gerencial (Supply Chain)

## 🎯 Visão Geral do Projeto
Este projeto detalha a concepção e implementação da **Torre de Controle Logística** e do **BI de Análise Gerencial** em um Centro de Distribuição (CD 801). Diante da ausência histórica de dados consolidados e de uma visão unificada da operação — evidenciada por um vácuo de indicadores confiáveis —, o projeto estruturou uma central de inteligência de dados utilizando o **Looker Studio**. A iniciativa integrou toda a cadeia (do recebimento à expedição e frota), transformando a liderança de um modelo estritamente reativo para uma gestão preditiva, ágil e focada em valor.

---

## 🔍 O Problema
No início de 2026, a operação enfrentava graves lacunas de visibilidade e governança de dados:
* **Cultura do "Escuro" e Ausência de Conslidação:** Inexistência de um painel corporativo único onde a alta gestão pudesse validar o andamento das frentes do CD em tempo real (havia apenas um BI isolado e inconsistente cobrindo exclusivamente o setor de separação).
* **Interferências Externas e Cego de Insumos (*Grades Forçadas*):** Simulações de ondas e reposições de loja geradas pelo setor comercial entravam na operação sem validação sistêmica ou visibilidade prévia, sabotando o volume planejado e gerando gargalos severos.
* **Gestão Reativa:** Tomada de decisão baseada em apagar incêndios diários por falta de visibilidade antecipada de gargalos, volumetria e capacidade de atendimento.

---

## 🛠️ A Abordagem e Solução

Para sanar a cegueira operacional e criar uma governança unificada, o projeto foi estruturado em quatro frentes estratégicas:

1. **Desenvolvimento do BI Análise Gerencial (Torre de Controle Base):**
   * Concepção e modelagem de um painel centralizador no **Looker Studio** para capturar o *start* do dia da operação.
   * Visibilidade consolidada de indicadores críticos: volume a produzir, saldo pendente de ressuprimento, *cross-docking*, separação de *picking* e pulmão.
   * Auditoria de inputs externos (*grades forçadas* e simulações comerciais), trazendo transparência ao impacto do comercial sobre a capacidade logística.
2. **Implantação da Daily Operacional Baseada em Dados:**
   * Instituição de reuniões diárias obrigatórias com a liderança fundamentadas nos dados da Torre de Controle, permitindo analisar o que foi realizado e antecipar demandas futuras (*S&OP Operacional*).
3. **Escalabilidade do Ecossistema de BI (Expansão da Torre):**
   * Após a consolidação do painel gerencial, desenvolvimento sucessivo de dashboards especializados cobrindo toda a cadeia logística:
     * **Recebimento**
     * **Ressuprimento**
     * **Separação**
     * **Conferência**
     * **Expedição**
     * **Frota**
     * **Gestão de Avarias**
4. **Visão Descritiva e Preditiva:**
   * Evolução dos relatórios para não apenas mostrar o histórico (*o que aconteceu*), mas sim projetar cenários e tendências (*o que pode acontecer*).

---

## 📈 Resultados e Impactos de Negócio

* **Governança e Transparência Absoluta:** Fim do "achismo" na liderança; qualquer diretog ou gestor passou a ter acesso imediato ao pulso da operação em um único clique.
* **Alinhamento Interdepartamental (Comercial x Logística):** Visibilidade transparente das *grades forçadas*, permitindo blindar o CD contra picos não planejados e alinhar o planejamento comercial à capacidade física real.
* **Virada de Chave Cultural:** Transição de uma postura operacional apagadora de incêndios para uma cultura analítica, preditiva e focada em eficiência contínua.

---

## 🛠️ Tecnologias e Conceitos Aplicados
* **Ferramentas de BI:** Looker Studio.
* **Sistemas:** WMS / ERP integrados.
* **Conceitos:** Torre de Controle Logística, Supply Chain Analytics, Gestão de Indicadores de Desempenho (KPIs), S&OP Operacional, Governança de Dados.
