# Atividade 06

## ASP.NET Core e Redis

Criar um projeto ASP.NET Core Web API no Visual Studio. 

No link abaixo existem informações para a configuração da conexão com o Redis.

- [Cache Redis distribuído](https://docs.microsoft.com/pt-br/aspnet/core/performance/caching/distributed?view=aspnetcore-2.2#distributed-redis-cache)

Abaixo um exemplo de implementação do Redis.

- [ASP.NET Core 2.0: implementando cache em APIs REST](https://medium.com/@renato.groffe/asp-net-core-2-0-implementando-cache-em-apis-rest-cd2df219f13b)

A Web API a ser desenvolvida ao ser chamada verifica que se a informação está armazenada no Redis, caso não exista o cache, ele busca a informação de um personagem de Star Wars, e armazena no Redis.

Implemente a Web API recebendo um parâmetro Id que será passado para a chamada a API https://swapi.co/api/people/{id}. O retorno será o JSON retornado pela api consultada.

Após terminar de desenvolver a Web API, teste usando o Postman e o FastoRedis para verificar se os valores estão sendo gravados no Redis.

