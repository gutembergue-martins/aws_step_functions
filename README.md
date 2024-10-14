## AWS Step Functions

O AWS Step Functions pode ser utilizado com mais de 220 serviços da AWS, incluindo:
- Serviços de computação, como AWS Lambda, Amazon ECS, Amazon EKS e AWS Fargate
- Serviços de banco de dados, como Amazon DynamoDB
- Serviços de mensagens, como Amazon SNS e Amazon SQS
- Serviços de processamento de dados
- Serviços de análise, como Amazon Athena, AWS Batch, AWS Glue, Amazon EMR e AWS Glue DataBrew
- Serviços de IA generativa e machine learning, como Amazon SageMaker e Amazon Bedrock

O AWS Step Functions é um serviço de fluxo de trabalho visual que permite coordenar componentes de aplicativos e microsserviços distribuídos. Ele cria máquinas de estado na nuvem para executar as etapas e coordenar os componentes da aplicação.

Este repositório inclui exemplos detalhados que o ajudarão a desbloquear o poder do fluxo de trabalho sem servidor.

## Exemplos e postagens de blog de apoio

### O que é o Amazon Bedrock?

O Amazon Bedrock é um serviço totalmente gerenciado que disponibiliza modelos básicos de alto desempenho (FMs) das principais empresas de IA e da Amazon para seu uso por meio de um sistema unificado. API Você pode escolher entre uma ampla variedade de modelos de base para encontrar o modelo mais adequado ao seu caso de uso. O Amazon Bedrock também oferece um amplo conjunto de recursos para criar aplicações de IA generativa com segurança, privacidade e IA responsável. Usando o Amazon Bedrock, você pode facilmente experimentar e avaliar os principais modelos básicos para seus casos de uso, personalizá-los de forma privada com seus dados usando técnicas como ajuste fino e geração aumentada de recuperação (RAG) e criar agentes que executem tarefas usando seus sistemas corporativos e fontes de dados.

### O que posso fazer com o Amazon Bedrock?

Você pode usar o Amazon Bedrock para fazer o seguinte:

- Fazer testes com prompts e configurações: Envie solicitações e gere respostas com inferência de modelo ao enviar prompts usando diferentes configurações e modelos de base para gerar respostas. Você pode usar o API ou os playgrounds de texto, imagem e bate-papo no console para experimentar uma interface gráfica. Quando estiver pronto, configure seu aplicativo para fazer solicitações ao InvokeModelAPIs.

- Aumentar a geração de resposta com informações de suas fontes de dados: crie bases de conhecimento ao fazer upload de fontes de dados para consulta a fim de aumentar a geração de resposta de um modelo de base.

- Crie aplicativos que raciocinem sobre como ajudar um cliente: crie agentes que usem modelos básicos, façam API chamadas e (opcionalmente) consultem bases de conhecimento para raciocinar e realizar tarefas para seus clientes.

- Adapte modelos a tarefas e domínios específicos com dados de treinamento: personalize um modelo de base do Amazon Bedrock ao fornecer dados de treinamento para ajuste fino ou pré-treinamento contínuo, a fim de ajustar os parâmetros de um modelo e melhorar sua performance em tarefas específicas ou em determinados domínios.

- Melhore a eficiência e a saída de uma aplicação baseada em FM: compre throughput provisionado para um modelo de base a fim de executar inferências em modelos com mais eficiência e com descontos.

- Determine o melhor modelo para o seu caso de uso: avalie as saídas de diferentes modelos com conjuntos de dados de prompts integrados ou personalizados para determinar o modelo mais adequado à sua aplicação.

### Como faço para começar a usar o Amazon Bedrock?

Recomendamos que você comece com o Amazon Bedrock fazendo o seguinte:

1. Familiarize-se com os [termos e conceitos](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/key-definitions.html) que o Amazon Bedrock usa.

2. Entenda como AWS [cobra](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/bedrock-pricing.html) pelo uso do Amazon Bedrock.

3. Experimente os [Começando a usar o Amazon Bedrock](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/getting-started.html) tutoriais. Nos tutoriais, você aprende a usar os playgrounds no console [Amazon](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/what-is-bedrock.html) Bedrock. Você também aprende e como usar o [AWS SDK](https://docs.aws.amazon.com/pt_br/bedrock/latest/userguide/getting-started-api.html) para ligar para as API operações da Amazon Bedrock.

4. Leia a documentação dos recursos que você deseja incluir em seu aplicativo.

### Acelerando cargas de trabalho usando paralelismo no AWS Step Functions

Neste exemplo, você usa o [AWS Step Functions](https://aws.amazon.com/step-functions/) para criar um aplicativo que usa processamento paralelo para concluir quatro horas de trabalho em cerca de 60 segundos.

Blog Post: [Accelerating workloads using parallelism in AWS Step Functions](https://aws.amazon.com/blogs/compute/accelerating-workloads-using-parallelism-in-aws-step-functions/)

### Controlar a simultaneidade em sistemas distribuídos usando AWS Step Functions

Neste exemplo, você usa [AWS Step Functions](https://aws.amazon.com/step-functions/) para controlar a simultaneidade em seu sistema distribuído. Isso ajuda a evitar a sobrecarga de recursos limitados em seu pipeline de processamento de dados sem servidor ou a reduzir o risco de disponibilidade controlando a velocidade em seus fluxos de trabalho de automação de TI.

Blog Post: [Controlling concurrency in distributed systems using AWS Step Functions](https://aws.amazon.com/blogs/compute/controlling-concurrency-in-distributed-systems-using-aws-step-functions/)

### Simulação de integrações de serviços com Step Functions Local
Neste exemplo, você usa o Local do AWS Step Functions para testar uma máquina de estado simulando as chamadas de serviço. Você pode encontrar detalhes no arquivo [README](./sam/app-local-testing-mock-config/README.md) do exemplo.

Blog Post: [Mocking service integrations with AWS Step Functions Local](https://aws.amazon.com/blogs/compute/mocking-service-integrations-with-aws-step-functions-local/)


## Segurança

Consulte [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) para obter mais informações.

## Licença

Esta biblioteca está licenciada sob a licença MIT-0. Veja o arquivo LICENÇA.

