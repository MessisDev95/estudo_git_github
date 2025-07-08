# 📘 Guia de Padrões de Commits

Este guia define os padrões utilizados para escrever mensagens de commit claras, organizadas e padronizadas no projeto, seguindo o modelo dos **Conventional Commits**.

---

## ✅ Estrutura do Commit

```
<tipo>(<escopo opcional>): <mensagem clara no imperativo>
```

### Exemplo:
```
feat(login): adicionar validação de senha
```

---

## 🧩 Tipos de Commits

| Tipo        | Quando usar                                                   |
|-------------|---------------------------------------------------------------|
| `feat`      | Adição de nova funcionalidade                                 |
| `fix`       | Correções de bugs                                             |
| `docs`      | Alterações na documentação (README, Wiki etc.)                |
| `style`     | Ajustes de estilo/código que **não alteram comportamento**    |
| `refactor`  | Refatoração de código (sem alteração de funcionalidade)       |
| `test`      | Adição ou modificação de testes                               |
| `chore`     | Tarefas de manutenção ou configs (build, dependências)        |
| `build`     | Alterações no processo de build ou ferramentas                |
| `ci`        | Configurações de integração contínua (GitHub Actions, etc.)   |
| `perf`      | Melhorias de performance                                      |

---

## 🎯 Escopos Comuns (opcional)

Use um escopo para especificar a parte afetada do projeto:

- `login`
- `usuario`
- `api`
- `dashboard`
- `config`
- `db` (banco de dados)

**Exemplo com escopo:**

```
fix(usuario): corrigir erro ao editar perfil
```

---

## 🚫 Evite mensagens genéricas como:

- `update`
- `teste`
- `arrumando`
- `mudanças feitas`
- `commit final`

Essas mensagens tornam o histórico confuso e pouco útil.

---

## 💬 Boas práticas

- Use verbos no **imperativo**: `adicionar`, `corrigir`, `remover`, etc.
- Seja claro e direto.
- Commits pequenos e focados (um assunto por vez).
- Use inglês se o projeto for internacional.

---

## 💡 Exemplos práticos

\`\`\`bash
git commit -m "feat(auth): criar tela de login"
git commit -m "fix(api): corrigir erro 500 ao salvar usuário"
git commit -m "docs: adicionar instruções de instalação no README"
git commit -m "refactor: reorganizar funções da tela inicial"
git commit -m "style: remover console.log desnecessário"
git commit -m "chore: atualizar dependências do projeto"
\`\`\`

---

Feito com 💻 por Messis e equipe.
