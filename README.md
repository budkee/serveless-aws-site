# Serveless Static Web App on AWS

Aplicação web sem servidor através dos serviços da AWS.

- [Página do Tutorial](https://aws.amazon.com/pt/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/)

## Problemas

Aparentemente, o bucket público que preenche o repositório não existe mais e o tutorial não foi atualizado. Para prosseguir com o tutorial, ao invés de copiar com o seguinte comando:

    aws s3 cp s3://wildrydes-us-east-1/WebApplication/1_StaticWebHosting/website ./ --recursive

Utilize este comando:

    aws s3 cp s3://ttt-wildrydes/wildrydes-site ./ --recursive

Para saber mais, acompanhe a [issue](https://github.com/aws-samples/aws-serverless-workshops/issues/292).

