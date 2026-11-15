# Contribuindo com Guia Elixo

Obrigado pelo interesse em contribuir. Este guia explica como propor mudanças de forma que sejam revisadas e integradas rapidamente.

## Antes de começar

- Procure uma [issue](https://github.com/pedroiff0/guia-elixo/issues) existente sobre o assunto. Se não houver, abra uma descrevendo o problema ou a ideia antes de escrever código grande.
- Leia o [Código de Conduta](CODE_OF_CONDUCT.md). Ao participar, você concorda em segui-lo.
- Vulnerabilidades não vão em issue pública: use o processo de [SECURITY.md](SECURITY.md).

## Preparando o ambiente

1. Faça um fork e clone: `git clone https://github.com/<seu-usuario>/guia-elixo.git`.
2. Siga a seção "Trabalhando no projeto" do [README](README.md) para instalar dependências e rodar os testes.
3. Confirme que a suíte passa antes de mexer em qualquer coisa.

## Fluxo de contribuição

1. Crie uma branch a partir de `main` com nome curto e descritivo: `feat/exportar-csv`, `fix/erro-login`, `docs/guia-deploy`.
2. Faça commits pequenos e coesos no padrão [Conventional Commits](https://www.conventionalcommits.org/pt-br/): `feat:`, `fix:`, `docs:`, `refactor:`, `test:`, `chore:`.
3. Adicione ou ajuste testes para o comportamento alterado.
4. Atualize a documentação e a seção `Unreleased` do [CHANGELOG.md](CHANGELOG.md).
5. Rode lint e testes localmente.
6. Abra o pull request com o modelo do repositório, descreva o que mudou e por quê, e vincule a issue (`Closes #123`).

## Critérios de revisão

- A mudança resolve um problema claro e tem escopo pequeno.
- Testes passam e o CI está verde.
- Sem segredos, dados pessoais ou arquivos gerados no diff.
- Estilo consistente com o código existente (veja `.editorconfig`).

## Reportando problemas

Use o formulário de [nova issue](https://github.com/pedroiff0/guia-elixo/issues/new/choose). Informe versão, sistema operacional, passos para reproduzir, resultado esperado e resultado obtido. Logs ajudam, mas remova qualquer dado sensível antes de colar.

## Dúvidas

Veja [SUPPORT.md](SUPPORT.md).
