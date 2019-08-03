# Atividade 02

## Implicações das 8 falácias da computação distribuída

Nesta atividade vamos tentar explorar um pouco quais são as implicações das 8 falácias no desenho de uma aplicação que deve ser executada na nuvem.

- Quais itens dos 8 pontos podem ser atacados no momento do desenho da aplicação, para diminuir os impactos deles? Quais técnicas o desenvolvedor deve usar?
  
| Falácia                                | O que pode ser feito                                                                                          |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| A rede é confiável                     |                                                                                                               |
| A latência é zero                      |                                                                                                               |
| A largura de banda é infinita          |                                                                                                               |
| A rede é segura                        | Exemplo: não armazernar informações de conexão em arquivos, utilizar cofres de chaves como o Azure Key Vault  |
| A topologia da rede nunca muda         | Exemplo: não utilizar IPs fixos na configuração de acesso a algum serviço externo, usar o nome DNS do serviço |
| Existe um administrador                |                                                                                                               |
| Custo de transferência de dados é zero |                                                                                                               |
| A rede é homogênea                     |                                                                                                               |

- [Explicando as falácias](pdfs/explicando_falacias.pdf)

Próxima: [Atividade 03](03-atividade.md)