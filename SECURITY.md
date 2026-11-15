# Política de segurança

## Versões com suporte

Recebem correções de segurança a versão mais recente publicada e a branch `main`. Versões anteriores só em casos críticos, a critério dos mantenedores.

## Como reportar uma vulnerabilidade

Não abra issue, pull request ou discussão pública para vulnerabilidades. Use o relato privado do GitHub: aba [Security](https://github.com/pedroiff0/guia-elixo/security) e botão "Report a vulnerability".

Inclua no relato:

- descrição do problema e impacto;
- passos para reproduzir ou prova de conceito mínima;
- versão ou commit afetado;
- sugestão de correção, se houver.

## O que esperar

| Etapa | Prazo alvo |
| :--- | :--- |
| Confirmação de recebimento | 7 dias |
| Avaliação inicial e classificação | 14 dias |
| Correção ou plano de mitigação | 30 dias para severidade alta ou crítica |

Você será mantido informado e, se desejar, creditado no aviso público após a correção. Pedimos divulgação coordenada: aguarde a correção antes de tornar o problema público.

## Boas práticas para quem usa o projeto

- Nunca versione `.env`, chaves, tokens ou certificados; use `.env.example` apenas com valores fictícios.
- Mantenha as dependências atualizadas (o Dependabot, quando ativo, abre os pull requests).
- Rotacione imediatamente qualquer credencial que tenha vazado.
