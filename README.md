# 📘 Projeto de Engenharia de Dados – Azure, Databricks e ADF

## 🚀 Objetivos do Projeto

- ✔️ Construí um **pipeline completo de Engenharia de Dados**
- ✔️ Estruturei um **Data Lake** utilizando **Azure Data Lake Storage Gen2**
- ✔️ Configurei o **Azure Databricks** integrado ao ambiente em nuvem
- ✔️ Desenvolvi notebooks no Databricks utilizando **Scala**
- ✔️ Criei pipelines de ingestão e transformação no **Azure Data Factory (ADF)**
- ✔️ Integrei o projeto completo com o **GitHub** para versionamento
- ✔️ Configurei **gatilhos de execução** para automatizar o pipeline
- ✔️ Coloquei todo o fluxo em **produção** no Azure

---

## 🗂️ Arquitetura do Projeto

A solução que implementei utiliza os seguintes serviços da Azure:

- **Azure Data Lake Storage Gen2** → armazenamento em camadas (Bronze, Silver)  
- **Azure Databricks** → processamento distribuído via notebooks em Scala  
- **Azure Data Factory** → orquestração das atividades  
- **GitHub** → versionamento de notebooks e pipelines  
- **Triggers do ADF** → automação de execuções

### 🔄 Fluxo resumido da solução

1. **Ingestão** → Carrego dados brutos na camada Bronze do Data Lake  
2. **Transformação** → Processos no Databricks geram as camadas Silver e Gold  
3. **Orquestração** → O Azure Data Factory coordena todas as etapas  
4. **Versionamento (CI/CD)** → GitHub controla mudanças e histórico  
5. **Produção** → O pipeline roda automaticamente via triggers

## 🔧 Tecnologias e Ferramentas que utilizei

- **Azure Data Lake Storage Gen2**
- **Azure Databricks**
- **Scala**
- **Azure Data Factory**
- **GitHub**
- **Azure Monitor (opcional)**
- **Triggers do ADF**

---

## ▶️ Como executo o pipeline

1. **Configuração do Data Lake**  
   - Criei a Storage Account  
   - Ativei o *Hierarchical Namespace*  
   - Estruturei os containers bronze/silver

2. **Configuração do Databricks**  
   - Configurei o workspace e o cluster  
   - Fiz a integração com o Data Lake via ABFS  
   - Desenvolvi os notebooks em Scala

3. **Construção dos Pipelines no ADF**  
   - Modelei as etapas de ingestão, transformação e movimentação  
   - Conectei atividades e notebooks

4. **Integração com o GitHub**  
   - Versionei notebooks  
   - Versionei pipelines do ADF

5. **Configuração dos Triggers**  
   - Programei gatilhos para execução automática

---

## 📦 Deploy em Produção

Para finalizar o projeto, eu:

- Publiquei os pipelines no Azure Data Factory  
- Ativei os triggers  
- Realizei testes de execução  
- Monitorei logs e alertas pelo ADF Monitor e Azure Monitor

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais.

