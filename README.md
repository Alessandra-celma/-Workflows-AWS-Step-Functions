# Explorando Workflows Automatizados com AWS Step Functions

Este repositório contém anotações e práticas sobre o **AWS Step Functions**, serviço de orquestração de fluxos de trabalho na nuvem da Amazon, realizadas durante o desafio da [DIO](https://www.dio.me).

---

## 📌 O que é o AWS Step Functions?
O **AWS Step Functions** é um serviço de orquestração que permite coordenar múltiplos serviços da AWS por meio de fluxos de trabalho visuais, com pouco ou nenhum código.  

Ele facilita a automação, integrações e execução de processos distribuídos com **confiabilidade, escalabilidade e monitoramento em tempo real**.

---

## 🔧 O que foi praticado no desafio
Durante a prática, foram realizados os seguintes passos:

1. **Criação do Workflow**
   - Definição do fluxo de execução no Step Functions.
   - Configuração dos estados (States) e transições.

2. **Integração com Serviços AWS**
   - Validação de arquivos em **S3**.
   - Execução de funções **AWS Lambda**.
   - Uso de **SNS** e **SQS** para mensageria.
   - Interação com tabelas **DynamoDB**.

3. **Execução e Monitoramento**
   - Testes do workflow para validar entradas e saídas.
   - Acompanhamento de logs e métricas no console.
   - Monitoramento visual do progresso do fluxo.

4. **Boas Práticas**
   - Uso de mensageria para desacoplamento de sistemas.
   - Automação de tarefas repetitivas.
   - Escalabilidade e resiliência no desenho da arquitetura.

---

## 📊 Resumo
O **Step Functions** permite criar aplicações distribuídas mais simples e confiáveis, coordenando serviços AWS em **fluxos de trabalho visuais**.  
É uma poderosa ferramenta para aplicar **automação, mensageria e boas práticas de arquitetura em nuvem**.

---

## 🖼️ Imagem do Desafio
Coloque sua imagem (diagrama ou print do workflow) dentro da pasta `images/` e use o link abaixo:

```markdown
![Workflow AWS Step Functions](./images/workflow-step-functions.png)