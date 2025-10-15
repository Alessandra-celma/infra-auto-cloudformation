# infra-auto-cloudformation
☁️ Implementando Infraestrutura Automatizada com AWS CloudFormation
Descrição do Projeto

-----

Este repositório contém templates AWS CloudFormation criados para automatizar a infraestrutura em nuvem, incluindo VPC, EC2, Security Groups e Firewalls.
O objetivo é praticar Infraestrutura como Código (IaC) utilizando YAML, promovendo automação, escalabilidade e segurança.
Tecnologias Utilizadas
	•	AWS CloudFormation
	•	Amazon EC2
	•	Amazon VPC
	•	Security Groups
	•	YAML

 -----

Como Executar
	1.	Acesse o console da AWS.
	2.	Vá até CloudFormation > Create Stack.
	3.	Faça upload do template desejado (ex: templates/vpc-template.yaml).
	4.	Clique em Next e siga as instruções.
	5.	Após o deploy, verifique os recursos criados em Resources.

-----

Estrutura dos Templates
Template.                        Função
vpc-template.yaml.       Cria a rede VPC, subnets e tabelas de rota
ec2-template.yaml.       Cria instâncias EC2 e vincula à VPC
security-group.yaml.     Configura regras de firewall e portas liberadas
outputs.yaml.            Exibe os recursos criados e seus IDs

----

Conceitos Envolvidos

	•	Infraestrutura como Código (IaC)
	•	Automação de Deploy
	•	Provisionamento Reprodutível
	•	Gerenciamento de Recursos AWS

----

 📚 Links Úteis

- 🌩️ [Documentação Oficial AWS CloudFormation](https://docs.aws.amazon.com/cloudformation/)
- 🧱 [Guia de Recursos AWS](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-template-resource-type-ref.html)
- 💻 [Plataforma DIO – Desafio CloudFormation](https://web.dio.me/)
- 📘 [Cursos AWS na DIO](https://web.dio.me/track/aws-cloud)



