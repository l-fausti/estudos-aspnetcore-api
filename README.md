Projeto de estudos em ASP.NET Core (.NET 8) com foco em Web API usando Controllers.

## 🎯 Objetivo

Praticar a criação de APIs REST com ASP.NET Core: rotas, controllers, Swagger e boas práticas iniciais.

## 🛠️ Tecnologias

- .NET 8
- ASP.NET Core Web API
- Swashbuckle (Swagger)

## 📋 Endpoints

### WeatherForecast
- `GET /WeatherForecast` — retorna previsão do tempo aleatória (endpoint padrão do template)

### Usuario
- `GET /Usuario/ObterDataHoraAtual` — retorna data e hora atuais do servidor
- `GET /Usuario/Apresentar/{nome}` — retorna uma mensagem de boas-vindas personalizada

## ▶️ Como rodar

\`\`\`bash
dotnet watch run
\`\`\`

Depois acesse o Swagger em:
\`\`\`
http://localhost:{porta}/swagger
\`\`\`

## 📌 Status

Projeto para fins de estudo.