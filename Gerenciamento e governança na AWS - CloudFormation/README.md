# Descrição do Desafio
Este laboratório tem como objetivo de implementar sua primeira Stack com AWS CloudFormation. O entregável é um repositório organizado contendo anotações e insights adquiridos durante a prática, servindo como material de apoio para os seus estudos e futuras implementações.


# Stacks com AWS CloudFormation

O **AWS CloudFormation** é um serviço que permite modelar e provisionar recursos da AWS de forma automatizada, utilizando arquivos de template em JSON ou YAML. Esses templates descrevem a infraestrutura desejada como código (IaC – *Infrastructure as Code*), garantindo consistência, reprodutibilidade e facilidade de gerenciamento.  

No CloudFormation, o conceito central é o **Stack**.

## O que é um Stack

- Um **Stack** é um conjunto de recursos da AWS que são criados, atualizados ou excluídos em conjunto, a partir de um template do CloudFormation.  
- Ele representa uma unidade lógica de implantação, permitindo gerenciar toda a infraestrutura como um único recurso.  
- Alterações no template podem ser aplicadas ao Stack, atualizando automaticamente os recursos envolvidos.  

## Principais Características

- **Automação**: provisionamento e configuração de recursos sem necessidade de intervenção manual.  
- **Controle de Versão**: templates podem ser versionados em repositórios Git, facilitando auditoria e colaboração.  
- **Consistência**: garante que ambientes (desenvolvimento, teste, produção) sejam criados de forma idêntica.  
- **Gerenciamento Simplificado**: operações de criação, atualização e exclusão são centralizadas no Stack.  
- **Rollback Automático**: em caso de falha na criação ou atualização, o CloudFormation reverte as mudanças para manter o ambiente estável.  

## Exemplos de Uso

- Criação de ambientes completos (VPC, sub-redes, instâncias EC2, bancos de dados, balanceadores de carga).  
- Automação de pipelines de CI/CD.  
- Replicação de ambientes de teste e produção de forma padronizada.  
- Gerenciamento de permissões e políticas de segurança via IAM.  

## Objetivo

O uso de **Stacks no AWS CloudFormation** permite tratar a infraestrutura como código, trazendo maior previsibilidade, escalabilidade e governança para projetos em nuvem. Este material serve como apoio para estudos e futuras implementações em ambientes reais.
