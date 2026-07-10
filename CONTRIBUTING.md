# Contribuindo

Este arquivo é o padrão org-wide para **marcovillar-consultoria**. Qualquer
repositório sem seu próprio `CONTRIBUTING.md` herda estas convenções.

## Fluxo

1. Trabalhe em um branch a partir da `main` (nunca commite direto na `main`).
2. Abra um PR usando o template — preencha **Resumo** e **Como testar**.
3. O PR precisa do CI verde e de 1 review aprovado antes do merge.

## Convenções

- **Idioma:** código, nomes de arquivo e frontmatter em EN-US; prosa, título e
  corpo de PR e mensagens de commit em PT-BR (protocolo de idiomas em
  `openfathom-meta`).
- **Commits:** [Conventional Commits](https://www.conventionalcommits.org) —
  prefixo de tipo em EN (`feat`, `fix`, `docs`, `chore`...), descrição em PT-BR.
- **Decisões de arquitetura:** registre um ADR quando a mudança alterar
  topologia, dependências ou trade-offs relevantes.
- **Segredos:** nunca commite credenciais ou valores específicos de ambiente.

## Segurança

Para reportar vulnerabilidades, veja `SECURITY.md` — não abra issue pública.
