# desafio-cloudformation-codegirls2025
Repositório para o desafio de CloudFormation do curso Santander Code Girls

# 📘 Desafio AWS CloudFormation

Este repositório contém o registro do processo de criação de uma **stack** na AWS utilizando o **CloudFormation** como parte de um desafio prático. O objetivo foi compreender o funcionamento da ferramenta, sua integração com outros serviços da AWS e o ciclo de criação e gerenciamento de recursos automatizados por meio de templates.

---

## 🚀 Etapas do Desafio

### **1. Acesso ao CloudFormation**
Acessei o serviço **AWS CloudFormation** no console da AWS e iniciei o processo de criação de uma nova stack.

### **2. Escolha do Template**
No **Passo 1**, selecionei a opção **“Criar a partir de um template”**.  
Utilizei um **template do repositório fornecido pela AWS**, que já continha a estrutura necessária para provisionar os recursos automaticamente.

### **3. Configuração da Stack**
No **Passo 2**, forneci um **nome para a stack**.  
Neste ponto, um **bucket S3** já havia sido criado previamente e estava disponível para uso durante o processo.

### **4. Definição de Parâmetros e Tags**
No **Passo 3**, adicionei uma **tag de identificação** para facilitar a organização e o rastreamento da stack.  
Não realizei modificações adicionais neste passo — ou seja:
- Não configurei uma **role IAM personalizada**;  
- Mantive as opções padrão para **rollback em caso de falhas**.

### **5. Revisão e Criação**
No **Passo 4**, revisei todas as configurações realizadas, confirmei os detalhes e finalizei o processo de **criação da stack**.

---

## 💡 Aprendizados

Durante a realização deste desafio, pude compreender melhor:

- **O conceito de stacks** e como elas agrupam e gerenciam recursos AWS como uma única unidade lógica;  
- **A importância dos templates CloudFormation**, que permitem a **infraestrutura como código (IaC)**, facilitando o versionamento e a reprodutibilidade dos ambientes;  
- Como **tags** auxiliam na organização e identificação de recursos em ambientes com múltiplas stacks;  
- O papel do **Amazon S3** no armazenamento de templates e arquivos utilizados pelo CloudFormation;  
- A importância de revisar cuidadosamente cada etapa antes da criação, especialmente parâmetros e permissões IAM;  
- Como o **CloudFormation automatiza o provisionamento** e simplifica o gerenciamento de infraestrutura em comparação à criação manual de recursos.

---

## 🧩 Tecnologias Utilizadas

- **AWS CloudFormation**  
- **Amazon S3**  
- **AWS Management Console**

---

## 🗂️ Estrutura do Repositório

📁 aws-cloudformation-desafio/
 ├── README.md          → Documentação do processo e aprendizados
 ├── template.yaml      → (Opcional) Template utilizado, se disponível
 └── imagens/           → Capturas de tela do processo (opcional)


---

## ✨ Conclusão

Este desafio foi uma excelente introdução prática ao **CloudFormation**, reforçando a importância de automatizar a infraestrutura e de compreender o fluxo de criação e gerenciamento de stacks na AWS.
