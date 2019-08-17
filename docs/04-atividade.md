# Atividade 04

## Proxy Reverso

Nesta atividade vamos configurar um proxy reverso para uma aplicação .NET Core.

![Proxy Reverso](imagens/kestrel-to-internet.png)

Mais informações:
- [Kestrel com Proxy Reverso](https://docs.microsoft.com/pt-br/aspnet/core/fundamentals/servers/kestrel?view=aspnetcore-2.2#when-to-use-kestrel-with-a-reverse-proxy)

Crie uma pasta chamada Handoncloud na raiz da sua unidade de disco C: ou D:, dentro dela crie uma pasta chamada Atividade4.




Ao executar o comando `docker network ls`, será listado a rede **atividade4_proxygx-network**.

```bash
C:\HandsOnCloud\Atividade4
λ  docker network ls
NETWORK ID          NAME                         DRIVER              SCOPE
82bc1989fe15        atividade4_proxygx-network   bridge              local
3cd62acdca03        bridge                       bridge              local
308f174ba3a3        host                         host                local
f03e2c44fa09        none                         null                local
```

Ao executar o comando `docker-compose ps` serão listados os contêineres criados.

```bash
C:\HandsOnCloud\Atividade4
λ docker-compose ps
       Name                     Command               State           Ports
-----------------------------------------------------------------------------------
atividade4_apigx_1   dotnet bin/GxNetCoreStartu ...   Up      0.0.0.0:20001->80/tcp
atividade4_proxy_1   nginx -g daemon off;             Up      0.0.0.0:20000->80/tcp
```

Próxima: [Atividade 03](03-atividade.md)