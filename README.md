# Serveless Static Web App on AWS

Aplicação web sem servidor gerenciado pelos serviços da AWS.

## Sobre a aplicação

É um sistema de aluguel de unicórnios onde o usuário, após se registrar, passa as coordenadas e realiza a solicitação do seu unicórnio. 

## Andamento  ![](https://geps.dev/progress/100?successColor=006600)

[Módulo 1: Hospedar um site estático](https://aws.amazon.com/pt/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/module-1/)
    
- [x] Feito?
- [Site](https://main.d3jsf80xkb0tkt.amplifyapp.com/)

[Módulo 2: Gerenciar usuários](https://aws.amazon.com/pt/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/module-2/)

- [x] Feito?

[Módulo 3: Criar um backend sem servidor](https://aws.amazon.com/pt/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/module-3/)

- [x] Feito?

[Módulo 4: Implantar uma API RESTful](https://aws.amazon.com/pt/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/module-4/)

- [x] Feito?

[Módulo 5: Limpeza de recurso](https://aws.amazon.com/pt/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/module-5/)

- [x] Feito?


## Problemas

### Módulo 1: Hospedando o site estático no AWS Amplify

Aparentemente, o bucket público que preenche o repositório não existe mais e o tutorial não foi atualizado. Para prosseguir com o tutorial, ao invés de copiar com o seguinte comando:

    aws s3 cp s3://wildrydes-us-east-1/WebApplication/1_StaticWebHosting/website ./ --recursive

Utilize este comando:

    aws s3 cp s3://ttt-wildrydes/wildrydes-site ./ --recursive

Para saber mais, acompanhe a [issue](https://github.com/aws-samples/aws-serverless-workshops/issues/292).

### Módulo 4: Implementando a API 

Tutorial desatualizado em algumas etapas passo 7: "Selecione POST na nova lista suspensa que aparece em OPÇÕES e, em seguida, selecione o ícone de marca de seleção.", não aparece esse ícone. 

Ao validar a implementação, não é possível fazer o request do unicórnio, pois, pelo o que eu entendi, o token não está sendo passado corretamente.


## Melhorias

- [Configurar um domínio personalizado no AWS Amplify](https://docs.aws.amazon.com/amplify/latest/userguide/custom-domains.html)
- Criar uma página de login

## Links e Referências

- [Markdown Progress](https://github.com/gepser/markdown-progress)
- [Página do Tutorial](https://aws.amazon.com/pt/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/)
