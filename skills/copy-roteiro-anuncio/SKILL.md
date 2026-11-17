---
name: copy-roteiro-anuncio
description: Escreve roteiros de anúncio em vídeo (Reels, Stories, Feed) com a estrutura gancho → promessa → mecanismo → prova → objeções → CTA, em famílias por nível de consciência (problema-solução, segredo, história, promessa, oferta), com modelos de lacunas, regras de duração, leitura em voz alta, ficha de produção e variações a partir de um criativo validado. Use quando pedirem "roteiro de anúncio", "escreve o vídeo do criativo", "roteiro para o Reels", "roteiro de 45 segundos", "adapta esse roteiro para outro formato", "variações do criativo campeão" ou "revisa esse roteiro".
---

# Roteiro de anúncio

Você escreve o que é dito e mostrado depois do gancho. O formato atrai, o gancho para, o roteiro vende. (Base: os 5 elementos e os 99 roteiros em 5 famílias da Kiwify; a estrutura de ouro gancho → conteúdo → chamada e as particularidades de low ticket da OnClass; a anatomia dos 119 anúncios do DVN.)

## Entradas mínimas

- Briefing do cliente (de preferência `copy/briefing-<cliente>.md` no projeto; se não houver, use a skill `copy-criativos-cliente` para montar ou peça: público, dor, causa, promessa, mecanismo, produto e preço, provas reais, objeções, CTA e destino).
- Nível de consciência do público e o ângulo.
- Gancho (da skill `copy-ganchos-headlines`) e formato (da skill `copy-formatos-criativo`).

## Procedimento

1. **Escolha a família** pelo nível de consciência (`references/familias-de-roteiro.md`): segredo e história para frio; problema-solução para frio e morno; promessa para morno; oferta para quente.
2. **Monte o esqueleto** com os blocos de `references/estrutura-e-regras.md`: gancho, identificação/dor, mecanismo do problema, mecanismo da solução, prova, objeções, produto, CTA com valor embutido. Em low ticket, o produto é a solução e o preço aparece.
3. **Preencha com o banco de respostas do briefing** (as lacunas). Nada de número, depoimento ou resultado que não esteja confirmado.
4. **Adapte ao formato:** quem fala, em que ordem, onde entra a objeção (na boca de um personagem? numa caixinha? num print?), e a duração típica do formato.
5. **Escreva em blocos de tempo** `[0–3 s]`, `[3–10 s]`… com a fala e, ao lado, o que aparece na tela.
6. **Escreva a ficha "Como fica na tela"** e a lista "o que gravar / o que editar" (modelo na skill `copy-formatos-criativo`, `references/ficha-como-fica-na-tela.md`).
7. **Revise** com `references/leitura-e-revisao.md`: leitura em voz alta cronometrada, checklist, voz do especialista, compliance.
8. **Entregue também** a copy do anúncio (texto principal e título) e, quando pedido, variações (`references/variacoes.md`).

## Formato de entrega de cada roteiro

```
## [código] · [formato] · [ângulo] · [nível] · [duração alvo]
**Por que este:** 1–2 linhas (o que o gancho filtra, o que a peça testa)
**Roteiro**
[0–3 s] Fala: "…"            | Tela: …
[3–10 s] Fala: "…"           | Tela: …
…
**Como fica na tela** (ficha)
**O que gravar / O que editar**
**Copy do anúncio:** texto principal (1ª linha = gancho) · título (até ~40 caracteres)
**Cuidados:** números a confirmar, autorizações, compliance
```

## Regras que valem sempre

- **Uma ideia por roteiro.** Um erro, uma promessa, uma oferta.
- **Gancho → dor → causa → saída → prova → produto → CTA.** A ordem pode mudar no formato (o diálogo põe a objeção antes da prova), mas nenhum bloco some, exceto prova quando não há prova real (aí use prova lógica e autoridade verificável).
- **CTA com uma ação só**, falada pelo menos duas vezes, nomeando o botão e onde ele está, com valor embutido (o que a pessoa encontra ao clicar).
- **Curto por padrão:** 30 a 60 s (≈ 75 a 150 palavras faladas a ~150 palavras/min). Mais longo só com motor de retenção e público que tolera (mais velho, nicho técnico).
- **Fala de gente, não de anúncio.** Frases curtas, a palavra do público, sem "imperdível", "transforme sua vida", "fórmula", "segredo revelado".
- **Low ticket:** diga o que é o entregável e como funciona; prova social é quase obrigatória (mesmo indireta); fale o preço (exato até ~R$ 67; acima, "menos de R$ 100"); tela final com promessa e preço.

## Compliance (curto)

- **Advocacia para cliente final** (Código de Ética da OAB e Provimento 205/2021): roteiro informativo; sem promessa de resultado, sem preço ou forma de pagamento, sem caso concreto de cliente, sem autoengrandecimento, sem pressa ou escassez. A CTA convida a entender a situação, não a "garantir" um resultado.
- **Infoproduto e demais anúncios na Meta**: sem antes e depois pessoal, sem afirmar atributo pessoal do espectador, sem promessa de renda ou cura, sem escassez ou preço riscado falsos.
- **Nenhum número inventado.** Prova só com dado real do cliente; o que estiver "a confirmar" no briefing fica fora do roteiro ou entra como lacuna marcada.

## Referências

- `references/estrutura-e-regras.md` — os blocos, as regras de CTA, low ticket, duração e ritmo de fala.
- `references/familias-de-roteiro.md` — esqueletos com lacunas por família e nível (escritos para esta skill).
- `references/leitura-e-revisao.md` — leitura em voz alta, checklist, erros comuns e a ficha de produção.
- `references/variacoes.md` — como lateralizar um criativo validado, prompt de adaptação de formato e rotina de variação.

Skills vizinhas: `copy-ganchos-headlines`, `copy-formatos-criativo`, `copy-pagina-low-ticket`, `copy-criativos-cliente` e, para produção, `editar-criativos`.
