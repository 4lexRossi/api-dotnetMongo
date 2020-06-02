<h1 align="center">Curso DIO Pro - Construindo um projeto de uma API.NET integrada ao MongoDB</h1>

Esse repo é uma live coding para DIO - Pro
[Digital Innovation One](https://digitalinnovation.one/sign-up?ref=QFX2ZVP4RU)
uma incrivel aula ministrada por [Gabriel Faraday](https://www.linkedin.com/in/gabrielfbarros/)

## clone o repositório 

`git clone https://github.com/4lexRossi/api-dotnetMongo.git`

## Requisitos minimos
dotnet versão 3.1.300
Uma IDE de sua preferência

## Instalar dependências
```
    dotnet add package MongoDB.Driver
```

Criar uma conta no [MongoDB](https://www.mongodb.com/)
Após a criação terá que alterar o campo 
`"ConnectionString": "mongodb+srv://seu_usuario:sua_senha@dotnet-mongo-seu_usuario-v5slk.gcp.mongodb.net/test?retryWrites=true&w=majority"`
no arquivo `appsettings.json`

## Para iniciar o servidor, use o comando:

```
   dotnet run
```
## Testando a Api:

Através do `POSTMAN` pode testar os métodos `Post`, `Get`, `Put` e `Delete`

## através do endereço  e modelo abaixo

https://localhost:5001/infectado

```json
{
	"dataNascimento": "1990-03-01",
	"sexo": "M",
	"latitude": -23.5630994,
	"longitude": -46.6565712
}
```


Links Uteis:

- .net core - https://dotnet.microsoft.com/download

- visual code - https://code.visualstudio.com/download

- postman - https://www.postman.com/downloads/

- mongo atlas - https://www.mongodb.com/cloud/atlas/register


-----------------------------------------------

Referências:

https://docs.mongodb.com/

https://docs.mongodb.com/manual/

https://docs.mongodb.com/ecosystem/drivers/csharp/

https://docs.atlas.mongodb.com/
