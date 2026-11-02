# .github

Arquivos padrão de comunidade da conta `b-dantas`. Os templates de issue em
`.github/ISSUE_TEMPLATE/` e o de pull request em `.github/PULL_REQUEST_TEMPLATE.md`
valem para todo repositório desta conta que não tenha os seus próprios.

Cinco tipos de issue: Bug, Feature, Chore, Docs e Ideia (pensamento inacabado,
que se desdobra em outras issues). Cada template aplica uma label: `bug`,
`enhancement`, `chore`, `documentation` e `ideia`. As três primeiras e
`documentation` o GitHub cria por padrão; `chore` e `ideia` precisam existir no
repositório, senão o GitHub as ignora em silêncio:

```sh
gh label create chore -R <owner>/<repo> -c c5def5 -d "Manutenção que não muda comportamento para quem usa"
gh label create ideia -R <owner>/<repo> -c D4C5F9 -d "Pensamento inacabado ou épico; desdobra em outras issues"
```

Convenções específicas de um projeto (comandos de verificação, pastas, outras
labels) ficam no repositório dele.
