# Data Quality Toolkit

Toolkit pequeno e explicável para validar contratos de dados antes de alimentar análises e dashboards.

> O projeto não inclui dados proprietários; os exemplos são sintéticos.

## Pergunta analítica

Como detectar cedo colunas ausentes, valores nulos, duplicidades e violações de domínio?

## Roadmap

- [x] Checagens de schema e completude.
- [x] Funções determinísticas e testes unitários.
- [ ] Relatório HTML de qualidade.
- [ ] Integração com Great Expectations ou alternativa equivalente.
- [ ] CI para bloquear contratos inválidos.

## Executar localmente

```bash
python -m pytest
```

## Princípios

Cada check deve ser rastreável, reproduzível e acompanhado de uma decisão: bloquear, alertar ou aceitar com justificativa. Não inclua dados pessoais, credenciais ou amostras protegidas.
