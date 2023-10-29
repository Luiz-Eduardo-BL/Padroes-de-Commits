# Guia de Padrão de Commits

Este guia descreve o padrão de commits que estamos usando para manter um histórico organizado e compreensível de alterações no projeto. Siga estas diretrizes ao fazer commits para contribuir com o projeto.

## Padrão de Commits

Nossos commits seguem o padrão **[Conventional Commits](https://www.conventionalcommits.org/pt-br)** para manter um histórico claro e informativo das alterações.

Os padrões de commits são uma convenção simples para ser utilizada nas mensagens de commit. Eles definem um conjunto de regras para criar um histórico de commit explícito, o que facilita a criação de ferramentas automatizadas baseadas na especificação. Esses commits auxiliarão você e sua equipe a entenderem de forma facilitada quais alterações foram realizadas no trecho de código que foi commitado.


## Tipo e descrição

Use um dos seguintes tipos para descrever a natureza da alteração:

| Tipo     | Descrição                                                |
|----------|---------------------------------------------------------|
| `feat`   | Para adicionar uma nova funcionalidade.                  |
| `fix`    | Para correção de bugs.                                   |
| `chore`  | Para tarefas de manutenção, melhorias, organização, etc. |
| `refactor` | Para alterações de código que não adicionam funcionalidades ou corrigem bugs. |
| `style`  | Para alterações na formatação do código, espaçamento, etc. |
| `docs`   | Para alterações na documentação.                         |
| `test`   | Para alterações nos testes.                              |
| `perf`   | Para melhorias de desempenho.                           |
| `build`  | Para alterações no processo de build.                    |
| `raw`    | Para alterações brutas ou não classificadas.             |
| `ci`     | Para alterações relacionadas a integração contínua ou pipelines de CI/CD. |



## Estrutura do Commit

Um commit deve seguir a seguinte estrutura:

```bash
git commit -m "<tipo>(<escopo>): <mensagem>"
- Detalhe 1
- Detalhe 2
```

- O **tipo** indica o tipo de alteração que o commit representa. Veja a seção Tipos de Commit para mais detalhes.
- O **escopo** é opcional e indica o escopo da alteração. Pode ser o nome de um módulo, componente ou funcionalidade do projeto.
- A **mensagem** é uma descrição curta e concisa do que o commit faz. Deve começar com um verbo no imperativo e não terminar com um ponto final.
- Os **detalhes** são opcionais e podem conter informações adicionais sobre o commit, como a motivação, a solução adotada ou as referências utilizadas. Devem ser separados da mensagem por uma linha em branco e podem ter múltiplas linhas.

## Complementos de Commits

Os complementos de commits são opcionais e podem conter informações adicionais sobre o commit, como a motivação, a solução adotada ou as referências utilizadas. Eles devem ser separados da mensagem por uma linha em branco e podem ter múltiplas linhas.

Os complementos devem usar uma linguagem clara, objetiva e informativa. Eles devem explicar o contexto e o raciocínio por trás do commit, bem como os possíveis impactos ou consequências da alteração.

## Exemplos de Commits

A seguir, apresentamos alguns exemplos de commits seguindo o padrão descrito neste guia.

**Adição de Nova Funcionalidade**

```makefile
Commit: feat: Adds search functionality
- Implements interactive search bar
- Adds search filters by category
Resolve a issue #123.
```

**Correção de Bug**

```makefile
Commit: fix(validation): Fixes input validation for user registration
- Resolves issues related to invalid input data
- Improves error handling for registration process
Closes issue #789.
```

**Tarefa de Manutenção**

```makefile
Commit: chore: optimizes imports and code formatting
- Reorganizes imports for better readability
- Adjusts code formatting according to guidelines
```

## Contribuição

Agradecemos contribuições para aprimorar este guia. Para contribuir, siga estas etapas:

1. Fork este repositório.
2. Crie uma branch para sua contribuição: `git checkout -b sua-contribuicao`
3. Faça suas alterações e commit.
4. Envie um pull request para este repositório.

Ao contribuir para este projeto, você concorda com os termos da [Licença MIT](./LICENSE).
