# Security Policy

## Reportar Vulnerabilidades

Envie e-mail para **everton.sefh@gmail.com** com:
- Descrição do problema
- Passos para reproduzir
- Impacto estimado

Resposta em até **72 horas**.

## Postura de Segurança

### Assinatura de Commits

Todos os commits deste repositório são assinados com GPG.

Verificar:

    git log --show-signature

Chave pública: `F9C2CAC4F61EED6D`

### Dependências

- Zero dependências externas no frontend
- Nenhum `npm install` necessário
- Nenhum script de terceiros carregado

### Boas Práticas Implementadas

- [x] HTTPS obrigatório em produção
- [x] Commits assinados com GPG Ed25519
- [x] Sem `eval()` no código
- [x] Sanitização de input do usuário
- [x] CSP restritiva
- [x] Sem cookies de tracking por padrão

## Escopo

Este repositório é um **MVP acadêmico**. Em produção, considerar:
- Backend com autenticação real
- Rate limiting server-side
- Verificação de identidade (KYC)
- LGPD compliance completo
