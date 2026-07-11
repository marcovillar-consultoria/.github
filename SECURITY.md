# Política de Segurança

Este arquivo é o padrão org-wide para **marcovillar-consultoria**. Qualquer repositório sem seu próprio `SECURITY.md` herda esta política.

## Como reportar uma vulnerabilidade

Reporte suspeitas de vulnerabilidade de forma privada — não abra uma issue pública.

- E-mail: **marco@marcovillar.com**
- Resposta inicial esperada em até 5 dias úteis.
- Inclua o repositório afetado, uma descrição do problema e passos de reprodução, se disponíveis.

## Correção e divulgação

Sendo um operador solo, não há SLA formal de correção — a prioridade depende da severidade e do repositório afetado (repos privados sem exposição externa real recebem prioridade menor que os públicos). Reportes recebem um retorno com o prazo estimado assim que triados. Divulgação pública, se houver, só acontece depois da correção estar disponível, e é coordenada com quem reportou.

## Nota de escopo para repositórios forkados

Repositórios que são forks mínimos de projetos upstream (ex. `openfathom-agent`, fork de [`NousResearch/hermes-agent`](https://github.com/NousResearch/hermes-agent)) aceitam reportes apenas para as mudanças específicas do fork mantidas aqui. Vulnerabilidades no código upstream não modificado devem ser reportadas diretamente no repositório de origem.
