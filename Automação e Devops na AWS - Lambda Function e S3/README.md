# Descrição do Desafio
Este laboratório tem como objetivo implementar uma infraestrutura automatizada com AWS CloudFormation. O entregável é um repositório organizado contendo anotações e insights adquiridos durante a prática, servindo como material de apoio para os seus estudos e futuras implementações.

# Tarefas Automatizadas com AWS Lambda e Amazon S3

A integração entre **AWS Lambda** e **Amazon S3** permite a automação de tarefas sem a necessidade de servidores, aproveitando o modelo *serverless* da AWS. O S3 atua como repositório de objetos (arquivos, imagens, logs, etc.), enquanto o Lambda executa funções sob demanda em resposta a eventos gerados no bucket.

## Como Funciona

- **Eventos do S3**: operações como upload, exclusão ou modificação de objetos em um bucket podem disparar eventos.  
- **Disparo da Função Lambda**: ao ocorrer um evento configurado, o S3 invoca automaticamente uma função Lambda associada.  
- **Execução Automatizada**: a função Lambda processa o objeto ou executa a lógica definida, sem necessidade de provisionar ou gerenciar servidores.  

## Exemplos de Uso

- **Processamento de Arquivos**: redimensionamento de imagens, conversão de formatos ou compressão de dados
