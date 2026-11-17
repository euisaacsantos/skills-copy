---
name: copy-ganchos-headlines
description: Gera ganchos (os 3 primeiros segundos de um anúncio) e headlines (de anúncio e de página) por nível de consciência e por ângulo — erro invisível, custo oculto, segredo da indústria, inimigo comum, frustração de quem já tentou, telepatia, qualificação por intenção, anti-venda, entre outros — com modelos de lacunas e critérios para escolher os melhores. Use quando pedirem "gera ganchos para…", "me dá 20 ganchos de dor", "hooks para o criativo", "headline para a página", "título do anúncio", "abertura do vídeo", "variações de gancho do criativo campeão" ou "que gancho usar para público frio".
---

# Ganchos e headlines

Você escreve a porta de entrada do anúncio e da página. O gancho decide quem para de rolar e quem continua; a headline decide se a pessoa lê o resto. Os dois fazem a mesma coisa em lugares diferentes: declaram, em uma frase, para quem é e por que importa agora.

Base: biblioteca de 146 ganchos e 80 headlines da Kiwify (Renan Matheus), método de gancho da DVN/OnClass (Guilherme Serraglio) e os padrões observados em 119 anúncios analisados. Tudo aqui foi reescrito como modelo próprio; não há cópia literal das planilhas.

## Antes de escrever

1. **Ache o briefing do cliente.** Procure no projeto atual um `copy/briefing-<cliente>.md` (ou equivalente). Se não existir, peça o mínimo: público, produto e preço, a dor principal, a promessa, a causa do problema, as provas REAIS disponíveis e o que já rodou (com o gancho do criativo que mais vendeu, se houver). Para montar um briefing completo, use a skill `copy-criativos-cliente`.
2. **Defina o nível de consciência** do público daquele conjunto de anúncios (inconsciente, consciente do problema, da solução, do produto, totalmente consciente). Leia `references/niveis-e-angulos.md`.
3. **Escolha 2 a 4 ângulos** compatíveis com esse nível. Se existir um criativo campeão, o ângulo dele é o primeiro da lista: variar a porta de entrada de um ângulo que já vende rende mais que inventar ângulo novo.

## Como gerar

1. Para cada ângulo, escreva ganchos a partir dos moldes de `references/modelos-de-ganchos.md`. Preencha as lacunas com as palavras do público (do briefing, de comentários, de perguntas reais), nunca com jargão de marketing.
2. Escreva cada gancho em dois canais, como os anúncios que vendem fazem:
   - **falado** (o que a pessoa diz nos primeiros 3 s, até ~12 palavras);
   - **na tela** (o texto fixo do frame 0, até ~8 palavras, legível sem som).
3. Gere pelo menos o dobro do que vai entregar e corte com o checklist de `references/criterios-e-checklist.md`. Dê nota e mostre só os aprovados.
4. Para headlines (página, título do anúncio, primeira linha do texto principal), use `references/headlines.md`. A headline da página precisa repetir a promessa do anúncio que leva até ela.

## Formato da entrega

Tabela com uma linha por gancho:

| # | Gancho falado (0–3 s) | Texto na tela (frame 0) | Ângulo | Nível de consciência | Formato que combina | Observação |

- "Formato que combina" aponta para a skill `copy-formatos-criativo` (ex.: telepatia, caixinha, certo vs errado).
- "Observação" traz o risco (política, compliance, número que precisa de confirmação) ou a variação sugerida.
- Para headlines: headline, subheadline (quando for página), nível e qual anúncio ela casa.

## Regras que valem sempre

- **Especificidade vence.** Número, cena, palavra que só o público usa. Gancho genérico ("isso mudou minha vida") só funciona colado num formato muito forte.
- **Filtre o público no gancho.** O gancho é também segmentação: quem não é o público deve sair cedo, e isso barateia o resultado bom.
- **Uma ideia por gancho.** Se precisa de vírgula e "e" para fazer sentido, são dois ganchos.
- **Gancho combina com o ângulo do roteiro.** Gancho de erro invisível com roteiro de oferta direta quebra a promessa; use categorias iguais ou vizinhas.
- **Não repita aberturas queimadas.** Se o briefing lista ganchos que já rodaram muito, não reescreva a mesma frase com sinônimo; mude a cena.
- **Para testar gancho, mude só o gancho.** Mesmo miolo, mesma CTA, 3 a 5 aberturas diferentes. A métrica é a taxa de gancho (visualizações de 3 s ÷ impressões) e, depois, o custo do resultado bom.

## Compliance (curto)

- **Advocacia anunciando para cliente final** (Código de Ética e Disciplina da OAB e Provimento 205/2021): o formato e o gancho de dor servem, mas sem promessa de resultado, sem preço ou condição de pagamento, sem sensacionalismo, sem caso concreto de cliente e sem autoengrandecimento. Gancho de "erro invisível" vira informação ("três sinais de que…"), nunca "ganhe sua causa".
- **Infoproduto e qualquer anúncio na Meta**: nada de afirmar atributo pessoal do espectador ("você está endividado?", "você tem depressão?"), antes e depois corporal, promessa de renda ou cura. Fale da situação ou da prática ("quem paga fornecedor no cartão…"), não da condição da pessoa.
- **Nenhum número inventado.** Número no gancho só se estiver no briefing como confirmado. Se o cliente não confirmou, escreva o gancho sem o número e marque a lacuna.

## Referências

- `references/niveis-e-angulos.md` — os 5 níveis de consciência, o que cada um precisa ouvir e os ângulos (mecanismos psicológicos) com quando usar e o risco de cada um.
- `references/modelos-de-ganchos.md` — moldes com lacunas, agrupados por ângulo, com nível e "também serve como".
- `references/headlines.md` — moldes de headline por foco (problema, solução, produto, oferta, genérica), headline de página × título de anúncio, e como casar anúncio e página.
- `references/criterios-e-checklist.md` — checklist de corte, nota de 0 a 2 por critério, sinais de gancho fraco e como testar.

Skills vizinhas: `copy-formatos-criativo` (a embalagem do gancho), `copy-roteiro-anuncio` (o que vem depois dos 3 s), `copy-pagina-low-ticket` (headline e bullets da página) e `copy-criativos-cliente` (o fluxo completo para um cliente).
