## AWS Step Functions

AWS Step Functions é um serviço de fluxo de trabalho visual de baixo código. Este repositório inclui exemplos detalhados que o ajudarão a desbloquear o poder do fluxo de trabalho sem servidor.

## Exemplos e postagens de blog de apoio

### Acelerando cargas de trabalho usando paralelismo no AWS Step Functions

Neste exemplo, você usa o [AWS Step Functions](https://aws.amazon.com/step-functions/) para criar um aplicativo que usa processamento paralelo para concluir quatro horas de trabalho em cerca de 60 segundos.

Blog Post: [Accelerating workloads using parallelism in AWS Step Functions](https://aws.amazon.com/blogs/compute/accelerating-workloads-using-parallelism-in-aws-step-functions/)

### Controlar a simultaneidade em sistemas distribuídos usando AWS Step Functions

Neste exemplo, você usa [AWS Step Functions](https://aws.amazon.com/step-functions/) para controlar a simultaneidade em seu sistema distribuído. Isso ajuda a evitar a sobrecarga de recursos limitados em seu pipeline de processamento de dados sem servidor ou a reduzir o risco de disponibilidade controlando a velocidade em seus fluxos de trabalho de automação de TI.

Blog Post: [Controlling concurrency in distributed systems using AWS Step Functions](https://aws.amazon.com/blogs/compute/controlling-concurrency-in-distributed-systems-using-aws-step-functions/)

### Simulação de integrações de serviços com Step Functions Local
Neste exemplo, você usa o Local do AWS Step Functions para testar uma máquina de estado simulando as chamadas de serviço. Você pode encontrar detalhes no arquivo [README](./sam/app-local-testing-mock-config/README.md) do exemplo.

Blog Post: [Mocking service integrations with AWS Step Functions Local](https://aws.amazon.com/blogs/compute/mocking-service-integrations-with-aws-step-functions-local/)

### Orquestrando a recuperação de objetos do S3 Glacier Deep Archive usando Step Functions
Neste exemplo, você usa o AWS Step Functions para orquestrar a restauração de objetos S3 do S3 Glacier Deep Archive. Você pode encontrar detalhes no arquivo [README](./cdk/app-glacier-deep-archive-retrieval/README.md) do exemplo.

Blog Post: [Orchestrating S3 Glacier Deep Archive object retrieval using Step Functions](Blog Link Here)

### Detecção e edição de segmentos de vídeo usando AWS Step Functions
Este fluxo de trabalho tem como objetivo mostrar como aproveitar o AWS Step Functions para executar tarefas típicas de edição de vídeo. Especificamente, o exemplo usa um vídeo que tem [barras coloridas SMPTE](https://en.wikipedia.org/wiki/SMPTE_color_bars) de duração aleatória no início. O fluxo de trabalho obterá um vídeo de demonstração do S3, passará pelo Amazon Rekognition para detectar segmentos e, em seguida, o Amazon MediaConvert removerá o segmento de vídeo inicial (barras coloridas SMPTE). Você pode encontrar detalhes no arquivo [README](./sam/app-video-segment-detection-and-edition/README.md) do exemplo.
Blog Post: [Low code workflows with AWS Elemental MediaConvert](https://aws.amazon.com/blogs/media/low-code-workflows-with-aws-elemental-mediaconvert/)

## Demonstrações dos recursos do Step Functions

### Funções da etapa de demonstração Teste local com integrações de serviços simuladas usando estruturas de teste Java (JUnit e Spock)
Nesta demonstração, você pode aprender como usar JUnit ou Spock para executar testes locais do Step Functions. Isso é útil se seus aplicativos sem servidor atuais forem desenvolvidos em torno de Java. Com essa abordagem você pode aproveitar as ferramentas de teste Java existentes.

[Demo App](./sam/demo-local-testing-using-java/README.md)

### Demonstração de ASL

Esta demonstração ilustra os recursos de ASL e [AWS Step Functions](https://aws.amazon.com/step-functions/), incluindo funções intrínsecas e processamento de caminho JSON.

Você pode implantar isso usando SAM ou de forma independente como um modelo CloudFormation no Console AWS

### ranscrição de vídeo com integrações de serviços AWS SDK ###

Nesta demonstração, você aprende a usar integrações de serviços do AWS SDK para criar um fluxo de trabalho de transcrição de vídeo.

Blog Post: [Now — AWS Step Functions Supports 200 AWS Services To Enable Easier Workflow Automation](https://github.com/aws-samples/aws-stepfunctions-examples/tree/main/sam/demo-video-transcription)

## Segurança

Consulte [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) para obter mais informações.

## Licença

Esta biblioteca está licenciada sob a licença MIT-0. Veja o arquivo LICENÇA.

