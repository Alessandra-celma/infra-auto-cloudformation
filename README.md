  # Implementando Infraestrutura Automatizada com AWS CloudFormation

##  Descrição

Explore a automação de infraestrutura como código (IaC), utilizando **templates em JSON ou YAML** para criação, configuração e gerenciamento de recursos na **AWS**.  
A atividade desafia os participantes a aplicar conceitos de **padronização, replicação e segurança** na infraestrutura em nuvem, simulando cenários reais de **provisionamento automatizado**.

---

## Objetivos do Projeto

- Criar e configurar recursos na AWS de forma automatizada.  
- Utilizar o **AWS CloudFormation** como ferramenta principal de IaC.  
- Aprender boas práticas de versionamento de infraestrutura.  
- Simular cenários reais de deploy e replicação de ambientes.  
- Compreender a relação entre **DevOps** e **Infraestrutura como Código**.

---

## Tecnologias Utilizadas

- **AWS CloudFormation**  
- **Amazon EC2**  
- **Amazon S3**  
- **Amazon VPC**  
- **IAM (Identity and Access Management)**  
- **JSON / YAML**  
- **Git & GitHub**

---

##  Estrutura do Projeto

```bash
📁 aws-cloudformation-project/
├── 📄 README.md
├── 📄 template-vpc.yaml
├── 📄 template-ec2.yaml
├── 📄 parameters.json
└── 📄 outputs.json
```
---

    •	template-vpc.yaml → Criação da rede VPC com subnets públicas e privadas.
	•	template-ec2.yaml → Configuração de instâncias EC2.
	•	parameters.json → Parâmetros reutilizáveis para o stack.
	•	outputs.json → Saídas com IDs e informações úteis do deploy.
    
---

## Passos para Execução
	1.	Faça login na sua conta AWS.
	2.	Acesse o serviço CloudFormation.
	3.	Clique em Create Stack → With new resources (standard).
	4.	Envie o template .yaml ou .json deste projeto.
	5.	Defina os parâmetros necessários.
	6.	Clique em Next → Next → Create Stack.
	7.	Aguarde até que o status mude para CREATE_COMPLETE.

----

## Diagrama da Arquitetura AWS

Representação simplificada da infraestrutura criada pelo CloudFormation:

```
                    ☁️ AWS Cloud
                         │
              ┌──────────┴──────────┐
              │                     │
         🌐 VPC (10.0.0.0/16)       │
              │                     │
     ┌────────┴─────────┐       🪣 S3 Bucket
     │                  │
🌍 Subnet Pública   🔒 Subnet Privada
     │                  │
     │                  │
  ⚙️ EC2 Instance     🧩 RDS Database
     │
     │
  🔐 IAM Role & Policies

```
---

## Explicação do fluxo:
	•	O CloudFormation provisiona todos os recursos de forma automatizada.
	•	A VPC organiza a rede, dividida em subnets públicas e privadas.
	•	A instância EC2 é criada dentro da subnet pública.
	•	O Bucket S3 armazena arquivos e logs do ambiente.
	•	O IAM controla permissões e segurança de acesso.


---


## Aprendizados-Chave
	•	Infraestrutura automatizada com CloudFormation
	•	Reutilização e versionamento de templates
	•	Boas práticas de segurança e replicação
	•	Integração com pipelines DevOps

⸻

## Links Úteis
	•	🌩️ Documentação oficial da AWS CloudFormation￼
	•	🧱 Guia de referência de recursos da AWS￼
	•	🎓 Plataforma DIO – Cursos e Desafios AWS￼

⸻

## Conclusão

Este projeto reforça o uso da Infraestrutura como Código (IaC) como base para autonomia, padronização e escalabilidade na nuvem.
Ao dominar o AWS CloudFormation, o desenvolvedor se torna capaz de entregar ambientes consistentes, seguros e replicáveis com apenas alguns comandos.

⸻

⭐ Se este projeto te ajudou, não esqueça de dar um “Star” no repositório!



