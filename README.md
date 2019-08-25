# Hands-On Cloud Native e Genexus

Hands-On para introdução dos conceitos da arquitetura Cloud Native e sua utilização com o Genexus.

Para este Hands-On vamos utilizar o Docker para criar os ambientes de testes. Não é necessário conhecimento anterior em Docker para executar o Hands-On.

### Instalando o Docker

Inicialmente é necessário configurar o ambiente para trabalharmos com o Docker e Genexus. Vamos instalar o Docker Desktop for Windows na mesma máquina que tem o Genexus  instalado.

O primeiro passo é ler a documentação do Docker que explica os requisitos para a instalação do Docker Desktop for Windows:

- [Requisitos para o Docker Desktop for Windows](https://docs.docker.com/docker-for-windows/install/#what-to-know-before-you-install)

Um ponto importante dos requisistos é a questão da configuração do Hyper-V no Windows se ele já não estiver configurado. O link abaixo explica como configurar o Hyper-V no Windows 10.

- [Configuração do Hyper-V](https://docs.docker.com/docker-for-windows/troubleshoot/#virtualization)

Após a leitura e configuração dos requisitos, agora é fazer o download do Docker Desktop for Windows e a instalação, para isso siga as instruções do link abaixo:

- [Download do Docker Desktop for Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows)

Com isso temos o ambiente preparado para executar os contêineres Docker.

## Genexus e Gerador .NET 

Para este Hands-On vamos utilizar também o Genexus 16 e gerador .NET.

Próximo: [Atividade 01](docs/01-atividade.md)