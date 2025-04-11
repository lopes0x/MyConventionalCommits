# Padrão de Commits

Este repositório documenta um padrão simples e eficaz para mensagens de commit, com foco em clareza, organização e boas práticas.

## Por Que Usar Um Padrão?

Adotar um padrão facilita a leitura do histórico do projeto, melhora a colaboração em equipe e torna o versionamento mais profissional.

## Regras Gerais

- Use mensagens **curtas, claras e diretas**.
- Comece sempre com o **tipo do commit** com a **letra inicial maiúscula**.
- Escreva em **português** sempre que possível.
- Não use ponto final na mensagem.

## Tipos de Commit

| Tipo       | Descrição |
|------------|-----------|
| `Feat`     | Nova funcionalidade |
| `Fix`      | Correção de bug |
| `Docs`     | Alterações na documentação |
| `Style`    | Ajustes de formatação e estilo (sem impacto na lógica) |
| `Refactor` | Melhorias no código sem alterar funcionalidades |
| `Test`     | Adição ou modificação de testes |
| `Chore`    | Tarefas de manutenção (ex: atualizar pacotes) |
| `Ci`       | Alterações em configurações de integração contínua |

## Exemplo de Commits

```bash
git commit -m "Feat: Adicionar botão de logout na navbar"
git commit -m "Fix: Corrigir erro de validação no formulário"
git commit -m "Docs: Atualizar instruções no README"
git commit -m "Style: Ajustar padding dos cards"
git commit -m "Refactor: Separar lógica de autenticação em serviço próprio"
git commit -m "Test: Criar testes para serviço de login"
git commit -m "Chore: Atualizar dependências do projeto"
