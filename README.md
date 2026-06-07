# Desafio DIO - Implementando sua Primeira Stack com AWS CloudFormation

## Descrição

Este projeto foi desenvolvido como parte do laboratório da DIO com o objetivo de criar e gerenciar recursos na AWS utilizando o AWS CloudFormation. Durante a prática, foi possível compreender o conceito de Infraestrutura como Código (IaC) e automatizar a criação de recursos na nuvem através de templates.

## Objetivos

* Compreender os conceitos de Infraestrutura como Código (IaC).
* Criar uma Stack utilizando AWS CloudFormation.
* Automatizar a criação de recursos na AWS.
* Documentar o processo de implementação e os aprendizados obtidos.

## O que é AWS CloudFormation?

O AWS CloudFormation é um serviço que permite modelar e provisionar recursos da AWS utilizando arquivos de template escritos em JSON ou YAML. Com ele, é possível criar ambientes completos de forma automatizada, padronizada e reproduzível.

## Conceitos Aprendidos

### Infraestrutura como Código (IaC)

Infraestrutura como Código é a prática de gerenciar recursos de infraestrutura através de arquivos de configuração, eliminando a necessidade de configurações manuais.

### Templates

Os templates definem quais recursos serão criados e suas configurações.

### Stack

Uma Stack é o conjunto de recursos AWS criados e gerenciados por um template do CloudFormation.

### Recursos

Os recursos podem incluir:

* Amazon S3
* Amazon EC2
* Amazon VPC
* IAM Roles
* Security Groups
* Outros serviços AWS

## Etapas Realizadas

1. Acesso ao Console AWS.
2. Abertura do serviço AWS CloudFormation.
3. Criação de um template.
4. Validação do template.
5. Criação da Stack.
6. Monitoramento dos eventos da Stack.
7. Verificação dos recursos criados.
8. Exclusão da Stack para evitar custos desnecessários.

## Exemplo de Estrutura do Template

```yaml
Resources:
  MeuBucket:
    Type: AWS::S3::Bucket
```

## Benefícios do CloudFormation

* Automação da infraestrutura.
* Padronização dos ambientes.
* Facilidade de replicação.
* Controle de versão dos templates.
* Redução de erros manuais.

## Desafios Encontrados

* Entender a sintaxe YAML utilizada nos templates.
* Interpretar mensagens de erro durante a validação.
* Compreender a relação entre recursos e dependências.

## Aprendizados

Durante a execução do laboratório foi possível entender como o CloudFormation simplifica a criação de ambientes na AWS e como a abordagem de Infraestrutura como Código facilita o gerenciamento e a manutenção dos recursos em nuvem.

## Evidências

As capturas de tela do processo de criação da Stack estão disponíveis na pasta `/images`.

## Conclusão

A prática permitiu compreender os fundamentos do AWS CloudFormation e sua importância na automação de infraestrutura. O conhecimento adquirido servirá como base para projetos futuros envolvendo DevOps, automação e computação em nuvem.

## Autor

Projeto desenvolvido como parte da formação AWS na DIO.
