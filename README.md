# ☁️ Implementando Infraestrutura Automatizada com AWS CloudFormation

## 📘 Descrição

Explore a automação de infraestrutura como código (IaC), utilizando **templates em JSON ou YAML** para criação, configuração e gerenciamento de recursos na **AWS**.  
A atividade desafia os participantes a aplicar conceitos de **padronização, replicação e segurança** na infraestrutura em nuvem, simulando cenários reais de **provisionamento automatizado**.

---

## 🚀 Objetivos do Projeto

- Criar e configurar recursos na AWS de forma automatizada.  
- Utilizar o **AWS CloudFormation** como ferramenta principal de IaC.  
- Aprender boas práticas de versionamento de infraestrutura.  
- Simular cenários reais de deploy e replicação de ambientes.  
- Compreender a relação entre **DevOps** e **Infraestrutura como Código**.

---

## 🧩 Tecnologias Utilizadas

- **AWS CloudFormation**  
- **Amazon EC2**  
- **Amazon S3**  
- **Amazon VPC**  
- **IAM (Identity and Access Management)**  
- **JSON / YAML**  
- **Git & GitHub**

---

## 🏗️ Estrutura do Projeto

```bash
📁 aws-cloudformation-project/
├── 📄 README.md
├── 📄 template-vpc.yaml
├── 📄 template-ec2.yaml
├── 📄 parameters.json
└── 📄 outputs.json
```
___

    •	template-vpc.yaml → Criação da rede VPC com subnets públicas e privadas.
	•	template-ec2.yaml → Configuração de instâncias EC2.
	•	parameters.json → Parâmetros reutilizáveis para o stack.
	•	outputs.json → Saídas com IDs e informações úteis do deploy.
