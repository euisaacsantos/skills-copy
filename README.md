# Skills de copy

Cinco skills do Claude Code para criar copy e criativos de tráfego pago para clientes. Foram escritas com palavras próprias a partir de cursos de copy: Combo 7 Bibliotecas, de Renan Matheus, e 50 Formatos que Escalam, de Guilherme Serraglio (DVN). O material dos cursos não está neste repositório.

## As skills

| Skill | Para que serve |
|---|---|
| `copy-criativos-cliente` | É a porta de entrada: "cria criativos para o cliente X". Monta o briefing do cliente em `copy/briefing-<cliente>.md` no projeto, chama as outras quatro, checa as regras da OAB e da Meta e só aceita números reais. |
| `copy-ganchos-headlines` | Ganchos e headlines por nível de consciência e por ângulo. |
| `copy-formatos-criativo` | 76 formatos de criativo, cada um com a descrição de como fica na tela. |
| `copy-roteiro-anuncio` | Roteiros de anúncio: 34 modelos em 5 famílias, mais as variações de um criativo que já funcionou. |
| `copy-pagina-low-ticket` | Página de venda curta (R$ 10 a R$ 100) em 15 seções, com checklist. |

## Como instalar

Para valer em todos os projetos da máquina:

```bash
git clone https://github.com/euisaacsantos/skills-copy.git
cp -R skills-copy/skills/copy-* ~/.claude/skills/
```

Para valer só num projeto, copie as pastas para `.claude/skills/` dentro dele. As skills não dependem dos arquivos dos cursos.

## Como usar

Peça ao Claude Code, por exemplo: "cria criativos para o cliente X", "gera 20 ganchos de dor para o produto Y" ou "revisa a página de vendas de R$ 47". Na primeira vez para um cliente, a skill pergunta o que falta no briefing e o salva no projeto.

Quando a regra de um curso bater de frente com o dado medido do cliente, vale o dado do cliente. Registre o conflito na entrega.
