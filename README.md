# Margin Edge — releases oficiais

Canal público exclusivo para distribuição dos instaladores do Margin Edge.
O código-fonte, configurações e segredos permanecem nos repositórios privados.

## Download

- Instalador Web: `Margin-Edge-Web-Setup.exe`
- Instalador offline: `Margin-Edge-Setup.exe`
- Manifesto de atualização: `margin-edge-release.json`

Os nomes dos assets são estáveis. Cada publicação utiliza uma tag versionada e imutável;
as URLs em `/releases/latest/download/` apontam automaticamente para a versão marcada como Latest.

O instalador Web baixa o pacote offline exclusivamente por HTTPS e valida o SHA-256 fixado em sua
compilação. O atualizador consulta o manifesto, valida o SHA-256 e aplica as verificações de assinatura
configuradas no terminal antes de executar uma nova versão.

## Integridade

Confira o SHA-256 publicado na release antes de distribuir manualmente um instalador. Releases de
produção devem utilizar assinatura Authenticode com timestamp.
