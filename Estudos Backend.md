# AWS Lambda

- O AWS Lambda é um serviço em nuvem da Amazon que executa aplicações em modelo Serverless, em que as aplicações são desenvolvidas sem a preocupação com os servidores. Tem suporte para várias linguagens como NodeJS, Python, Java, Go, .Net core etc.

- Com o Lambda, há custo pela quantidades de execução/consumo da função, não sendo necessário pagar pelo tempo ocioso, o que pode ser benéfico para sistemas que possuem maior pico de utilização em determinados períodos do ano. Assim, uma máquina com memória e poder computacional é dada ao desenvolvedor de acordo com a necessidade da aplicação. 

- As aplicações são construídas em pequenas funções, com o princípio da responsabilidade única e uma arquitetura orientada a eventos. Com isso, é possível responder a requisições HTTP, entregar imagens salvas no S3 e milhares de outras funcionalidades com o mínimo de código possível. 

- Dentre as principais vantagens podemos citar: desenvolvimento de aplicações com quantidade de código reduzida, escalabilidade estantânea e sem a cobrança pelos recursos ociosos. 

- O Lambda ainda permite a integração com serviços como o DynamoDB, S3 e API Gateway.

# Funções Lambda

- Há 3 principais formas de disparar a execução de funções Lambda: através de rotas HTTP, eventos (que ocorrem em serviços dentro da própria AWS) e pela linha de comando do Serverless Framework.

- As funções Lambda possuem um time out máximo de 15 minutos. 

# Serverless

- Serverless é um modelo de computação em nuvem, que significa "menos servidor", em que o desenvolvedor não precisa se preocupar com a infraestrutura da aplicação. O servidor ainda existe, mas é gerenciado pelo provedor do serviço em nuvem (O AWS Lambda, por exemplo), permitindo que o desenvolvedor foque apenas no software em si. 

- Normalmente as soluções Serverless disponíveis possuem um modelo de execução orientado a eventos. 

- O custo existe de acordo com o que a aplicação utilizar de recursos. 

- Com o Serverless, um evento aciona a execução do código, desta forma o provedor de nuvem aloca os recursos para essa execução de forma dinâmica. Quando uma função termina sua execução, não há mais cobrança. Portanto, o modelo Serverless traz uma boa eficiência e economia, mas também livra os desenvolvedores de tarefas relacionadas ao servidor e a escalabilidade da aplicação, ficando tudo a critério do provedor do serviço.

- As soluções de computação serverless costumam ser divididas em duas categorias: back-end como serviço (BaaS) e função como serviço (FaaS).  

- Função como serviço (FaaS) é um modelo de execução de computação orientado a eventos que são utilizados em aplicações Serverless e são chamadas através de APIs. O Serverless é normalmente utilizado com este modelo, em que os principais provedores de nuvem possuem um serviço como a AWS, com o AWS Lambda, Azure, com o Azure functions, Google Cloud, IBM Cloud Functions e outros.

# CloudFront

# S3

# DynamoDB

# Referências

- Aqui encontra-se todo o material utilizado para estudo e a criação deste resumo.

https://www.treinaweb.com.br/blog/o-que-e-aws-lambda

https://www.alura.com.br/conteudo/serverless-aws-lambda

https://dev.to/feministech/criando-uma-aws-lambda-com-serverless-framework-54ph

https://www.serverless.com/aws-lambda

https://www.youtube.com/watch?v=jiP45rEOEbA

https://www.redhat.com/pt-br/topics/cloud-native-apps/what-is-serverless

https://blog.tecnospeed.com.br/o-que-e-arquitetura-serverless/

https://docs.aws.amazon.com/pt_br/lambda/latest/dg/welcome.html

https://www.youtube.com/watch?v=lEo4bN-2ysQ

https://www.youtube.com/watch?v=ifdV3NuyoBI